<script setup>
  import fileImportResult from './HelloWorld.css'
  import fileWithURLImportResult from './HelloWorld.css?url'
</script>

<template>
  expect: '<code>/path/to/file.css</code>'
  <br />
  <br />
  use <code>import fileImportResult from './HelloWorld.css'</code> :
  <br />
  <code>{{ fileImportResult }}</code>
  <br />
  <br />
  use <code>import fileWithURLImportResult from './HelloWorld.css?url'</code> :
  <br />
  <code>{{ fileWithURLImportResult }}</code>
  <br />
</template>

