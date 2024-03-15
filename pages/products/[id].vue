<template>
  <div>Product for: {{ route.params.id }}</div>
  <div>
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iure, cum nemo.
    Perspiciatis, enim? Magni eveniet, voluptatum amet voluptate sapiente,
    suscipit illo rem architecto dignissimos velit sit nemo, enim unde aut.
  </div>
</template>

<script setup>
const route = useRoute();
definePageMeta({
  layout: "products",
});
</script>

<style lang="scss" scoped></style>
