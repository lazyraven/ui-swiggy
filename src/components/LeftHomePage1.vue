<template>
  <!-- <div class="w-max w-min mx-0 my-auto h-4/6"> -->
  <!-- <div class="w-3/4"> -->
  <div class="mt-12 w-3/4">
    <img
      class="absolute left-0 ml-20 w-48 h-12"
      src="../assets/swiggy_logo.svg.png"
    />
    <div class="float-right">
      <button
        type="button"
        class="text-black text-base font-semibold w-auto h-10 hover:text-orange-500 mx-6"
      >
        Login
      </button>
      <button
        type="button"
        class="text-white text-base bg-black px-8 py-2 font-sans absolute font-bold text-right"
      >
        Sign up
      </button>
    </div>
  </div>
  <div class="ml-20 mt-40 w-2/3 font-sans">
    <h1 class="text-4xl font-semibold">Hungry?</h1>
    <h1 class="text-xl font-normal text-gray-400 leading-10">
      Order food from favourite restaurants near you.
    </h1>
    <div class="mb-4 mt-8">
      <input
        class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-900 leading-tight focus:outline-none focus:shadow-outline h-14 font-medium text-lg"
        id="username"
        type="text"
        placeholder="Enter your delivery location"
      />
      <button
        type="button"
        class="text-white text-base bg-orange-400 px-8 py-2 font-sans absolute font-bold text-right h-14"
      >
        FIND FOOD
      </button>
    </div>
    <h3 class="mt-8 mb-2.5 text-gray-400 text-sm font-normal">
      POPULAR CITIES IN INDIA
    </h3>
    <h3>
      <!-- <span></span> -->
      Ahmedabad Bangalore Chennai Delhi Gurgaon Hyderabad Kolkata MumbaiPune&
      more.
    </h3>
  </div>
  <!-- </div> -->
</template>

<script>
export default {
  name: "LeftHomePage",
  data() {
    return {};
  },
};
</script>
