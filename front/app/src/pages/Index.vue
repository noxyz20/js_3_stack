<template>
  <q-page class="flex flex-center bg-secondary">

    <q-uploader
        url="http://localhost:5000/upload"
        color="primary"
        flat
        bordered
        style="max-width: 300px"
      />

  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'PageIndex'
})
</script>
