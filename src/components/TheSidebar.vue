<template>
  <div>

  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'
import ISidebarLink from '@/services/ISidebarLink'

@Component({
  props: {
    links: {
      type: Array as () => ISidebarLink[],
      required: true,
    },
  },
})
export default class TheSidebar extends Vue {
}
</script>
