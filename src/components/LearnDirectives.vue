<template>
  <input v-focus />
</template>
<script setup>
const vFocus = {
  mounted: (el) => {
    el.focus();
    console.log("this is focus");
  },
};
</script>
