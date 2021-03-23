<template>
  <nav>
    <div
      class="p-2 xl:rounded-bl-full xl:rounded-br-full bg-black text-white font-bold font-sans"
    >
      <ul class="flex space-x-3 justify-center p-2">
        <li>
          <router-link
            to="/"
            class="hover:bg-yellow-400 focus:outline-none focus:ring-2 focus:ring-yellow-400 focus:ring-opacity-50 p-2 rounded-lg"
            >Home</router-link
          >
        </li>
        <li>
          <router-link
            to="/travel"
            class="hover:bg-purple-400 focus:outline-none focus:ring-2 focus:ring-purple-400 focus:ring-opacity-50 p-2 rounded-lg"
            >Travel</router-link
          >
        </li>
        <li>
          <router-link
            to="/gallery"
            class="hover:bg-blue-400 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:ring-opacity-50 p-2 rounded-lg"
            >Gallery</router-link
          >
        </li>
        <li>
          <router-link
            to="/about"
            class="hover:bg-green-400 focus:outline-none focus:ring-2 focus:ring-green-400 focus:ring-opacity-50 p-2 rounded-lg"
          >
            About
          </router-link>
        </li>
        <li>
          <router-link
            to="/contact"
            class="hover:bg-red-300 focus:outline-none focus:ring-2 focus:ring-red-300 focus:ring-opacity-50 p-2 rounded-lg"
          >
            Contact
          </router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>
<style scoped>
.rainbow-text {
  background-image: linear-gradient(
    to left,
    violet,
    lightgreen,
    lightblue,
    lightgreen,
    yellow,
    orange,
    red
  );
}
</style>
