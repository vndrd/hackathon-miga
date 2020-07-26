<template>
  <div class="home">
    <Catalogo msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Catalogo from '@/components/Catalogo.vue'

export default {
  name: 'Home',
  components: {
    Catalogo
  }
}
</script>
