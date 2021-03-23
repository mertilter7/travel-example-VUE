<template>
  <div
    class="container xl:h-4/6 xl:w-2/6 md:h-4/6 md:w-4/6 h-full w-full mx-auto bg-red-300 xl:rounded-2xl md:rounded-2xl"
  >
    <h2 class="font-bold text-center my-5 font-sans text-white text-xl">
      Contact US
    </h2>
    <label class="my-11 flex flex-col justify-center">
      <span class="text-white font-bold font-sans mx-auto">Email Address</span>
      <input
        type="email"
        class="p-3 mx-2 form-input border rounded-xl focus:outline-none bg-red-200 border-red-200"
        placeholder=""
      />
      <span class="text-white font-bold m-3 font-sans mx-auto">Comment</span>
      <textarea
        class="border mx-2 rounded-xl p-4 resize-none bg-red-200 border-red-300 text-black text-md focus:outline-none"
        placeholder=""
      ></textarea>
    </label>
    <button
      type="button"
      class="focus:outline-none mx-2 text-white text-sm py-2.5 px-4 -my-7 rounded-md bg-red-500 hover:bg-red-600 hover:shadow-lg flex"
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