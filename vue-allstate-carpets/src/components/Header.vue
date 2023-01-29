<template>
  <header>
    <nav
      class="flex flex-row align-middle bg-orange-200 bg-gradient-to-r from-amber-600"
    >
      <img src="../assets/aclogo.png" alt="logo" class="h-20 w-20" />
      <div
        class="flex flex-row align-middle my-auto px-5 justify-items-stretch"
      >
        <router-link to="/" class="mx-2 rounded-md py-1 text-red-700 font-bold"
          >Home</router-link
        >
        <router-link
          to="/about"
          class="mx-2 rounded-md py-1 text-red-700 font-bold justify-end"
          >About-Us</router-link
        >
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderVue'
}
</script>
