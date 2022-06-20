<template>
  <!-- <div class="w-max w-min mx-0 my-auto h-4/6"> -->
  <div class="flex flex-row relative">
    <div class="w-2/3 float-right mt-12 inline-block basis-1/4">
      <img
        class="absolute left-0 ml-12 w-48 h-12 mt-12"
        src="../assets/swiggy_logo.svg.png"
      />
    </div>
    <div class="w-2/3 pr-14">
      <div class="w-2/3 float-right mt-12 inline-block basis-1/4">
        <button
          type="button"
          class="text-black text-sm absolute font-semibold w-auto h-10 text-right hover:text-orange-500"
        >
          Login
        </button>
      </div>

      <div class="pr-14 w-2/3 float-right mt-12 inline-block basis-1/2">
        <button
          type="button"
          class="text-white text-sm bg-black p-3 absolute font-semibold h-10 w-auto text-right mt-7"
        >
          Sign up
        </button>
      </div>
    </div>
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
