<template lang="html">
  <div class="app">


      <button type="submit" @click="updateCount">Increment Counter: {{ count }}</button>


    <pre>{{ $data | json}}</pre>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: '',
      count: 0,
    };
  },

  methods: {
    handleIt() {
      alert('Handled');
    },

    updateCount() {
      this.count += 1;
    },
  },
};
</script>
