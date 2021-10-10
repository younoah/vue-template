<template>
  <main>
    <h1>App.vue</h1>
    <Hello />
    <World />
  </main>
</template>

<script>
import Hello from '~/components/Hello';
import World from '~/components/World';

export default {
  components: {
    Hello,
    World,
  },
};
</script>

<style lang="scss" scoped></style>
