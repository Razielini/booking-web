<template>
  <div
    class="w-full bg-black text-white"
  >
    {{ title }}
  </div>
</template>

<script lang="ts">
import { Vue } from 'vue-property-decorator'

export default class AppBar extends Vue {
  title: string = 'Title App Bar'
}
</script>
