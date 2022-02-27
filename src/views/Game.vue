<template>
  <div class="container">
    <div class="grid-rows-3 grid-flow-col gap-4"></div>
    <div class="grid grid-rows-3 grid-flow-col gap-3 border p-2">
      <div class="" v-for="x in [...Array(9).keys()]" :key="x">
        <input
          class="
            shadow
            appearance-none
            py-2
            px-3
            w-1/6
            text-gray-700
            focus:outline-none focus:shadow-outline
          "
          id="password"
          type="text"
          placeholder="X"
          maxlength="1"
        />
      </div>
    </div>
  </div>
</template>
<script lang="ts">
export default {
  data() {
    return {
      pattersList: [
        {
          x_1: "x",
          y_1: "o",
        },
        {
          x_1: "x",
          y_1: "o",
        },
        {
          x_1: "x",
          y_1: "o",
        },
        {
          x_1: "x",
          y_1: "o",
        },
        {
          x_1: "x",
          y_1: "o",
        },
        {
          x_1: "x",
          y_1: "o",
        },
        {
          x_1: "x",
          y_1: "o",
        },
        {
          x_1: "x",
          y_1: "o",
        },
      ],
    };
  },
  method: {
    genarate() {
      console.log(" list =", this.list);
    },
  },
  computed: {},
};
</script>
