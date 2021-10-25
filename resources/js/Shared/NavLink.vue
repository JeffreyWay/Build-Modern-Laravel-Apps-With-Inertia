<template>
  <Link
    class="text-black hover:underline"
    :class="{'font-bold underline': active }"
  >
    <slot />
  </Link>
</template>

<script>
export default {
  props: {
    active: Boolean
  }
};
</script>
