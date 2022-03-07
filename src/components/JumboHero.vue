<template>
  <div class="container">
    <h1>{{ hero }}</h1>
  </div>
</template>

<script>
export default {
  name: "JumboHero",
  data() {
    return {
      hero: "JumboTron",
    };
  },
};
</script>

<style scoped lang="scss">
.container {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 35vh;
  background: url("https://picsum.photos/200/300") no-repeat center;
  background-size: cover;
}

h1 {
  color: green;
  text-align: center;
}
</style>
