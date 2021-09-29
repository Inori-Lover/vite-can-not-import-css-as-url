<script setup>
  // import justImportCSS from './test.css'
  import importCSSAsURL from './test.css?url'
  // import justImportJS from './test.js'
  import importJSAsURL from './test.js?url'
  // import justImportPNG from './test.png'
  import importPNGAsURL from './test.png?url'
  // import justImportSvg from './test.svg'
  import importSvgAsURL from './test.svg?url'
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
  <code>{{ importPNGAsURL }}</code>
  <br />
  <br />
  <code>{{ importSvgAsURL }}</code>
</template>

