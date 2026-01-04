<template>
  <div>
    <nav>
      <NuxtLink to="/">Inicio</NuxtLink> | 
      <NuxtLink to="/about">About</NuxtLink> |
     <NuxtLink to="/contact">Contact</NuxtLink>
    </nav>
    <slot />
    <footer>Mi Pie de Página</footer>
  </div>
</template>