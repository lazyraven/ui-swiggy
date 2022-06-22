<template>
  <!-- <div class="w-max w-min mx-0 my-auto h-4/6"> -->

  <div class="flex flex-row mt-12">
    <div class="basis-1/2">
      <img
        class="absolute left-0 ml-24 w-48 h-12"
        src="../assets/swiggy_logo.svg.png"
      />
    </div>
    <div class="basis-1/4 m-2">
    </div>
    <div class="basis-1/4 m-2">
      <button
        type="button"
        class="text-black text-base font-semibold w-auto h-10 hover:text-orange-500 mx-2"
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
  <div>
  <h1>Hungry</h1>
  <h1>Order food from favourite restaurants near you.</h1>
   <div class="mb-4 mt-12">
      <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline h" id="username" type="text" placeholder="Username">
    <button
        type="button"
        class="text-white text-base bg-orange-600 px-8 py-2 font-sans absolute font-bold text-right"
      >
       FIND FOOD
      </button>
    </div>
    <h3>POPULAR CITIES IN INDIA</h3>
    <h3>Ahmedabad Bangalore Chennai Delhi Gurgaon Hyderabad Kolkata MumbaiPune& more.</h3>
  </div>

</template>

<script>
export default {
  name: "LeftHomePage",
  data() {
    return {};
  },
};
</script>
