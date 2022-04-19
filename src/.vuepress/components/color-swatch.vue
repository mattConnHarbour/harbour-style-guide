<template>
    <div :style="{display: 'flex'}">
      <div :style="{width: width+'px', height: width+'px', backgroundColor: color, marginRight: '1em'}"></div>
      <p>{{color}}</p>
    </div>
</template>

<script>
  export default {
    props: ['color', 'width'],
    data() {
      return {
      }
    }
  }
</script>
