<template>
  <text class="message">Roy, let's use Vue.js to build your Weex app.</text>
</template>

<script>
export default {
  name: 'hello-world',
  components: { },
  props: [
    'index'
  ],
  data: () => ({
  }),
  created () {
    if (this.index === 't') {
      console.error(2)
    }
  },
  methods: {
  }
}
</script>
