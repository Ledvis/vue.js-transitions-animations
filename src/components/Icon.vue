<template>
  <svg>
    <use :href="use"></use>
  </svg>
</template>

<script>
export default {
  name: "Icon",
  props: {
    use: String
  }
};
</script>
