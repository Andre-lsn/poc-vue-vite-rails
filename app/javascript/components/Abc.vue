<template lang="">
  <div>
    <h2>Eu sou uma batata {{ color }}</h2>

    <button @click="increment">
      Increment
    </button>

    <span>
      {{  count  }}
    </span>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        color: 'purple',
        count: 0
      }
    },
    methods: {
      increment () {
        this.count = this.count + 1
      }
    }
  }
</script>