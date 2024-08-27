<template>
  <nav>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/about">About</NuxtLink>
    <NuxtLink to="/profile">Profile</NuxtLink>
  </nav>

  <!-- Here Nuxt will replace the page content  -->
  <slot></slot>
</template>
