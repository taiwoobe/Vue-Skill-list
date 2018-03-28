<template>
  <div class="about">
      <h1> Hello {{ username }} This is an About Page</h1>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laudantium, totam molestias modi, unde ipsa deleniti nam error neque impedit doloremque saepe? Minus sequi ea a aliquid deleniti quidem. Atque, commodi.</p>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      username: this.$route.params.name
    };
  }
};
</script>