---
layout: default
---

<!DOCTYPE html>
<html lang="{{ site.lang | default: "en-US" }}">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  {% seo %}
  <link rel="stylesheet" href="{{ "/assets/css/style.css?v=" | append: site.github.build_revision | relative_url }}">
  <!--[if lt IE 9]>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js"></script>
  <![endif]-->
  {% include head-custom.html %}
</head>
<body>
  <div class="container">
    <aside class="sidebar">
      <ul class="sidebar-list">
        <li><a href="#header1">Header 1</a></li>
        <li><a href="#header2">Header 2</a></li>
        <li><a href="#header3">Header 3</a></li>
        <li><a href="#header4">Header 4</a></li>
        <li><a href="#header5">Header 5</a></li>
        <li><a href="#header6">Header 6</a></li>
        <!-- Add more links for other sections as needed -->
      </ul>
    </aside>

    <div class="main-content">
      Text can be **bold**, _italic_, or ~~strikethrough~~.
      <!-- Rest of your content -->

      <h1 id="header1">Header 1</h1>
      <!-- Content for Header 1 -->

      <h2 id="header2">Header 2</h2>
      <!-- Content for Header 2 -->

      <h3 id="header3">Header 3</h3>
      <!-- Content for Header 3 -->

      <h4 id="header4">Header 4</h4>
      <!-- Content for Header 4 -->

      <h5 id="header5">Header 5</h5>
      <!-- Content for Header 5 -->

      <h6 id="header6">Header 6</h6>
      <!-- Content for Header 6 -->

      <!-- Your content continues -->
    </div>
  </div>
  <script src="{{ "/assets/js/scale.fix.js" | relative_url }}"></script>
</body>
</html>
