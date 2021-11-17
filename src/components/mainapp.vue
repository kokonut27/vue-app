<template>
  <h1> {{ msg }} </h1>
</template>

<script>
export default {
  name: 'mainapp',
  props: {
    msg: String
  }
}
</script>