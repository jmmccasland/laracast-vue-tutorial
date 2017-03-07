<template lang="html">
  <div class="app">
    <h1>{{ message }}</h1>
    <input v-model="message">
  </div>

</template>

<script>
export default {
  data() {
    return {
      message: 'Hello World',
    };
  },

  methods: {

  },
};
</script>
