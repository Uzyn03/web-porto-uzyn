<template>
  <section id="About" class="bg-gray-50 py-6">
    <div class="container mx-auto px-8 md:px-2">
      <div class="flex flex-col md:flex-row items-center gap-12">
        <!-- Bagian Kiri: Foto Profil -->
        <div class="md:w-1/3">
          <img
            src="/src/assets/user.jpg"
            alt="Poto uzyn"
            class="w-11/12 rounded-2xl mx-auto md:mx-0 my-4"
          />
        </div>

        <!-- Bagian Kanan: Deskripsi Diri -->
        <div class="md:w-2/3">
          <h2 class="text-3xl font-bold mb-4">About Me</h2>
          <p class="text-lg text-gray-700 mb-6">
            Halo, saya Ahmad Fauzi, mahasiswa Teknik Informatika yang antusias
            dan memiliki minat yang besar dalam pengembangan web. Saya senang
            mengubah ide menjadi sebuah web yang elegan dan fungsional dan terus
            meningkatkan keterampilan pengkodean saya.
          </p>

          <h3 class="text-2xl font-semibold mb-3">Skills & Tools</h3>
          <ul class="list-disc list-inside mb-6 text-gray-700">
            <li>Frontend: HTML, CSS, JavaScript, Vue, Tailwindcss</li>
            <li>Backend (Exploring): Node.js</li>
            <li>Tools: Git, VS Code, Figma</li>
            <li>Data Analis (Exploring)</li>
          </ul>

          <h3 class="text-2xl font-semibold mb-3">Goals & Vision</h3>
          <p class="text-lg text-gray-700">
            Saya bertujuan untuk membangun proyek-proyek di dunia nyata,
            berkolaborasi dengan pengembang lain, dan mendapatkan kesempatan
            kerja untuk mengembangkan kemampuan saya.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>
