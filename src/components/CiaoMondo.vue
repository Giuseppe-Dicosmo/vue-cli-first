<template>
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  name: "CiaoMondo",
  data() {
    return {
      title: "La mia prima app con Vue CLI!",
    };
  },
};
</script>

<style scoped lang="scss">
h1 {
  color: red;
}
</style>
