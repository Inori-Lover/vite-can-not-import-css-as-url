<script setup>
  // import justImportCSS from './test.css'
  import importCSSAsURL from './test.css?url'
  // import justImportJS from './test.js'
  import importJSAsURL from './test.js?url'
  // import justImportImg from './test.png'
  import importImgAsURL from './test.png?url'
</script>

<template>
  expect: '<code>/path/to/file.ext</code>'
  <br />
  <br />
  <code>{{ importCSSAsURL }}</code>
  <br />
  <br />
  <code>{{ importJSAsURL }}</code>
  <br />
  <br />
  <code>{{ importImgAsURL }}</code>
</template>

