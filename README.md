<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>صفحة هبوط - سمو العلم</title>
  <style>
    :root{
      --bg:#0f172a;
      --card:#0b1220;
      --accent1:#7c3aed;
      --accent2:#06b6d4;
      --text:#e6eef8;
      --muted:#9fb3c8;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family:system-ui,-apple-system,Segoe UI,Roboto,"Noto Sans Arabic",sans-serif;
      background:linear-gradient(180deg,var(--bg) 0%, #071022 100%);
      color:var(--text); -webkit-font-smoothing:antialiased;
      display:flex;align-items:center;justify-content:center;padding:20px;
    }
    .wrap{
      width:100%;max-width:420px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:18px;padding:28px;box-shadow:0 8px 30px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03);
    }
    .brand{display:flex;align-items:center;gap:14px;margin-bottom:18px}
    .logo{
      width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--accent1),var(--accent2));display:flex;align-items:center;justify-content:center;font-weight:700;color:white;font-size:20px
    }
    h1{margin:0;font-size:20px}
    p.lead{margin:4px 0 18px;color:var(--muted);font-size:14px}

    .buttons{display:grid;gap:12px}
    .btn{
      display:flex;gap:12px;align-items:center;padding:14px;border-radius:12px;text-decoration:none;color:var(--text);background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border:1px solid rgba(255,255,255,0.03);transition:transform .12s ease, box-shadow .12s ease;
    }
    .btn:active{transform:scale(.995)}
    .btn:hover{box-shadow:0 6px 20px rgba(12,18,40,0.6)}
    .icon{
      width:42px;height:42px;border-radius:10px;display:flex;align-items:center;justify-content:center;background:rgba(255,255,255,0.03);
      flex-shrink:0
    }
    .label{display:flex;flex-direction:column}
    .label .title{font-weight:600}
    .label .subtitle{font-size:13px;color:var(--muted)}

    /* Special colored buttons */
    .call{border-left:4px solid #10b981}
    .facebook{border-left:4px solid #1877f2}
    .instagram{border-left:4px solid #e1306c}
    .whatsapp{border-left:4px solid #25D366}

    /* responsive tweaks */
    @media (max-width:380px){.logo{width:56px;height:56px;font-size:18px}.btn{padding:12px}.icon{width:38px;height:38px}}
  </style>
</head>
<body>
  <main class="wrap" role="main">
    <header class="brand">
      <div class="logo">س</div>
      <div>
        <h1>سمو العلم للسفر والسياحة</h1>
        <p class="lead">وصلنا بسرعة — اختر ما تريد</p>
      </div>
    </header>

    <nav class="buttons" aria-label="روابط سريعة">
      <!-- Call button -->
      <a class="btn call" href="tel:+9647863306853">
        <span class="icon" aria-hidden>
          <!-- phone SVG -->
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.86 19.86 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.86 19.86 0 0 1-3.07-8.63A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.12 1.21.37 2.4.73 3.55a2 2 0 0 1-.45 2.11L8.09 10.91a16 16 0 0 0 6 6l1.53-1.53a2 2 0 0 1 2.11-.45c1.15.36 2.34.61 3.55.73A2 2 0 0 1 22 16.92z" fill="currentColor"/>
          </svg>
        </span>
        <span class="label"><span class="title">اتصل الآن</span><span class="subtitle">+964 786 330 6853</span></span>
      </a>

      <!-- Facebook -->
      <a class="btn facebook" href="https://www.facebook.com/share/1FpQmuYKZg/" target="_blank" rel="noopener noreferrer">
        <span class="icon" aria-hidden>
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M22 12.07C22 6.48 17.52 2 11.93 2S2 6.48 2 12.07c0 4.97 3.66 9.09 8.44 9.92v-7.03H8.03v-2.89h2.41V9.34c0-2.39 1.43-3.71 3.62-3.71 1.05 0 2.15.19 2.15.19v2.37h-1.21c-1.2 0-1.57.74-1.57 1.5v1.8h2.67l-.43 2.89h-2.24v7.03C18.34 21.16 22 17.04 22 12.07z" fill="currentColor"/></svg>
        </span>
        <span class="label"><span class="title">فيسبوك</span><span class="subtitle">شارك صفحتنا</span></span>
      </a>

      <!-- Instagram -->
      <a class="btn instagram" href="https://www.instagram.com/sumuu_aleilm?igsh=aG4zNGlhcnl4d2py" target="_blank" rel="noopener noreferrer">
        <span class="icon" aria-hidden>
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5zm5 6.2A4.8 4.8 0 1 0 16.8 13 4.8 4.8 0 0 0 12 8.2zm6.4-3.6a1.1 1.1 0 1 1-1.1 1.1 1.1 1.1 0 0 1 1.1-1.1z" fill="currentColor"/></svg>
        </span>
        <span class="label"><span class="title">انستغرام</span><span class="subtitle">تابعنا @sumuu_aleilm</span></span>
      </a>

      <!-- WhatsApp -->
      <a class="btn whatsapp" href="https://wa.me/9647863306853" target="_blank" rel="noopener noreferrer">
        <span class="icon" aria-hidden>
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M20.5 3.5A11 11 0 0 0 3.5 20.5L2 22l1.6-4.6A11 11 0 1 0 20.5 3.5zM12 19.2a7.2 7.2 0 1 1 0-14.4 7.2 7.2 0 0 1 0 14.4zM17 14.3c-.3-.1-1.8-.9-2.1-1-.3-.1-.4-.1-.6.1-.2.2-.9.9-1.1 1.1-.2.2-.4.2-.7.1-.8-.3-2.6-1.5-3.5-2.8-.3-.4 0-.6.2-.9.2-.2.3-.4.5-.6.2-.2.2-.4 0-.7-.1-.3-.6-1-1-1.4-.3-.3-.6-.3-.9-.3-.2 0-.4 0-.7.1s-.9.4-1.4 1.1c-.5.7-.6 1.2-.6 1.8 0 .6.3 1.4.9 2.1 1.1 1.3 3 2.8 5.1 3.4 2.1.6 2.9.6 3.9.5.9-.1 1.8-.6 2.1-1.2.3-.6.3-1.1.2-1.2-.1-.1-1.1-.6-1.4-.7z" fill="currentColor"/></svg>
        </span>
        <span class="label"><span class="title">واتساب</span><span class="subtitle">+964 786 330 6853</span></span>
      </a>
    </nav>

    <p style="margin-top:18px;color:var(--muted);font-size:13px;text-align:center">تم إنشاء الروابط بناءً على ما زودتني به. اضغط على الزر للانتقال أو الاتصال.</p>
  </main>
</body>
</html>
