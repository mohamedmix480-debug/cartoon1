# cartoon1
cartoon
<!doctype html>

<html lang="ar">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>موقع أنمى - معرض الصور</title>
  <style>
    :root{ --bg:#0f1115; --card:#111215; --accent:#e63946; --text:#e6e6e6; }
    *{box-sizing:border-box}
    body{margin:0;font-family:Tahoma, Arial, sans-serif;background:linear-gradient(180deg,#0b0c0f, #0f1115);color:var(--text);min-height:100vh;display:flex;flex-direction:column;align-items:center}
    header{width:100%;padding:24px 16px;text-align:center}
    h1{margin:0;font-size:clamp(18px,3vw,32px)}
    .gallery{width:100%;max-width:980px;padding:16px;display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px}
    .card{background:var(--card);border-radius:12px;overflow:hidden;box-shadow:0 6px 20px rgba(0,0,0,0.6);display:flex;flex-direction:column;align-items:stretch;text-align:center}
    .thumb{width:100%;aspect-ratio:3/4;object-fit:cover;display:block}
    .caption{padding:12px 10px;font-size:16px;background:linear-gradient(0deg,rgba(0,0,0,0.12),transparent);}
    .caption .title{font-weight:700}
    .caption .alt{display:block;font-size:13px;color:rgba(230,230,230,0.7);margin-top:6px}
    footer{margin:28px 0 40px;color:rgba(230,230,230,0.6)}
    @media (max-width:420px){.caption{font-size:14px}}
  </style>
</head>
<body>
  <header>
    <h1>معرض أنمى</h1>
  </header>  <main class="gallery">
    <!-- بطاقة 1 -->
    <article class="card">
      <img class="thumb" src="./1000002778.jpg" alt="Tokyo Ghoul">
      <div class="caption">
        <div class="title">Tokyo Ghoul</div>
        <div class="alt">طوكيو غول</div>
      </div>
    </article><!-- بطاقة 2 -->
<article class="card">
  <img class="thumb" src="./1000002779.jpg" alt="Claymore">
  <div class="caption">
    <div class="title">Claymore</div>
    <div class="alt">كلايمور</div>
  </div>
</article>

<!-- بطاقة 3 -->
<article class="card">
  <img class="thumb" src="./1000002783.webp" alt="One Piece">
  <div class="caption">
    <div class="title">One Piece</div>
    <div class="alt">ون بيس</div>
  </div>
</article>

  </main>  <footer>افتح هذا الملف (anime-gallery-index.html) في المتصفح لمشاهدة الموقع.</footer>
</body>
</html>
