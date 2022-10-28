<template>
  <div>
    <p>This is a Vue component, rendered inside a Markdown page</p>
    <ContentSlot :use="$slots.default" />
  </div>
</template>

<style scoped>
p {
  border: 1px solid #787878;
  padding: 2px;
}
</style>