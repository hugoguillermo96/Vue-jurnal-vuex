<template>
  <div id="noEntrySelect">
    <div class="d-flex justify-content-center">
      <h1 class="align-self-center" >No has seleccionado nada aún.</h1>
    </div>

    <Fab/>
  </div>
</template>

<script>

import Fab from "../components/Fab.vue";

export default {
    name: 'noEntrySelect',
    components: {
      Fab
    }

}
</script>
<style lang="scss" scoped>


</style>