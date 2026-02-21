<template>
  <NavbarComponentsView></NavbarComponentsView>
  <div class="container">
    <div class="row">
      <div class="col-xl-3" v-for="(item,index) in 8" :key="index">
        <ImgCardComponentsView></ImgCardComponentsView>
      </div>
    </div>
  </div>
</template>

<script>
import NavbarComponentsView from "@/components/NavbarComponentsView.vue";
import ImgCardComponentsView from "@/components/ImgCardComponentsView.vue";
export default {
  components: {
    NavbarComponentsView, ImgCardComponentsView
  }
}
</script>