<!doctype html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>{{ page.title }} - {{ site.title }}</title>
  <style>
    body{font-family:system-ui,Segoe UI,Roboto,"Noto Sans CJK SC",sans-serif;max-width:900px;margin:36px auto;color:#222;padding:0 16px}
    header,footer{border-bottom:1px solid #eee;padding-bottom:12px;margin-bottom:18px}
    nav a{margin-right:12px;color:#0366d6;text-decoration:none}
    .meta{color:#666;font-size:0.9em}
    .container{margin-top:12px}
  </style>
</head>
<body>
  <header>
    <h1><a href="{{ '/' | relative_url }}" style="color:inherit;text-decoration:none">{{ site.title }}</a></h1>
    <nav>
      <a href="{{ '/' | relative_url }}">首页</a>
      <a href="{{ '/about.html' | relative_url }}">关于我</a>
      <a href="{{ '/posts/生活记录/' | relative_url }}">生活记录</a>
    </nav>
  </header>

  <main class="container">
    {{ content }}
  </main>

  <footer>
    <small>© {{ site.title }}</small>
  </footer>
</body>
</html>
