<script >
import Apptitle from './components/Apptitle.vue'
import Appjumbo from './components/Appjumbo.vue'
export default {
  components: {
    Appjumbo, Apptitle
  }
}
</script>

<template>
  <Apptitle />
  <Appjumbo />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
