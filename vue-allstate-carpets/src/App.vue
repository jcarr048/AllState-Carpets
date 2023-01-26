<template>
  <div>
    <HeaderVue />
    <router-view />
  </div>
</template>

<script>
import HeaderVue from '@/components/Header.vue'
export default {
  components: {
    HeaderVue
  }
}
</script>
