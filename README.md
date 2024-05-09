<!DOCTYPE html>
<html>
<body>

<h1>SANGAT MENGERIKAN</h1>

<p>Pencet tombol dibawah untuk mengetahuinya.</p>

<button onclick="showContent()">Show hidden content</button>

<template>
  <h2>UntukMu</h2>
  <img src="https://cdn.britannica.com/45/5645-050-B9EC0205/head-treasure-flower-disk-flowers-inflorescence-ray.jpg" width="214" height="204">
</template>

<script>
function showContent() {
  let temp = document.getElementsByTagName("template")[0];
  let clon = temp.content.cloneNode(true);
  document.body.appendChild(clon);
}
</script>

</body>
</html>
