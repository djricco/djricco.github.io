---
title: DJ Ricco
---

<html lang="en">
<head>
  <meta charset="utf-8">
  <title>DJ Ricco</title>


  <!-- Mobile Specific Metas
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- CSS
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="stylesheet" href="/css/normalize.css">
  <link rel="stylesheet" href="/css/skeleton.css">

  <!-- Favicon
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="icon" type="image/png" href="/images/favicon.ico">

</head>
<body>
  <style type="text/css">

  #logo {
    width: 90%;
  }

  @media (min-width: 800px) {
    #logo {
      width: 780px;
    }
  }

  h1 {
      font-size: 3rem;
      line-height: 1.2;
      letter-spacing: -.1rem;
  }

  .social .icon {
      width: 28px;
      height: 26px;
      display: inline-block;
      background: url(/images/social.png) center center no-repeat;
      margin: 0;
      vertical-align: middle;
  }

  .instagram .icon {
      background-position: -28px 0;
  }

  a {
    color: white;
    text-decoration: none;  
  }

  </style>
<div class="bg">
	<img id="logo" src="/images/logo.svg">
  <div class="row" style="margin-bottom: 15px;">
    <div class="six columns">
      <div style="color: #fff;">
        contato: 11 98292 6242
      </div>
    </div>
    <div class="six columns">
      <div class="social instagram">
        <a href="https://www.instagram.com/djricco_oficial/" target="_blank">
          <span class="icon"></span>
          <span class="title">_djricco</span>
        </a>
      </div>
    </div>
  </div>
	

{% for post in site.posts %}
  {{ post }}
{% endfor %}


</div>
</body>
</html>
