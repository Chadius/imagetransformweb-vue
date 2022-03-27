<template>
  <div>
    <h1>Image Transformer</h1>

    <form>
      <button id="upload">Upload Image</button>
      <p>Preview Window</p>
      <p>Input File Description</p>

      <label for="formula-text">Transformation Formula</label>
      <textarea id="formula-text"></textarea>
      <button id="preview">Preview</button>

      <label for="output-width">Output Width</label>
      <input type="number" id="output-width">

      <label for="output-height">Output Height</label>
      <input type="number" id="output-height">
      <button id="download">Download</button>
    </form>
  </div>
</template>

<script>
export default {
  name: 'TransformInput',
  props: {
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
