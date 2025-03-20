<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Powerful Modern Website</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" />
</head>
<body class="font-sans bg-gray-50">
  <!-- Header Section -->
  <header class="bg-blue-600 text-white py-6">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">My Powerful Website</h1>
      <nav>
        <a href="#services" class="mx-4">Services</a>
        <a href="#contact" class="mx-4">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-blue-500 text-white text-center py-20">
    <h2 class="text-5xl font-bold mb-4">Welcome to Your Future</h2>
    <p class="text-xl mb-6">Innovative solutions for your business needs.</p>
    <a href="#services" class="bg-white text-blue-600 px-8 py-3 rounded-full font-semibold">Explore Services</a>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-16">
    <div class="container mx-auto">
      <h2 class="text-4xl font-bold text-center mb-10">Our Services</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-2xl font-bold">Web Development</h3>
          <p class="text-gray-600 mt-4">High-quality websites built with modern technologies.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-2xl font-bold">Digital Marketing</h3>
          <p class="text-gray-600 mt-4">Grow your audience and reach your goals with strategic marketing.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-2xl font-bold">Consulting</h3>
          <p class="text-gray-600 mt-4">Expert guidance to navigate complex business challenges.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-gray-100 py-16">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-6">Contact Us</h2>
      <p class="text-gray-600 mb-8">We'd love to hear from you!</p>
      <form class="max-w-lg mx-auto">
        <input class="w-full p-3 mb-4 border border-gray-300 rounded" type="text" placeholder="Your Name" required />
        <input class="w-full p-3 mb-4 border border-gray-300 rounded" type="email" placeholder="Your Email" required />
        <textarea class="w-full p-3 mb-4 border border-gray-300 rounded" rows="5" placeholder="Your Message" required></textarea>
        <button class="bg-blue-600 text-white px-6 py-3 rounded-full" type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer Section -->
  <footer class="bg-blue-600 text-white py-6 text-center">
    <p>&copy; 2025 My Powerful Website. All rights reserved.</p>
  </footer>
</body>
</html>
