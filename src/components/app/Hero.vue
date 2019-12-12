<template>
  <section class="hero">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">
          Hero counter {{ counter }}
        </h1>
        <h2 class="subtitle">
          Counter: {{ counter }}
        </h2>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Hero',
    props: ['counter'],
  };
</script>

<style scoped>

</style>
