<template>
  <div>
    <h1>{{ title }}</h1>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Home Page',
      message: 'Welcome to our Laravel + Vue SPA!'
    };
  }
};
</script>
