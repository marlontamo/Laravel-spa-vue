<template>
  <div>
    <h1>{{ title }}</h1>
    <p>{{ description }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'About Us',
      description: 'We are building a single-page application using Laravel 10 and Vue 3.'
    };
  }
};
</script>
