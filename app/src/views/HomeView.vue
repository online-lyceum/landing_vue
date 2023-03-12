<template>
    <div class="main-header">
        <start-header/>
        <title-project/>
    </div>
</template>

<script>
import StartHeader from "@/components/StartHeader.vue"
import TitleProject from "@/components/TitleProject.vue";
export default {
  name: 'HomeView',
  components: {
      TitleProject,
    StartHeader
  }
}
</script>
<style>
.main-header {
    position:absolute;
    top:50%;
    width: 100%;
    margin-top: -52px;
}
</style>
