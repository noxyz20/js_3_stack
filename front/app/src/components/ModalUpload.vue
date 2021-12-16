<template>

  <div class="q-pa-md">
    <h4 class="q-m-none">Upload File :</h4>
    <div class="q-gutter-sm row items-start">
      <q-uploader
        url="http://localhost:4444/upload"
        style="max-width: 300px"
      />
    </div>
  </div>
</template>

<script>
export default {
  setup () {
    return {}
  }
}
</script>
