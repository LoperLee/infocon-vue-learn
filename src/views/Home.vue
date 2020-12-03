<template>
  <div class="home">
    <Counter/>
  </div>
</template>

<script>
export default {
  components: {
    Counter: () => import('@/components/Counter.vue'),
  },
}
</script>
