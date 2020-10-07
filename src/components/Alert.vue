<template>
  <div>
    <b-alert variant="success" :show="5" dismissible fade>{{
      message
    }}</b-alert>
  </div>
</template>
<script>
export default {
  props: ["message"],
};
</script>
