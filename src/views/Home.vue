<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <TheSidebar />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'
import TheSidebar from '@/components/TheSidebar.vue'

@Component({
  components: {
    TheSidebar,
  },
})
export default class Home extends Vue {

}

</script>
