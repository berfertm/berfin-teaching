<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Berfin English</title>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body class="bg-gray-50 text-gray-800 scroll-smooth">
    <!-- Navigation -->
    <header class="bg-white shadow">
      <nav class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
        <h1 class="text-2xl font-bold text-blue-600">Berfin English</h1>
        <ul class="hidden md:flex space-x-6 font-medium">
          <li><a href="#about" class="hover:text-blue-600">About</a></li>
          <li><a href="#services" class="hover:text-blue-600">Services</a></li>
          <li><a href="#contact" class="hover:text-blue-600">Contact</a></li>
        </ul>
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-blue-500 to-indigo-600 text-white py-20 px-6">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-4xl font-bold mb-4">Unlock Your English Potential</h2>
        <p class="text-xl">Learn confidently with a qualified, passionate tutor</p>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 px-6 scroll-mt-20">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-3xl font-bold mb-6 text-blue-700">About Me</h2>
        <p class="text-lg leading-relaxed mb-4">
          Hi! I'm Berfin, a certified English teacher helping learners gain confidence and fluency through personalized, modern lessons.
        </p>
        <div class="flex justify-center gap-10 mt-6">
          <div>
            <p class="text-2xl font-bold text-blue-600">5+</p>
            <p>Years Experience</p>
          </div>
          <div>
            <p class="text-2xl font-bold text-blue-600">200+</p>
            <p>Students Taught</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="bg-white py-16 px-6 scroll-mt-20">
      <div class="max-w-6xl mx-auto text-center">
        <h2 class="text-3xl font-bold mb-10 text-blue-700">My Services</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <!-- Service Card -->
          <div class="bg-gray-100 rounded-xl shadow p-6 hover:shadow-xl transition">
            <h3 class="text-xl font-semibold mb-2">General English</h3>
            <p>Build fluency and confidence in everyday communication.</p>
            <button onclick="toggleModal('modal1')" class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Learn More</button>
          </div>
          <div class="bg-gray-100 rounded-xl shadow p-6 hover:shadow-xl transition">
            <h3 class="text-xl font-semibold mb-2">Business English</h3>
            <p>Communicate effectively and professionally in the workplace.</p>
            <button onclick="toggleModal('modal2')" class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Learn More</button>
          </div>
          <div class="bg-gray-100 rounded-xl shadow p-6 hover:shadow-xl transition">
            <h3 class="text-xl font-semibold mb-2">Exam Prep (IELTS, TOEFL)</h3>
            <p>Targeted strategies and support to help you ace your exam.</p>
            <button onclick="toggleModal('modal3')" class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Learn More</button>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-blue-50 py-16 px-6 scroll-mt-20">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-3xl font-bold mb-6 text-blue-700">Contact Me</h2>
        <form id="contactForm" class="space-y-4">
          <input type="text" placeholder="Your Name" class="w-full border p-3 rounded" required />
          <input type="email" placeholder="Your Email" class="w-full border p-3 rounded" required />
          <textarea placeholder="Your Message" class="w-full border p-3 rounded" rows="4" required></textarea>
          <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700">Send</button>
          <p id="formSuccess" class="text-green-600 mt-2 hidden">Message sent successfully!</p>
        </form>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-6">
      <p>© 2025 Berfin English | Follow me on Instagram: @berflaneur</p>
    </footer>

    <!-- Modals -->
    <div id="modal1" class="fixed inset-0 bg-black bg-opacity-50 hidden flex items-center justify-center">
      <div class="bg-white p-6 rounded-xl max-w-md">
        <h3 class="text-xl font-bold mb-4">General English</h3>
        <p>Improve your speaking, listening, reading, and writing skills with dynamic, conversation-focused lessons.</p>
        <button onclick="toggleModal('modal1')" class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Close</button>
      </div>
    </div>
    <div id="modal2" class="fixed inset-0 bg-black bg-opacity-50 hidden flex items-center justify-center">
      <div class="bg-white p-6 rounded-xl max-w-md">
        <h3 class="text-xl font-bold mb-4">Business English</h3>
        <p>Tailored lessons to help you write emails, give presentations, and speak confidently in meetings and interviews.</p>
        <button onclick="toggleModal('modal2')" class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Close</button>
      </div>
    </div>
    <div id="modal3" class="fixed inset-0 bg-black bg-opacity-50 hidden flex items-center justify-center">
      <div class="bg-white p-6 rounded-xl max-w-md">
        <h3 class="text-xl font-bold mb-4">Exam Prep</h3>
        <p>Targeted preparation for IELTS, TOEFL, and Cambridge exams with practice tests, tips, and feedback.</p>
        <button onclick="toggleModal('modal3')" class="mt-4 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Close</button>
      </div>
    </div>

    <!-- Scripts -->
    <script>
      function toggleModal(id) {
        const modal = document.getElementById(id);
        modal.classList.toggle("hidden");
      }

      document.getElementById("contactForm").addEventListener("submit", function (e) {
        e.preventDefault();
        document.getElementById("formSuccess").classList.remove("hidden");
        this.reset();
      });
    </script>
  </body>
</html>
