<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Berfin English</title>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body class="bg-white text-gray-800 scroll-smooth">

    <!-- NAVIGATION -->
    <header class="fixed top-0 left-0 right-0 bg-white shadow-md z-50">
      <nav class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
        <h1 class="text-2xl font-bold">Berfin English</h1>
        <ul class="hidden md:flex space-x-6 font-medium">
          <li><a href="#about" class="hover:text-blue-600">About</a></li>
          <li><a href="#services" class="hover:text-blue-600">Services</a></li>
          <li><a href="#contact" class="hover:text-blue-600">Contact</a></li>
        </ul>
        <div class="md:hidden">
          <button id="menu-btn" class="focus:outline-none">
            <svg class="w-6 h-6" fill="none" stroke="currentColor"
              viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <path stroke-linecap="round" stroke-linejoin="round"
                stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
            </svg>
          </button>
        </div>
      </nav>
      <ul id="mobile-menu" class="hidden md:hidden px-4 pb-4 space-y-2">
        <li><a href="#about" class="block">About</a></li>
        <li><a href="#services" class="block">Services</a></li>
        <li><a href="#contact" class="block">Contact</a></li>
      </ul>
    </header>

    <!-- HERO -->
    <section class="pt-28 pb-20 bg-gradient-to-r from-blue-400 to-blue-600 text-white text-center">
      <div class="max-w-2xl mx-auto px-4">
        <h2 class="text-4xl font-bold mb-4">Welcome to Berfin English</h2>
        <p class="text-lg">Personalized English lessons to help you speak confidently.</p>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="scroll-mt-20 py-16 px-4 max-w-5xl mx-auto">
      <h3 class="text-3xl font-bold mb-6 text-center">About Me</h3>
      <p class="text-lg text-center mb-6">
        I’m Berfin, an experienced English teacher who helps students gain fluency and confidence. Whether you're learning for travel, work, or exams, I tailor lessons to your goals.
      </p>
      <div class="flex flex-wrap justify-center gap-8 mt-8">
        <div class="text-center">
          <h4 class="text-2xl font-semibold">5+</h4>
          <p>Years Teaching</p>
        </div>
        <div class="text-center">
          <h4 class="text-2xl font-semibold">200+</h4>
          <p>Happy Students</p>
        </div>
        <div class="text-center">
          <h4 class="text-2xl font-semibold">100%</h4>
          <p>Customized Lessons</p>
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services" class="scroll-mt-20 py-16 px-4 bg-gray-50">
      <h3 class="text-3xl font-bold mb-10 text-center">My Services</h3>
      <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
        <!-- Card 1 -->
        <div class="bg-white shadow-md rounded-xl p-6 text-center">
          <h4 class="text-xl font-bold mb-2">General English</h4>
          <p class="text-sm mb-4">Improve everyday communication skills.</p>
          <button onclick="openModal('modal1')" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Learn More</button>
        </div>
        <!-- Card 2 -->
        <div class="bg-white shadow-md rounded-xl p-6 text-center">
          <h4 class="text-xl font-bold mb-2">Business English</h4>
          <p class="text-sm mb-4">Speak confidently in professional settings.</p>
          <button onclick="openModal('modal2')" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Learn More</button>
        </div>
        <!-- Card 3 -->
        <div class="bg-white shadow-md rounded-xl p-6 text-center">
          <h4 class="text-xl font-bold mb-2">Exam Prep (IELTS)</h4>
          <p class="text-sm mb-4">Ace your English exam with personalized prep.</p>
          <button onclick="openModal('modal3')" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Learn More</button>
        </div>
      </div>
    </section>

    <!-- MODALS -->
    <div id="modal1" class="fixed inset-0 bg-black bg-opacity-40 hidden items-center justify-center z-50">
      <div class="bg-white rounded-lg p-6 max-w-md text-center">
        <h4 class="text-2xl font-bold mb-2">General English</h4>
        <p class="mb-4">Focus on speaking, listening, and vocabulary for real-life use.</p>
        <button onclick="closeModal('modal1')" class="text-blue-600 hover:underline">Close</button>
      </div>
    </div>

    <div id="modal2" class="fixed inset-0 bg-black bg-opacity-40 hidden items-center justify-center z-50">
      <div class="bg-white rounded-lg p-6 max-w-md text-center">
        <h4 class="text-2xl font-bold mb-2">Business English</h4>
        <p class="mb-4">Learn to write emails, give presentations, and join meetings fluently.</p>
        <button onclick="closeModal('modal2')" class="text-blue-600 hover:underline">Close</button>
      </div>
    </div>

    <div id="modal3" class="fixed inset-0 bg-black bg-opacity-40 hidden items-center justify-center z-50">
      <div class="bg-white rounded-lg p-6 max-w-md text-center">
        <h4 class="text-2xl font-bold mb-2">Exam Prep</h4>
        <p class="mb-4">Practice writing, speaking, and strategy for top exam scores.</p>
        <button onclick="closeModal('modal3')" class="text-blue-600 hover:underline">Close</button>
      </div>
    </div>

    <!-- CONTACT -->
    <section id="contact" class="scroll-mt-20 py-16 px-4 max-w-3xl mx-auto">
      <h3 class="text-3xl font-bold mb-8 text-center">Contact Me</h3>
      <form id="contact-form" class="space-y-4 bg-white p-6 rounded-lg shadow-md">
        <input type="text" placeholder="Name" required class="w-full p-3 border rounded" />
        <input type="email" placeholder="Email" required class="w-full p-3 border rounded" />
        <textarea placeholder="Message" required class="w-full p-3 border rounded"></textarea>
        <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700">Send</button>
        <p id="form-response" class="text-green-600 hidden mt-2">Thanks for your message! I'll be in touch.</p>
      </form>
    </section>

    <!-- FOOTER -->
    <footer class="bg-gray-800 text-white text-center py-6">
      <p>&copy; 2025 Berfin English. All rights reserved.</p>
    </footer>

    <!-- SCRIPTS -->
    <script>
      const menuBtn = document.getElementById('menu-btn');
      const mobileMenu = document.getElementById('mobile-menu');
      menuBtn.addEventListener('click', () => {
        mobileMenu.classList.toggle('hidden');
      });

      function openModal(id) {
        document.getElementById(id).classList.remove('hidden');
        document.getElementById(id).classList.add('flex');
      }

      function closeModal(id) {
        document.getElementById(id).classList.add('hidden');
        document.getElementById(id).classList.remove('flex');
      }

      document.getElementById('contact-form').addEventListener('submit', function (e) {
        e.preventDefault();
        document.getElementById('form-response').classList.remove('hidden');
        this.reset();
      });
    </script>
  </body>
</html>
