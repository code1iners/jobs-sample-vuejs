<template>
  <h1>Job Detail Page</h1>
  <p>The job id is {{ $route.params.id }}</p>
</template>

<script>
export default {
  props: ["id"],
  mounted() {
    console.log(this.id);
  },
};
</script>

<style></style>
