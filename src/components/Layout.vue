<template>
  <main>
    <navigation />
    <slot></slot>
  </main>
</template>

<script>
  import Navigation from './Navigation.vue';

  export default {
    components: { Navigation }
  }
</script>

<style lang="scss">

</style>
