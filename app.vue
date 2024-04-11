<template>
  <div>
    <FormKit type="form" @submit="handleSubmit">
      <FormKit type="text" name="title" label="Title" />
    </FormKit>
  </div>
</template>

<script setup lang="ts">
function handleSubmit(data: any, node: FormKitNode) {
  console.log("Data", data);
}
</script>
