<template>
  <div class="home">
  <Header />
    <Hero />
    <Services/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import Services from '@/components/Services.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Services,
}
}
</script>
