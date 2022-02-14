<template>
  <div>
    <h1> {{judul1}} {{judul2}}</h1>
    <img
      src="https://m.media-amazon.com/images/M/MV5BZmQ5NGFiNWEtMmMyMC00MDdiLTg4YjktOGY5Yzc2MDUxMTE1XkEyXkFqcGdeQXVyNTA4NzY1MzY@._V1_SX300.jpg"
      alt="Naruto Poster"
      width="400px"
    />
  </div>
</template>

<script>
import { ref } from "@vue/reactivity";
export default {
  name: "TampilaDeapan",
  setup() {
    const judul1 = ref("Vue");
    const judul2 = ref("Movie");
    return {
      judul1,
      judul2,
    };
  },
};
</script>

<style>
</style>