<template>
  <div class="home">
    <Login></Login>
  </div>
</template>

<script>
// @ is an alias to /src
import Login from '@/components/Login.vue'

export default {
  name: 'HomeView',
  components: {
    Login
}
}
</script>
