<template>
  <div id="entry">
    <div class="entry-title d-flex justify-content-between p-2">
      <div>
        <span class="text-success fs-3 fw-bold">15</span>
        <span class="mx-1 fs3">Julio</span>
        <span class="mx-2 fs-4 fw-light">22, jueves</span>
      </div>

      <div>
        <button class="btn btn-danger mx-2">
          <i class="fas fa-trash-alt"></i>
          Borar
        </button>
        <button class="btn btn-info">
          <i class="fas fa-upload"></i>
          Subir imagen
        </button>
      </div>
    </div>
    <hr />
    <div class="d-flex flex-column px-3 h-75">
      <textarea placeholder="¿Qué susedió hoy?"></textarea>
    </div>
    <Fab icon="fa-save" />
    <img
      src="https://i0.wp.com/klubbingkids.com/wp-content/uploads/2020/12/quien-es-charlotte-de-witte-klubbingkids-2.jpg"
      alt="Entry-imagen"
      class="img-thumbnail"
    />
  </div>
</template>

<script>
import Fab from "../components/Fab.vue";

export default {
  name: "entry",
  components: {
    Fab,
  },
};
</script>

<style lang="scss" scoped>
textarea {
  font-size: 20px;
  border: none;
  height: 100%;

  &focus {
    outline: none;
  }
}

img{
  width: 200px;
  position: fixed;
  bottom: 150px;
  right: 20px;
  box-shadow: 0px 5px 10px rgba($color: #000000, $alpha: 0.2);
}
</style>