<template>
  <div @click="increment">
    <div class="hero">
      <Hero :counter="counter" />
    </div>
    <div class="tweet">
      <Tweet :counter="counter" />
    </div>
    <div class="menus">
      <Menus />
    </div>
    <div class="dark-title">
      <DarkTitle />
    </div>
    <div class="section">
      <Section :counter="counter" />
    </div>
    <div class="tiles">
      <Tiles :counter="counter" />
    </div>
    <div class="footer">
      <Footer />
    </div>
  </div>
</template>

<script>
  import Footer from './app/Footer';
  import Tiles from './app/Tiles';
  import Section from './app/Section';
  import Hero from './app/Hero';
  import DarkTitle from './app/DarkTitle';
  import Tweet from './app/Tweet';
  import Menus from './app/Menus';

  export default {
    name: 'App',
    components: { Menus, Tweet, DarkTitle, Hero, Section, Tiles, Footer },
    data() {
      return {
        counter: 0,
      };
    },
    methods: {
      increment() {
        this.counter++;
      },
    },
  };
</script>
