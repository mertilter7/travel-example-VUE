<template>
  <div class="container h-full mx-auto">
    <label class="my-11 flex flex-col justify-center">
      <span class="text-gray-700">Email Address</span>
      <input
        type="email"
        class="p-2 form-input border rounded"
        placeholder="john@example.com"
      />
      <span class="text-gray-700 m-3">Comment</span>
      <textarea
        class="border rounded p-4 resize-none"
        placeholder="text area"
      ></textarea>
    </label>
    <button
      type="button"
      class="focus:outline-none text-white text-sm py-2.5 px-5 -my-9 rounded-md bg-gray-700 hover:bg-gray-900 hover:shadow-lg flex items-center"
    >
      <svg
        class="w-4 h-4 mr-2"
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.095c-.5 0-.905.405-.905.905 0 .714-.211 1.412-.608 2.006L7 11v9m7-10h-2M7 20H5a2 2 0 01-2-2v-6a2 2 0 012-2h2.5"
        />
      </svg>
      Submit
    </button>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
</style>