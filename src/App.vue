<template>
  <div class="min-h-screen bg-gray-100">
    <!-- Hero Section -->
    <section class="bg-blue-600 text-white py-20 text-center">
      <h1 class="text-4xl font-bold">Find Your Dream Job Today</h1>
      <p class="mt-4 text-lg">Connecting top talent with leading companies</p>
      <button class="mt-6 px-6 py-3 bg-white text-blue-600 font-semibold rounded-lg shadow-lg hover:bg-gray-200">
        Get Started
      </button>
    </section>

    <!-- Dashboard Stats -->
    <section class="py-20 bg-white text-center">
      <h2 class="text-3xl font-bold">Job Board Statistics</h2>
      <div class="flex justify-center mt-8 space-x-10">
        <div class="p-6 bg-gray-200 rounded-lg">
          <p class="text-2xl font-bold">10K+</p>
          <p>Jobs Posted</p>
        </div>
        <div class="p-6 bg-gray-200 rounded-lg">
          <p class="text-2xl font-bold">5K+</p>
          <p>Companies</p>
        </div>
        <div class="p-6 bg-gray-200 rounded-lg">
          <p class="text-2xl font-bold">50K+</p>
          <p>Applications</p>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section class="py-20 bg-gray-100 text-center">
      <h2 class="text-3xl font-bold">Our Services</h2>
      <div class="flex justify-center mt-8 space-x-10">
        <div class="p-6 bg-white rounded-lg shadow-md">
          <h3 class="text-xl font-bold">Job Listings</h3>
          <p class="mt-2 text-gray-600">Find the best job opportunities</p>
        </div>
        <div class="p-6 bg-white rounded-lg shadow-md">
          <h3 class="text-xl font-bold">Resume Reviews</h3>
          <p class="mt-2 text-gray-600">Optimize your resume for recruiters</p>
        </div>
        <div class="p-6 bg-white rounded-lg shadow-md">
          <h3 class="text-xl font-bold">Career Coaching</h3>
          <p class="mt-2 text-gray-600">Guidance from industry experts</p>
        </div>
      </div>
    </section>

    <!-- Clientele Section -->
    <section class="py-20 bg-white text-center">
      <h2 class="text-3xl font-bold">Our Trusted Clients</h2>
      <div class="flex justify-center mt-8 space-x-10">
        <!-- <img src="/pepsico.png" alt="Client 1" class="h-16">
        <img src="/vcentric.jpg" alt="Client 2" class="h-16">
        <img src="/zettamine.svg" alt="Client 3" class="h-16"> -->
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-6 text-center">
      <p>&copy; 2025 DigiHire. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "LandingPage",
};
</script>