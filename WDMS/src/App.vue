<script setup>
import { RouterLink, RouterView } from 'vue-router'
import FeatureCard from './components/FeatureCard.vue'
</script>

<template>
  <div class="bg-gray-50">
    <!-- Header -->
    <header class="bg-blue-900 text-white py-6">
      <div class="max-w-7xl mx-auto px-6 flex items-center justify-between">
        <img src="@/assets/dpwh-logo.png" alt="DPWH Logo" class="h-20" />
        <div>
          <h1 class="text-3xl font-bold">Weighbridge Data Management System</h1>
          <p class="text-lg mt-2">Securing Roads Through Efficient Vehicle Weight Monitoring</p>
        </div>
        <div>
          <button class="bg-blue-500 text-white py-2 px-4 rounded-md mr-2">Login</button>
          <button class="bg-gray-500 text-white py-2 px-4 rounded-md">Register</button>
        </div>
      </div>
    </header>

    <!-- About Section -->
    <section class="max-w-7xl mx-auto px-6 py-12">
      <h2 class="text-2xl font-semibold text-center mb-6">About the System</h2>
      <p class="text-lg text-center max-w-3xl mx-auto">
        The Weighbridge Data Management System streamlines vehicle weighing operations across DPWH stations. It ensures compliance with road safety standards, reduces road damage, and provides data-driven insights for enforcement.
      </p>
    </section>

    <!-- Features Section -->
    <section class="bg-white py-12">
      <div class="max-w-7xl mx-auto px-6 text-center">
        <h2 class="text-2xl font-semibold mb-6">Core Features</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Feature 1 -->
          <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
            <div class="text-blue-500 text-4xl mb-4">📦</div>
            <h3 class="text-xl font-semibold">Centralized Database</h3>
            <p>Unified storage for vehicle logs, weight records, and violations.</p>
          </div>
          <!-- Feature 2 -->
          <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
            <div class="text-blue-500 text-4xl mb-4">📝</div>
            <h3 class="text-xl font-semibold">Daily Logs</h3>
            <p>Log truck data and weights quickly and accurately.</p>
          </div>
          <!-- Feature 3 -->
          <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
            <div class="text-blue-500 text-4xl mb-4">🚛</div>
            <h3 class="text-xl font-semibold">Violation Tracking</h3>
            <p>Automatically flag and track overloaded vehicles.</p>
          </div>
          <!-- Feature 4 -->
          <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
            <div class="text-blue-500 text-4xl mb-4">📊</div>
            <h3 class="text-xl font-semibold">Reports & Analytics</h3>
            <p>Generate compliance and statistical reports.</p>
          </div>
          <!-- Feature 5 -->
          <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
            <div class="text-blue-500 text-4xl mb-4">🛡️</div>
            <h3 class="text-xl font-semibold">Role-Based Access</h3>
            <p>Admin and operator roles with secure authentication.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Call to Action -->
    <section class="bg-blue-900 text-white py-12 text-center">
      <h2 class="text-2xl font-semibold mb-6">Start managing weighbridge data efficiently today.</h2>
      <div>
        <button class="bg-blue-500 text-white py-3 px-6 rounded-md mr-2">Log In</button>
        <button class="bg-gray-500 text-white py-3 px-6 rounded-md">Request Access</button>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-6">
      <div class="max-w-7xl mx-auto px-6 flex items-center justify-between">
        <p>&copy; DPWH 2025</p>
        <div class="flex space-x-6">
          <a href="#" class="text-gray-400 hover:text-white">Home</a>
          <a href="#" class="text-gray-400 hover:text-white">About</a>
          <a href="#" class="text-gray-400 hover:text-white">Contact</a>
          <a href="#" class="text-gray-400 hover:text-white">Privacy Policy</a>
        </div>
      </div>
    </footer>
  </div>
</template>
