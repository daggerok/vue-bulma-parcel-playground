<template>
  <body>
  <section class="section">
    <div class="container">
      <h1 class="title">Section</h1>
      <h2 class="subtitle">
        A simple container to divide your page into <strong>sections</strong>, like the one you're currently reading
      </h2>
      <div class="counter">
        <p>counter: {{ counter }}</p>
      </div>
    </div>
  </section>
  </body>
</template>

<script>
  export default {
    name: 'Section',
    props: ['counter'],
  };
</script>

<style scoped>

</style>
