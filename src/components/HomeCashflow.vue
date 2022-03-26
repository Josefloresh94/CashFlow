<template>
  <Layout>
    <template #header>
      <Header />
    </template>
    <template #resume>
      <Resume />
    </template>
    <template #movements>
      <Movements />
    </template>
  </Layout>
</template>

<script>
import Layout from "./LayoutCashflow.vue";
import Header from "./HeaderCashflow.vue";
import Resume from "./Resume/IndexCashflow.vue";
import Movements from "./MovementsCashflow.vue";
export default {
  components: {
    Layout,
    Header,
    Resume,
    Movements,
  },
};
</script>
