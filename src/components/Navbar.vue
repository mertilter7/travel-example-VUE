<template>
  <nav>
    <div class="bg-black text-white p-2 xl:rounded-bl-full xl:rounded-br-full">
      <ul class="flex space-x-3 justify-center p-2">
        <li>
          <router-link
            to="/"
            class="hover:bg-purple-700 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50 p-2 rounded-lg"
            >Home</router-link
          >
        </li>
        <li>
          <router-link
            to="/travel"
            class="hover:bg-purple-700 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50 p-2 rounded-lg"
            >Travel</router-link
          >
        </li>
        <li>
          <router-link
            to="/gallery"
            class="hover:bg-purple-700 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50 p-2 rounded-lg"
            >Gallery</router-link
          >
        </li>
        <li>
          <router-link
            to="/about"
            class="hover:bg-purple-700 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50 p-2 rounded-lg"
          >
            About
          </router-link>
        </li>
        <li>
          <router-link
            to="/contact"
            class="hover:bg-purple-700 focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-opacity-50 p-2 rounded-lg"
          >
            Contact
          </router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>
