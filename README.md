# new-brand
Чатботоор өөрийн танилцуулга вэб хуудас хийлгүүлэв.
<!-- SAVE AS: index.html  -->
<!doctype html>
<html lang="mn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>K50-style Shop — Жишээ</title>
  <style>
    :root{
      --accent:#111827;
      --primary:#ef4444;
      --muted:#6b7280;
      --card:#ffffff;
      --bg:#f8fafc;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:var(--accent);line-height:1.4}
    header{background:linear-gradient(90deg,#fff 0%, #f7f7f7 100%);border-bottom:1px solid #e6e6e6;position:sticky;top:0;z-index:40}
    .container{max-width:1100px;margin:0 auto;padding:20px}
    .nav{display:flex;gap:16px;align-items:center;justify-content:space-between}
    .brand{display:flex;gap:12px;align-items:center}
    .brand img{width:46px;height:46px;object-fit:cover;border-radius:8px}
    .brand h1{font-size:18px;margin:0}
    .search{flex:1;margin:0 20px}
    .search input{width:100%;padding:10px 14px;border-radius:8px;border:1px solid #ddd}
    .nav-links{display:flex;gap:12px;align-items:center}
    .btn{background:var(--primary);color:#fff;padding:8px 12px;border-radius:8px;border:0;cursor:pointer}
    .ghost{background:transparent;border:1px solid #ddd;padding:8px 12px;border-radius:8px;cursor:pointer}

    /* hero */
    .hero{background:linear-gradient(90deg,#fff,#f2f8ff);padding:28px
    
