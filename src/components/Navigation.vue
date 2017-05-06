<template>
  <nav class="nav has-shadow">
    <div class="container">
      <left-links />
      <span class="nav-toggle">
        <span></span>
        <span></span>
        <span></span>
      </span>
      <right-links />
    </div>
  </nav>
</template>

<script>
  import RightLinks from './RightLinks.vue';
  import LeftLinks from './LeftLinks.vue';

  export default {
    components: { RightLinks, LeftLinks }
  }
</script>

<style lang="scss">

</style>
