<template>
  <div class="com-container">
    <p>{{common.message}}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      common: {
        name: "demo-second",
        message: "welcome to demo-second page..."
      }
    };
  }
};
</script>
