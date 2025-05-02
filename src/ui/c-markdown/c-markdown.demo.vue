<script setup lang="ts">
const md = `
# XTools.VuiZ.Net

## About
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nisl quis
mollis blandit, nunc nisl aliquam nunc, vitae aliquam nisl nunc vitae nisl.

- Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- Sed euismod, nisl quis mollis blandit, nunc nisl aliquam nunc, vitae aliquam nisl nunc vitae nisl.

[it-tools](https://xtools.vuiz.net)
`;
</script>

<template>
  <c-markdown :markdown="md" />
</template>
