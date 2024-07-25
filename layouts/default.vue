<template>
  <div>
    <header>
      <h1>Ecommerce</h1>
    </header>

    <slot />

    <footer>
      <p>© {{ new Date().getFullYear() }} Ecommerce</p>
    </footer>
  </div>
</template>
