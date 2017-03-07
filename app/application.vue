<template lang="html">
  <div class="app">
    <form>

      <textarea v-model="message"></textarea>
      <span class="error" v-show="!message">You must enter a message</span>
      <button type="submit" v-show="message">Send Message</button>
    </form>

    <pre>{{ $data | json}}</pre>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: '',
    };
  },

  methods: {

  },
};
</script>
