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
      d="M12,2C6.5,2,2,6.5,2,12s4.5,10,10,10s10-4.5,10-10S17.5,2,12,2z M13,12c0,0.6-0.4,1-1,1c-0.2,0-0.3,0-0.5-0.1l-2.6-1.5c-0.5-0.3-0.6-0.9-0.4-1.4c0.3-0.5,0.9-0.6,1.4-0.4l1.1,0.6V7c0-0.6,0.4-1,1-1s1,0.4,1,1V12z"
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