<template>
  <div
    class="container mx-auto w-full h-full xl:h-3/5 xl:w-5/12 md:h-4/6 md:w-7/12 sm:h-4/6 sm:w-7/12 bg-purple-300 flex justify-center xl:rounded-2xl md:rounded-2xl"
  >
    <div>
      <h2 class="my-2 text-white font-bold text-2xl font-sans">Get Reserve</h2>
      <section>
        <label class="block my-10">
          <span class="text-white font-semibold">Name & Surname :</span>
          <input
            type="text"
            class="form-input mt-1 block w-full border p-1 rounded-md"
            placeholder="Name"
          />
          <label class="block my-5">
            <span class="text-white font-semibold">Email Adress :</span>
            <input
              type="email"
              class="form-input mt-1 block w-full border p-1 rounded-md"
              placeholder="john@example.com"
              v-model="mail"
            />
          </label>
          <p class="font-semibold text-white p-1 font-sans">Travel Options</p>
          <label>
            <select class="p-2 rounded-lg">
              <option class="" v-for="(travel, id) in travels" :key="id">
                {{ travel }}
              </option>
            </select>
          </label>
        </label>

        <input
          type="date"
          id="datemin"
          min="now"
          class="focus:bg-red-300 text-black rounded-lg p-2"
        />
      </section>
      <button
        type="button"
        class="focus:outline-none text-white text-sm p-2 my-3 rounded-md bg-purple-500 hover:bg-purple-900 hover:shadow-lg flex items-center"
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
  </div>
</template>
<script>
export default {
  name: "Travel",
  components: {},
  data() {
    return {
      travels: ["Maldives", "Bali", "Bahamas", "Miami", "Mykonos", "Rhodos"],
      date: "",
      identify: "",
      mail: "",
    };
  },
  methods: {},
};
</script>