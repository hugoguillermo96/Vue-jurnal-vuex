<template>
  <div id="dayBookLayout">
    <NavbarBook />
    <div class="d-flex">
      <div class="col-4">
        <EntryList />
      </div>
      <div class="col">
        <router-view></router-view>
       

      </div>

    </div>
  </div>
</template>

<script>
import NavbarBook from "../components/Navbar.vue";
import EntryList from "../components/EntryList.vue";


export default {
  name: "dayBook",
  components: {
    NavbarBook,
    EntryList,
    
  },
};
</script>