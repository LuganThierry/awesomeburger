<template>
  <BannerComp/>
  <div class="main-container">
    <h1 class="form-title-monte">Monte o seu Awesome Burger</h1>
    <FormComp/>
  </div>

</template>

<script>
import BannerComp from '@/components/BannerComp.vue';
import FormComp from '@/components/FormComp.vue';

export default {
  name: 'HomeView',
  components: {
    BannerComp,
    FormComp
  }
}

</script>

<style>

.form-title-monte {

  margin: 0 auto 0 -60px;

}

</style>
