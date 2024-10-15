<template>
  <section class="w-full h-screen flex items-center">
    <div
      class="max-w-7xl px-4 mx-auto sm:px-6 lg:px-8 flex flex-col md:flex-row items-center justify-between"
    >
      <!-- Teks di Sebelah Kiri -->
      <div class="md:w-1/2 text-center md:text-left">
        <h4 class="text-xl font-semibold text-gray-600">Welcome Everyone 👋</h4>
        <h2 class="text-2xl font-bold text-gray-800">
          I'm <span class="text-teal-400">Ahmad Fauzi</span>
        </h2>
        <p class="text-lg text-gray-600 mb-10">
          Ungraduate Informatics Engineering Student at STMIK Mardira Indonesia
        </p>
        <button
          class="px-6 py-2 bg-teal-500 text-white rounded-lg hover:bg-teal-700 transition"
        >
          Contact Me
        </button>
      </div>

      <!-- Gambar di Sebelah Kanan -->
      <div class="md:w-1/2 mt-8 md:mt-0 flex justify-center">
        <img
          src="/src/assets/uzynbg.png"
          alt="Hero Image"
          class="w-2/3 max-w-sm rounded-full shadow-teal-900 shadow-lg bg-gradient-to-r from-teal-400 to-sky-700"
        />
      </div>
    </div>
  </section>
</template>
