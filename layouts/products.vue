<template>
  <div class="container">
    <header class="shadow-s">
      <nav class="mx-auto p-4">
        <NuxtLink to="/products">Products</NuxtLink>
      </nav>
    </header>
    <div class="mx-auto p-4">
      <slot />
    </div>
    <footer class="mx-auto p-4 flex justify-start">
      <ul class="flex gap-4">
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/products">Products</NuxtLink>
        </li>
      </ul>
    </footer>
  </div>
</template>

<style>
.router-link-exact-active {
  color: cadetblue;
}
</style>
