<template>
  <h1>World.vue</h1>
  <div>{{ reversedMessage }}</div>
</template>

<script>
import { mapState, mapGetters, mapMutations, mapActions } from 'vuex';

export default {
  computed: {
    // reversedMessage() {
    //   return this.$store.getters['message/reversedMessage'];
    // },
    ...mapGetters('message', ['reversedMessage']),
  },
};
</script>

<style lang="scss" scoped>
h1 {
  color: royalblue;
}
</style>
