<template>
  <div>
    <p>카운터! {{ cnt }}</p>
    <button @click="up">올리기</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cnt: 100
    }
  },
  methods: {
    up() {
      this.cnt++
    },
  }
}
</script>