<template>
  <div class="overlay" :class="transparent ? 'overlay-transparent' : ''" @click="$emit('click', $event)"></div>  
</template>

<script>
export default {
  name: 'vui-overlay',
  props: {
    transparent: {
      type: Boolean,
      default: false
    }
  }
}
</script>
