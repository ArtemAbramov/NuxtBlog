<template>
  <div class="wrapper-content wrapper-content--fixed">
    <section class="about">
      <div class="container">
        <h1 class="title">About my blog: </h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia aliquam commodi ratione eaque minima, est alias voluptatem consectetur inventore ipsam!</p>
        <intro title='Lorem ipsum dolor sit amet consectetur' />
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia aliquam commodi ratione eaque minima, est alias voluptatem consectetur inventore ipsam!</p>
        <img src="@/assets/img/about.jpg" alt="">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia aliquam commodi ratione eaque minima, est alias voluptatem consectetur inventore ipsam!</p>
      </div>
    </section>
  </div>
</template>

<script>
import intro from '@/components/UI/Intro.vue'
export default {
  components: { intro }
}
</script>

<style lang="scss">
.about {
  text-align: center;

  p {
    margin-bottom: 10px;
  }
}
</style>