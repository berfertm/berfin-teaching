# berfin-teaching
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Teaching Website</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script>
  
    }
  </script>
</head>
<body class="font-sans antialiased text-gray-900 scroll-smooth">
  <!-- Navigation -->
  <nav class="bg-white shadow fixed w-full z-10">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex justify-between items-center py-4">
        <div class="text-2xl font-bold">MyTeaching</div>
        <div class="hidden md:flex space-x-6">
          <a href="#about" class="hover:text-blue-600">About</a>
          <a href="#services" class="hover:text-blue-600">Services</a>
          <a href="#contact" class="hover:text-blue-600">Contact</a>
  

  <!-- About Section -->
  <section id="about" class="py-20 px-4 max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-10">About Me</h2>
    <div class="grid md:grid-cols-2 gap-10">
      <p>Hello! I’m a certified English teacher with years of experience helping students improve their fluency, confidence, and language skills. I offer personalized, engaging lessons tailored to your needs.</p>
      <div class="flex space-x-8">
        <div>
          <p class="text-4xl font-bold text-blue-600">5+</p>
          <p>Years Teaching</p>
        </div>
        <div>
          <p class="text-4xl font-bold text-blue-600">100+</p>
          <p>Students Taught</p>
        </div>
      </div>
    </div>
  </section>


  <!-- Contact Section -->
  <section id="contact" class="py-20 px-4 max-w-3xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-10">Contact Me</h2>
    <form name="contactForm" onsubmit="return validateForm()" class="space-y-6">
      <input type="text" name="name" placeholder="Your Name" class="w-full border p-3 rounded" required>
      <input type="email" name="email" placeholder="Your Email" class="w-full border p-3 rounded" required>
      <textarea name="message" rows="5" placeholder="Your Message" class="w-full border p-3 rounded" required></textarea>
      <button type="submit" class="bg-blue-600 text-white py-2 px-6 rounded hover:bg-blue-700">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white py-6">
    <div class="max-w-6xl mx-auto px-4 flex justify-between items-center">
      <p>&copy; 2025 MyTeaching. All rights reserved.</p>
      <div class="flex space-x-4">
        <a href="#" class="hover:text-blue-400">Instagram</a>
        <a href="#" class="hover:text-blue-400">LinkedIn</a>
        <a href="#" class="hover:text-blue-400">Email</a>
      </div>
    </div>
  </footer>
</body>
</html>
