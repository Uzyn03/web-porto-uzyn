<template>
  <header class="w-full border-b border-teal-400 bg-transparent fixed z-50">
    <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-16">
        <div class="flex items-center">
          <a href="#" class="text-2xl font-bold text-gray-800"
            ><span class="text-teal-500">U</span>zyn</a
          >
        </div>
        <div>
          <a
            href="#"
            @click.prevent="scrollTo('Home')"
            class="text-gray-800 hover:bg-teal-500 hover:text-slate-50 px-3 py-1 rounded-lg font-semibold"
            >Home</a
          >
          <a
            href="#"
            @click.prevent="scrollTo('About')"
            class="text-gray-800 hover:bg-teal-500 hover:text-slate-50 px-3 py-1 rounded-lg font-semibold"
            >About</a
          >
          <a
            href="#"
            class="text-gray-800 hover:bg-teal-500 hover:text-slate-50 px-3 py-1 rounded-lg font-semibold"
            >Project</a
          >
          <a
            href="#"
            class="text-gray-800 hover:bg-teal-500 hover:text-slate-50 px-3 py-1 rounded-lg font-semibold"
            >Contact</a
          >
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  methods: {
    scrollTo(section) {
      const element = document.getElementById(section);
      if (element) {
        element.scrollIntoView({ behavior: "smooth" });
      }
    },
  },
};
</script>

<style scoped>
a {
  margin: 0 15px;
  cursor: pointer;
}
</style>
