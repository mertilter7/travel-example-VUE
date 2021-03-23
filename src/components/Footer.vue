<template>
  <footer class="footer bg-black text-white inset-x-0 p-3 text-md text-center ">
    <p class="py-2">COMPANY</p>

    <div>
      <ul class="flex justify-center my-6 space-x-1">
        <li>
          <router-link
            to="/"
            class="hover:bg-purple-500 focus:outline-none focus:ring-2 focus:ring-purple-500 focus:ring-opacity-50 p-1 rounded-md"
            >Home</router-link
          >
        </li>
        <li>
          <router-link
            to="/travel"
            class="hover:bg-red-400 focus:outline-none focus:ring-2 focus:ring-red-400 focus:ring-opacity-50 p-1 rounded-md"
            >Travel</router-link
          >
        </li>
        <li>
          <router-link
            to="/gallery"
            class="hover:bg-blue-400 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:ring-opacity-50 p-1 rounded-md"
            >Gallery</router-link
          >
        </li>
        <li>
          <router-link
            to="/about"
            class="hover:bg-green-400 focus:outline-none focus:ring-2 focus:ring-purple-400 focus:ring-opacity-50 p-1 rounded-md"
            >About</router-link
          >
        </li>
        <li>
          <router-link
            to="/contact"
            class="hover:bg-yellow-400 focus:outline-none focus:ring-2 focus:ring-yellow-400 focus:ring-opacity-50 p-1 rounded-md"
            >Contact</router-link
          >
        </li>
      </ul>
    </div>
    <div class="space-x-4 my-3">
      <a href=""
        ><i
          class="fab fa-twitter bg-blue-600 rounded-3xl p-3 hover:bg-yellow-600 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50"
        ></i
      ></a>
      <a href=""
        ><i
          class="fab fa-instagram bg-blue-600 rounded-3xl p-3 hover:bg-green-600 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50"
        ></i
      ></a>
      <a href=""
        ><i
          class="fab fa-facebook bg-blue-600 rounded-3xl p-3 hover:bg-red-600 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50"
        ></i
      ></a>
    </div>
  </footer>
</template>
<script>
export default {};
</script>
<style scoped>

</style>
