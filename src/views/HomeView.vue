<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div id="btn botones">
      <button @click="goToDayBook" class="btn btn-primary">Primary</button>
      <button @click="goToDayBook" class="btn btn-secondary">Secondary</button>
      <button @click="goToDayBook" class="btn btn-success">Success</button>
    </div>
   
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  },
  methods: {
    goToDayBook() {
      this.$router.push( { name: 'no-entry'} )
    }
  }
}
</script>
