<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Practical 10 - Iframe</title>
<style>
body{margin:0;font-family:Arial,sans-serif;background:linear-gradient(to right,#6dd5ed,#a1c4fd);text-align:center;}
header{background:#222;color:#fff;padding:15px;}
h2{margin-top:10px;}
.container{width:90%;margin:auto;padding:20px;}
.box{background:#f4f4f4;padding:20px;margin:25px 0;border-radius:15px;box-shadow:0 5px 15px rgba(0,0,0,0.3);}
iframe{width:100%;height:400px;border:none;margin-top:15px;border-radius:12px;}
footer{background:#222;color:#fff;padding:10px;margin-top:20px;}
</style>
</head>
<body>
<header>
<h1>Practical 10 - HTML Iframe</h1>
<p>Embedding External Pages, Google Maps & Videos</p>
</header>
<div class="container">
<div class="box">
<h2>Embedded External Website</h2>
<p>Example: Wikipedia</p>
<iframe src="https://www.wikipedia.org" title="Wikipedia Website" loading="lazy"></iframe>
</div>
<div class="box">
<h2>SB Jain College Location</h2>
<p>Nagpur, Maharashtra</p>
<iframe src="https://www.google.com/maps?q=S.B.%20Jain%20Institute%20of%20Technology%20Management%20and%20Research%20Nagpur&output=embed" title="SB Jain College Map" loading="lazy" allowfullscreen></iframe>
</div>
<div class="box">
<h2>Embedded YouTube Video</h2>
<iframe src="https://www.youtube.com/embed/ysz5S6PUM-U" title="YouTube video player" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
</div>
<footer>
<p>Submitted for Web Designing Lab Practical</p>
</footer>
</body>
</html>
