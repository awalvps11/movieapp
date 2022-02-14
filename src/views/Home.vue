<template>
  <div class="container">
    <div class="row">
      <div class="col-md-8">
        <tampilan-deapan />
      </div>
    </div>
  </div>
</template>

<script>
import TampilanDeapan from "../components/TampilanDeapan.vue";
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    TampilanDeapan,
  },
};
</script>

    