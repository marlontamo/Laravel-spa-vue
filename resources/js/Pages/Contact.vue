<template>
  <div>
    <h1>{{ title }}</h1>
    <p>You can contact us at: {{ email }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Contact Page',
      email: 'contact@example.com'
    };
  }
};
</script>
