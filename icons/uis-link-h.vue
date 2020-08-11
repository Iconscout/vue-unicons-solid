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
      d="M10,15H7c-1.7,0-3-1.3-3-3s1.3-3,3-3h3c0.6,0,1-0.4,1-1s-0.4-1-1-1H7c-2.8,0-5,2.2-5,5s2.2,5,5,5h3c0.6,0,1-0.4,1-1S10.6,15,10,15z M17,7h-3c-0.6,0-1,0.4-1,1s0.4,1,1,1h3c1.7,0,3,1.3,3,3s-1.3,3-3,3h-3c-0.6,0-1,0.4-1,1s0.4,1,1,1h3c2.8,0,5-2.2,5-5S19.8,7,17,7z M8,12c0,0.6,0.4,1,1,1h6c0.6,0,1-0.4,1-1s-0.4-1-1-1H9C8.4,11,8,11.4,8,12z"
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