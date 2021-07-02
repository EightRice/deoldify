<div class="d-flex flex-column flex-md-row align-items-center p-3 px-md-4 mb-3 bg-white border-bottom shadow-sm">

##### SingularityNET

[User's Guide Hub](../index.html)</div>

<div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">

# deoldify-colorizer

Service User's Guide

</div>

<script>Holder.addTheme('thumb', { bg: '#55595c', fg: '#eceeef', text: 'Thumbnail' });</script> <script>function Editor(preview) { this.update = function () { var rawFile = new XMLHttpRequest(); var allText = "# Fail!"; rawFile.open("GET", "deoldify-colorizer.md", false); rawFile.onreadystatechange = function () { if(rawFile.readyState === 4) { if(rawFile.status === 200 || rawFile.status === 0) { allText = rawFile.responseText; } } }; rawFile.send(null); let converter = new showdown.Converter({ tables: true }); let html = converter.makeHtml(allText); preview.innerHTML = converter.makeHtml(html); }; this.update(); } var $ = function (id) { return document.getElementById(id); }; new Editor($("preview"));</script>