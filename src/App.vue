<script setup>
import Editor from "@tinymce/tinymce-vue";
</script>

<template>
  <main id="sample">
    <Editor
      api-key="ACA-TU-API-KEY"
      :init="{
        plugins: 'lists link image table code help wordcount'
      }"
    />
  </main>
</template>

<style scoped>
#sample{
  display: flex;
  flex-direction: column;
  place-items: center;
  width: 1000px;
}
</style>
