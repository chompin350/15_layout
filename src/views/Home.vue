<template>
  <div class="home">
    <NavBar/>
    <Card/>
  </div>
</template>

<script>

import NavBar from '@/components/Navbar.vue'
import Card from '@/components/Card.vue'

export default {
  name: 'Home',
  components: {
    NavBar,
    Card
  }
}
</script>
