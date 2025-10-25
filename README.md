<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>University Connect | Home</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    ::-webkit-scrollbar { width: 8px; }
    ::-webkit-scrollbar-thumb { background: #3b82f6; border-radius: 8px; }
  </style>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Navbar -->
  <header class="bg-white shadow-md sticky top-0 z-50">
    <nav class="max-w-7xl mx-auto flex justify-between items-center p-4">
      <h1 class="text-2xl font-bold text-blue-600">UniConnect</h1>
      <ul class="hidden md:flex space-x-6">
        <li><a href="#" class="hover:text-blue-600">Home</a></li>
        <li><a href="#" class="hover:text-blue-600">About</a></li>
        <li><a href="#" class="hover:text-blue-600">Universities</a></li>
        <li><a href="#" class="hover:text-blue-600">Contact</a></li>
      </ul>
      <button class="md:hidden p-2 text-blue-600 border rounded-lg">☰</button>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="bg-gradient-to-r from-blue-600 to-indigo-700 text-white py-20 text-center">
    <h2 class="text-4xl md:text-5xl font-bold mb-4">Connecting Universities. Empowering Students.</h2>
    <p class="text-lg mb-6 max-w-2xl mx-auto">
      Our mission is to unite top institutions and learners through technology, innovation, and collaboration.
    </p>
    <a href="#universities" class="bg-white text-blue-700 px-6 py-3 rounded-lg font-semibold hover:bg-gray-200">
      Explore Universities
    </a>
  </section>

  <!-- Universities Section -->
  <section id="universities" class="max-w-7xl mx-auto py-16 px-4">
    <h3 class="text-3xl font-bold text-center mb-10 text-gray-800">Top Partner Universities</h3>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 text-center">
      
      <div class="bg-white shadow-lg rounded-2xl p-6 hover:scale-105 transition">
        <h4 class="font-semibold text-xl mb-2">Amity University</h4>
        <p class="text-gray-600 text-sm">Pioneering education through innovation and global outreach.</p>
      </div>

      <div class="bg-white shadow-lg rounded-2xl p-6 hover:scale-105 transition">
        <h4 class="font-semibold text-xl mb-2">SRM University</h4>
        <p class="text-gray-600 text-sm">Empowering learners with world-class education and research.</p>
      </div>

      <div class="bg-white shadow-lg rounded-2xl p-6 hover:scale-105 transition">
        <h4 class="font-semibold text-xl mb-2">Amrita University</h4>
        <p class="text-gray-600 text-sm">Fostering values, innovation, and social responsibility.</p>
      </div>

      <div class="bg-white shadow-lg rounded-2xl p-6 hover:scale-105 transition">
        <h4 class="font-semibold text-xl mb-2">VIT University</h4>
        <p class="text-gray-600 text-sm">Innovating education to nurture leaders of tomorrow.</p>
      </div>

    </div>
  </section>

  <!-- Social Stats -->
  <section class="bg-blue-50 py-16">
    <div class="max-w-5xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-8">Our Growing Community</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div>
          <h4 class="text-5xl font-bold text-blue-700">50K+</h4>
          <p class="text-gray-600 mt-2">Active Students</p>
        </div>
        <div>
          <h4 class="text-5xl font-bold text-blue-700">120+</h4>
          <p class="text-gray-600 mt-2">Partner Universities</p>
        </div>
        <div>
          <h4 class="text-5xl font-bold text-blue-700">95%</h4>
          <p class="text-gray-600 mt-2">Satisfaction Rate</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 py-10 text-center">
    <p>© 2025 UniConnect. All rights reserved.</p>
    <p class="text-sm mt-2">Designed with ❤️ for education and collaboration.</p>
  </footer>

</body>
</html>
