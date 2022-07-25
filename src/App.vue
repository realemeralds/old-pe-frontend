<template>
  <h1>post request text</h1>
  <p>{{}}</p>
  <button @click="doSomething">sdakjsahd</button>
</template>

<script lang="ts">
export default {
  data(): object {
    return {
      count: 0,
    };
  },
  created(): {
    fetch("localhost:5000": string): Promise<T>.then((response) => response.json()).then((data) => console.log(data))
  }
};
</script>

<style scoped>
button {
  font-weight: bold;
}
</style>
