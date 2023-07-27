<template>
  <div class="main-container">
    <h1>Gerenciar pedidos: </h1>
    <DashboardCom/>
  </div>
</template>

<script>
import DashboardCom from '@/components/DashboardCom.vue';

export default {
  name: 'PedidosView',
  components: {
    DashboardCom
  }
}


</script>
