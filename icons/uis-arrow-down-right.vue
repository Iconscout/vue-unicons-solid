<template>
  <svg
    v-bind="$attrs"
    :width="size"
    :height="size"
    xmlns="http://www.w3.org/2000/svg"
    class="ui-svg-inline"
    viewBox="0 0 24 24"
    fill="currentColor"
  >
    <path
      d="M17,6c-0.6,0-1,0.4-1,1v7.6L7.7,6.3c-0.4-0.4-1-0.4-1.4,0c-0.4,0.4-0.4,1,0,1.4l8.3,8.3H7c-0.6,0-1,0.4-1,1s0.4,1,1,1h10c0.6,0,1-0.4,1-1V7C18,6.4,17.6,6,17,6z"
    />
  </svg>
</template>

<script>
import '../utils/style.css'

export default {
  props: {
    size: {
      type: String,
      default: '1em'
    }
  }
}
</script>