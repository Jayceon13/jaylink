<template>
  <div class="list-page">
    <q-page class="flex flex-direction: column flex-center">
      <q-avatar size="130px">
          <img src="~assets/avatar.jpg">
        </q-avatar>
      <img
        alt="KIKA PRO MAKEUP"
        src="~assets/KIKAPROMAKEUP.svg"
        style="width: 200px; height: 200px"
      >
    </q-page>
  </div>
</template>

<style lang="scss">
.list-page {
  background-image: linear-gradient(#FBEEFF, #D7A6E8);
}
</style>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
