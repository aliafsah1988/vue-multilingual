<template>
  <div class="home">
    <img class="main-image" src="@/assets/background.png" />
    <SampleComponent />
  </div>
</template>

<script>
import SampleComponent from "@/components/SampleComponent";

export default {
  name: "home",
  components: {
    SampleComponent
  }
};
</script>

<style lang="scss" scoped>
.main-image {
  width: 600px;
}
</style>
