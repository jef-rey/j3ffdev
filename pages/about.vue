<template>
  <div>
    <h1>about JEFF</h1>
    <h2>A bit about myself:</h2>
    <p>
      I am a sofware engineer and currently working as a systems administrator.
      I love Linux and noodles and gusty ocean breezes
    </p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'About',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Learn about Jeff',
        },
      ],
    }
  },
}
</script>


<style scoped>
</style>