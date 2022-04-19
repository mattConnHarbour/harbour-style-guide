<template>
  <div>
    <img :style="{maxWidth: '140px'}" :src="src" />
  </div>
</template>

<script>
  export default {
    props: ['src',],
    data() {
      return {
      }
    }
  }
</script>
