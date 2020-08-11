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
      d="M12,10c-1.1,0-2,0.9-2,2s0.9,2,2,2s2-0.9,2-2S13.1,10,12,10z M5,10c-1.1,0-2,0.9-2,2s0.9,2,2,2s2-0.9,2-2S6.1,10,5,10z M19,10c-1.1,0-2,0.9-2,2s0.9,2,2,2s2-0.9,2-2S20.1,10,19,10z"
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