<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Limit of Looped Eternity</title>
  <style>
    :root{
      --bg-1:#06070d;
      --bg-2:#111528;
      --bg-3:#241a35;
      --text:#eef2ff;
      --muted:#b8bfd8;
      --line:rgba(255,255,255,.12);
      --glass:rgba(255,255,255,.08);
      --glass-strong:rgba(255,255,255,.12);
      --accent:#9f7bff;
      --accent-2:#63d7ff;
      --accent-3:#ff8ad8;
      --shadow:0 10px 40px rgba(0,0,0,.35);
      --radius:22px;
      --maxw:1200px;
    }

    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      font-family:Inter,Segoe UI,Arial,sans-serif;
      color:var(--text);
      background:
        radial-gradient(circle at 15% 20%, rgba(99,215,255,.14), transparent 30%),
        radial-gradient(circle at 80% 15%, rgba(159,123,255,.16), transparent 28%),
        radial-gradient(circle at 50% 85%, rgba(255,138,216,.10), transparent 28%),
        linear-gradient(180deg,var(--bg-2),var(--bg-1) 40%, #05060a);
      overflow-x:hidden;
    }

    .noise,
    .grid,
    .aurora,
    .particles{
      position:fixed; inset:0; pointer-events:none;
    }
    .grid{
      background-image:
        linear-gradient(rgba(255,255,255,.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,.03) 1px, transparent 1px);
      background-size:40px 40px;
      mask-image:linear-gradient(to bottom, rgba(0,0,0,.8), transparent 80%);
    }
    .noise{
      opacity:.05;
      background-image:
        radial-gradient(circle, rgba(255,255,255,.8) 1px, transparent 1px);
      background-size:5px 5px;
      mix-blend-mode:soft-light;
    }
    .aurora::before,
    .aurora::after{
      content:"";
      position:absolute;
      width:42vw; height:42vw;
      border-radius:50%;
      filter:blur(70px);
      opacity:.18;
      animation:floatBlob 14s ease-in-out infinite;
    }
    .aurora::before{
      left:-10vw; top:10vh;
      background:radial-gradient(circle, var(--accent-2), transparent 60%);
    }
    .aurora::after{
      right:-10vw; top:22vh;
      background:radial-gradient(circle, var(--accent), transparent 60%);
      animation-delay:-6s;
    }

    @keyframes floatBlob{
      0%,100%{transform:translate(0,0) scale(1)}
      50%{transform:translate(4vw,-3vh) scale(1.08)}
    }

    .particles span{
      position:absolute;
      display:block;
      width:4px; height:4px;
      border-radius:50%;
      background:rgba(255,255,255,.75);
      box-shadow:0 0 12px rgba(255,255,255,.65);
      animation:particleFloat linear infinite;
      opacity:.45;
    }
    @keyframes particleFloat{
      from{transform:translateY(0) scale(.8); opacity:0}
      15%{opacity:.55}
      85%{opacity:.35}
      to{transform:translateY(-110vh) scale(1.3); opacity:0}
    }

    .wrap{position:relative; z-index:2}
    .container{width:min(var(--maxw), calc(100% - 32px)); margin:0 auto}

    header{
      position:sticky; top:0; z-index:20;
      backdrop-filter:blur(18px);
      background:linear-gradient(to bottom, rgba(6,8,15,.76), rgba(6,8,15,.35));
      border-bottom:1px solid rgba(255,255,255,.08);
    }
    .nav{
      display:flex; align-items:center; justify-content:space-between;
      gap:18px; padding:14px 0;
    }
    .brand{
      display:flex; align-items:center; gap:12px; min-width:0;
    }
    .logo{
      width:44px; height:44px; border-radius:14px; position:relative;
      background:linear-gradient(135deg, rgba(159,123,255,.25), rgba(99,215,255,.2));
      border:1px solid rgba(255,255,255,.14);
      box-shadow:var(--shadow);
      overflow:hidden;
    }
    .logo::before, .logo::after{
      content:""; position:absolute; border-radius:50%;
      inset:8px; border:1px solid rgba(255,255,255,.26);
    }
    .logo::after{
      inset:15px 21px 15px 9px;
      border-left-color:transparent;
      transform-origin:center;
      animation:clockHand 7s linear infinite;
    }
    @keyframes clockHand{to{transform:rotate(360deg)}}

    .brand-title{
      font-weight:700; letter-spacing:.08em; text-transform:uppercase;
      font-size:12px; color:var(--muted);
    }
    .brand-name{
      font-size:15px; font-weight:700; white-space:nowrap; overflow:hidden; text-overflow:ellipsis;
    }

    .nav-actions{display:flex; align-items:center; gap:10px; flex-wrap:wrap; justify-content:flex-end}
    .lang-switch{
      display:flex; padding:4px; border-radius:999px;
      background:rgba(255,255,255,.06);
      border:1px solid rgba(255,255,255,.10);
      box-shadow:var(--shadow);
    }
    .lang-btn{
      border:none; background:transparent; color:var(--muted);
      padding:9px 14px; border-radius:999px; cursor:pointer;
      font-weight:600; transition:.25s ease;
    }
    .lang-btn.active{
      color:#fff;
      background:linear-gradient(135deg, rgba(159,123,255,.35), rgba(99,215,255,.25));
      box-shadow:inset 0 0 0 1px rgba(255,255,255,.10);
    }

    .ghost-btn, .primary-btn, .secondary-btn{
      text-decoration:none; display:inline-flex; align-items:center; justify-content:center;
      gap:10px; border-radius:999px; font-weight:700; transition:.25s ease;
      border:1px solid rgba(255,255,255,.10); cursor:pointer;
      white-space:nowrap;
    }
    .ghost-btn{
      padding:11px 16px; color:#fff; background:rgba(255,255,255,.06);
    }
    .primary-btn{
      padding:15px 24px; color:#090b12;
      background:linear-gradient(135deg, #f6f7ff, #98f0ff 70%);
      box-shadow:0 12px 30px rgba(99,215,255,.2);
    }
    .secondary-btn{
      padding:15px 24px; color:#fff; background:rgba(255,255,255,.07);
      backdrop-filter:blur(10px);
    }
    .ghost-btn:hover,.secondary-btn:hover{transform:translateY(-2px); background:rgba(255,255,255,.10)}
    .primary-btn:hover{transform:translateY(-2px) scale(1.01)}

    .hero{
      min-height:94vh; display:grid; place-items:center;
      padding:54px 0 56px;
      position:relative;
    }
    .hero-grid{
      display:grid; gap:28px; grid-template-columns:1.2fr .9fr; align-items:center;
    }
    .panel{
      position:relative;
      background:linear-gradient(180deg, rgba(255,255,255,.10), rgba(255,255,255,.05));
      border:1px solid rgba(255,255,255,.12);
      border-radius:30px;
      box-shadow:var(--shadow);
      overflow:hidden;
      backdrop-filter:blur(16px);
    }
    .panel::before{
      content:""; position:absolute; inset:-1px;
      background:linear-gradient(135deg, rgba(255,255,255,.18), transparent 35%, transparent 65%, rgba(99,215,255,.14));
      mask:linear-gradient(#000 0 0) content-box, linear-gradient(#000 0 0);
      -webkit-mask:linear-gradient(#000 0 0) content-box, linear-gradient(#000 0 0);
      padding:1px;
      -webkit-mask-composite:xor; mask-composite:exclude;
      pointer-events:none;
    }
    .hero-copy{padding:38px}
    .eyebrow{
      display:inline-flex; align-items:center; gap:10px;
      padding:10px 14px; border-radius:999px;
      color:#dbe9ff; font-weight:700; font-size:13px;
      background:rgba(255,255,255,.06);
      border:1px solid rgba(255,255,255,.10);
    }
    .eyebrow-dot{
      width:8px; height:8px; border-radius:50%;
      background:linear-gradient(135deg,var(--accent-2),var(--accent));
      box-shadow:0 0 15px rgba(99,215,255,.7);
      animation:pulse 2.8s ease-in-out infinite;
    }
    @keyframes pulse{
      0%,100%{transform:scale(1); opacity:1}
      50%{transform:scale(1.45); opacity:.7}
    }
    h1{
      margin:18px 0 14px;
      font-size:clamp(40px, 7vw, 84px);
      line-height:.92;
      letter-spacing:-.04em;
    }
    .gradient-text{
      background:linear-gradient(135deg, #ffffff 15%, #b2f2ff 45%, #d4c4ff 70%, #ffffff 100%);
      -webkit-background-clip:text; background-clip:text; color:transparent;
      filter:drop-shadow(0 0 25px rgba(159,123,255,.18));
    }
    .subtitle{
      max-width:650px;
      font-size:clamp(16px,2.1vw,21px); line-height:1.6;
      color:var(--muted); margin-bottom:24px;
    }

    .cta-group{display:flex; gap:12px; flex-wrap:wrap}
    .mini-stats{
      display:grid; grid-template-columns:repeat(3,1fr); gap:12px;
      margin-top:26px;
    }
    .stat{
      padding:16px; border-radius:20px; background:rgba(255,255,255,.05);
      border:1px solid rgba(255,255,255,.09);
    }
    .stat strong{display:block; font-size:18px; margin-bottom:6px}
    .stat span{font-size:13px; color:var(--muted)}

    .hero-visual{
      min-height:560px;
      padding:26px;
      display:flex; align-items:center; justify-content:center;
      position:relative;
      background:
        linear-gradient(180deg, rgba(255,255,255,.10), rgba(255,255,255,.04)),
        radial-gradient(circle at 70% 18%, rgba(255,255,255,.16), transparent 22%),
        linear-gradient(180deg, rgba(64,82,155,.22), rgba(12,12,22,.2));
    }
    .scene{
      position:relative; width:100%; height:100%;
      min-height:500px;
      border-radius:28px;
      overflow:hidden;
      background:
        radial-gradient(circle at 50% 20%, rgba(255,214,170,.20), transparent 20%),
        linear-gradient(180deg, #415d98 0%, #231932 42%, #080910 100%);
      border:1px solid rgba(255,255,255,.10);
    }

    .sun{
      position:absolute; width:160px; height:160px; border-radius:50%;
      left:50%; top:70px; transform:translateX(-50%);
      background:radial-gradient(circle, rgba(255,235,214,.95), rgba(255,208,160,.65) 45%, rgba(255,208,160,0) 72%);
      filter:blur(2px);
      box-shadow:0 0 80px rgba(255,210,170,.25);
    }
    .clock{
      position:absolute; inset:auto 50% 110px auto; transform:translateX(50%);
      width:280px; height:280px; border-radius:50%;
      border:1px solid rgba(255,255,255,.16);
      box-shadow:0 0 0 18px rgba(255,255,255,.03), inset 0 0 0 1px rgba(255,255,255,.06);
      backdrop-filter:blur(4px);
    }
    .clock::before{
      content:""; position:absolute; inset:18px; border-radius:50%;
      border:1px dashed rgba(255,255,255,.12);
      animation:slowSpin 20s linear infinite;
    }
    .clock::after{
      content:""; position:absolute; left:50%; top:50%; width:10px; height:10px;
      border-radius:50%; background:#fff; transform:translate(-50%,-50%);
      box-shadow:0 0 18px rgba(255,255,255,.8);
    }
    .hand{
      position:absolute; left:50%; top:50%;
      transform-origin:bottom center;
      background:linear-gradient(180deg, #ffffff, rgba(255,255,255,.3));
      border-radius:999px;
      opacity:.9;
    }
    .hand.hour{width:4px; height:68px; transform:translate(-50%,-100%) rotate(90deg)}
    .hand.minute{width:3px; height:100px; transform:translate(-50%,-100%) rotate(90deg)}
    .frozen-label{
      position:absolute; left:50%; bottom:48px; transform:translateX(-50%);
      padding:10px 16px; border-radius:999px;
      background:rgba(5,8,18,.55); border:1px solid rgba(255,255,255,.10);
      color:#ecf5ff; font-size:12px; letter-spacing:.14em; text-transform:uppercase;
      backdrop-filter:blur(10px);
    }
    .city{
      position:absolute; left:0; right:0; bottom:0; height:42%;
      background:
        linear-gradient(to top, rgba(8,9,15,1), rgba(8,9,15,.05)),
        linear-gradient(90deg,
          transparent 0 4%, rgba(255,255,255,.06) 4% 6%, transparent 6% 10%,
          rgba(255,255,255,.05) 10% 12%, transparent 12% 18%,
          rgba(255,255,255,.05) 18% 24%, transparent 24% 28%,
          rgba(255,255,255,.05) 28% 31%, transparent 31% 38%,
          rgba(255,255,255,.04) 38% 45%, transparent 45% 50%,
          rgba(255,255,255,.05) 50% 55%, transparent 55% 60%,
          rgba(255,255,255,.06) 60% 67%, transparent 67% 73%,
          rgba(255,255,255,.05) 73% 78%, transparent 78% 84%,
          rgba(255,255,255,.04) 84% 92%, transparent 92% 100%);
      clip-path:polygon(0 100%,0 28%,7% 20%,11% 30%,17% 15%,21% 22%,28% 8%,32% 34%,38% 24%,45% 12%,51% 18%,58% 8%,63% 22%,69% 14%,74% 30%,82% 10%,88% 20%,95% 14%,100% 28%,100% 100%);
    }

    .falling-runes span{
      position:absolute; top:-10%; color:rgba(255,255,255,.22);
      font-size:14px; animation:runeFall linear infinite;
    }
    @keyframes runeFall{
      from{transform:translateY(-10vh); opacity:0}
      10%{opacity:.25}
      to{transform:translateY(115vh); opacity:0}
    }

    section{padding:40px 0}
    .section-head{margin-bottom:18px}
    .kicker{
      color:#d6e5ff; text-transform:uppercase; letter-spacing:.14em; font-size:12px; font-weight:800;
    }
    h2{margin:8px 0 10px; font-size:clamp(28px,4vw,44px)}
    .section-copy{color:var(--muted); max-width:720px; line-height:1.7}

    .cards{
      display:grid; gap:16px; grid-template-columns:repeat(3,1fr);
    }
    .card{
      padding:22px; border-radius:24px; background:var(--glass);
      border:1px solid rgba(255,255,255,.11);
      backdrop-filter:blur(14px);
      box-shadow:var(--shadow);
      position:relative; overflow:hidden;
    }
    .card::after{
      content:""; position:absolute; inset:auto -30% -45% auto;
      width:180px; height:180px; border-radius:50%;
      background:radial-gradient(circle, rgba(159,123,255,.16), transparent 65%);
      pointer-events:none;
    }
    .icon{
      width:50px; height:50px; border-radius:16px;
      display:grid; place-items:center;
      background:linear-gradient(135deg, rgba(159,123,255,.22), rgba(99,215,255,.18));
      border:1px solid rgba(255,255,255,.10);
      margin-bottom:14px; font-size:20px;
    }
    .card h3{margin:0 0 10px; font-size:20px}
    .card p{margin:0; color:var(--muted); line-height:1.7}

    .download{
      display:grid; gap:18px; grid-template-columns:1.1fr .9fr; align-items:stretch;
    }
    .download-box{padding:26px}
    .download-grid{
      display:grid; grid-template-columns:repeat(2,1fr); gap:14px; margin-top:18px;
    }
    .download-item{
      display:flex; flex-direction:column; gap:10px;
      padding:18px; border-radius:20px; background:rgba(255,255,255,.05);
      border:1px solid rgba(255,255,255,.09);
    }
    .download-item strong{font-size:18px}
    .download-item span{font-size:14px; color:var(--muted)}
    .tag{
      display:inline-flex; width:max-content;
      padding:7px 10px; border-radius:999px;
      background:rgba(255,255,255,.07); color:#e9f2ff;
      border:1px solid rgba(255,255,255,.10); font-size:12px; font-weight:700;
      letter-spacing:.08em; text-transform:uppercase;
    }

    .lang-note{
      padding:24px; display:flex; flex-direction:column; justify-content:center;
    }
    .lang-list{
      display:grid; gap:12px; margin-top:14px;
    }
    .lang-row{
      display:flex; align-items:center; justify-content:space-between;
      padding:14px 16px; border-radius:18px; background:rgba(255,255,255,.05);
      border:1px solid rgba(255,255,255,.09);
    }
    .lang-row strong{display:flex; align-items:center; gap:10px}
    .lang-row span{color:var(--muted); font-size:14px}

    footer{
      padding:24px 0 46px; color:var(--muted);
    }
    .footer-box{
      display:flex; align-items:center; justify-content:space-between; gap:16px; flex-wrap:wrap;
      padding:18px 22px; border-radius:22px;
      background:rgba(255,255,255,.05); border:1px solid rgba(255,255,255,.09);
      backdrop-filter:blur(12px);
    }

    [data-reveal]{opacity:0; transform:translateY(24px); transition:opacity .7s ease, transform .7s ease}
    [data-reveal].visible{opacity:1; transform:none}

    .help{
      color:var(--muted); font-size:14px; line-height:1.7; margin-top:10px;
    }

    @media (max-width: 980px){
      .hero-grid, .download, .cards{grid-template-columns:1fr}
      .hero{min-height:auto}
      .hero-visual{min-height:420px}
      .mini-stats{grid-template-columns:1fr}
    }
    @media (max-width: 680px){
      .nav{align-items:flex-start}
      .nav-actions{width:100%; justify-content:flex-start}
      .hero-copy{padding:26px}
      .download-grid{grid-template-columns:1fr}
      h1{line-height:1}
    }
  </style>
</head>
<body>
  <div class="noise"></div>
  <div class="grid"></div>
  <div class="aurora"></div>
  <div class="particles" aria-hidden="true"></div>

  <div class="wrap">
    <header>
      <div class="container nav">
        <div class="brand">
          <div class="logo"></div>
          <div>
            <div class="brand-title" data-i18n="brandTop">visual novel website</div>
            <div class="brand-name">The Limit of Looped Eternity</div>
          </div>
        </div>

        <div class="nav-actions">
          <div class="lang-switch" aria-label="Language selector">
            <button class="lang-btn active" data-lang="ru">RU</button>
            <button class="lang-btn" data-lang="en">EN</button>
            <button class="lang-btn" data-lang="pl">PL</button>
          </div>
          <a href="#download" class="ghost-btn" data-i18n="navDownload">Скачать</a>
        </div>
      </div>
    </header>

    <main>
      <section class="hero">
        <div class="container hero-grid">
          <div class="panel hero-copy" data-reveal>
            <div class="eyebrow">
              <span class="eyebrow-dot"></span>
              <span data-i18n="eyebrow">Мистическая визуальная новелла</span>
            </div>

            <h1 class="gradient-text" data-i18n="title">
              The Limit of<br>Looped Eternity
            </h1>

            <p class="subtitle" data-i18n="subtitle">
              Город застрял в одном часе. Солнце не движется. Часы не идут.
              Но чем дольше ты остаёшься, тем сильнее забываешь, зачем пришёл.
            </p>

            <div class="cta-group">
              <a href="#download" class="primary-btn" data-i18n="ctaDownload">Скачать игру</a>
              <a href="#about" class="secondary-btn" data-i18n="ctaStory">О сюжете</a>
            </div>

            <div class="mini-stats">
              <div class="stat">
                <strong data-i18n="stat1Value">3 языка</strong>
                <span data-i18n="stat1Label">Русский, English, Polski</span>
              </div>
              <div class="stat">
                <strong data-i18n="stat2Value">Атмосфера</strong>
                <span data-i18n="stat2Label">Застывшее время и тайны</span>
              </div>
              <div class="stat">
                <strong data-i18n="stat3Value">Ren'Py</strong>
                <span data-i18n="stat3Label">Идеально для страницы новеллы</span>
              </div>
            </div>
          </div>

          <div class="panel hero-visual" data-reveal>
            <div class="scene">
              <div class="sun"></div>
              <div class="clock">
                <div class="hand hour"></div>
                <div class="hand minute"></div>
              </div>
              <div class="frozen-label" data-i18n="frozen">time: frozen</div>
              <div class="city"></div>
              <div class="falling-runes" aria-hidden="true"></div>
            </div>
          </div>
        </div>
      </section>

      <section id="about">
        <div class="container">
          <div class="section-head" data-reveal>
            <div class="kicker" data-i18n="aboutKicker">о проекте</div>
            <h2 data-i18n="aboutTitle">Дизайн под твою историю</h2>
            <p class="section-copy" data-i18n="aboutText">
              Эта страница сделана как атмосферный лендинг для визуальной новеллы:
              неоновые блики, стеклянные панели, медленные анимации, селектор языка
              и блоки скачивания, чтобы сайт выглядел как реальная страница релиза.
            </p>
          </div>

          <div class="cards">
            <article class="card" data-reveal>
              <div class="icon">⏳</div>
              <h3 data-i18n="card1Title">Застывшее время</h3>
              <p data-i18n="card1Text">
                Центральная круговая композиция с часами и закатом подчёркивает идею
                города, который застрял в одном моменте.
              </p>
            </article>

            <article class="card" data-reveal>
              <div class="icon">✨</div>
              <h3 data-i18n="card2Title">Плавные анимации</h3>
              <p data-i18n="card2Text">
                Частицы, свечение, мягкий параллакс и появление блоков при прокрутке
                делают страницу более живой и современно выглядящей.
              </p>
            </article>

            <article class="card" data-reveal>
              <div class="icon">🌍</div>
              <h3 data-i18n="card3Title">Выбор языка</h3>
              <p data-i18n="card3Text">
                Вверху есть переключатель RU / EN / PL. Текст страницы меняется без
                перезагрузки, что удобно для игроков из разных стран.
              </p>
            </article>
          </div>
        </div>
      </section>

      <section id="download">
        <div class="container download">
          <div class="panel download-box" data-reveal>
            <div class="kicker" data-i18n="downloadKicker">скачивание</div>
            <h2 data-i18n="downloadTitle">Скачать новеллу</h2>
            <p class="section-copy" data-i18n="downloadText">
              Ниже — готовые карточки под разные платформы. Просто замени ссылки
              внутри кнопок на свои реальные файлы или страницы загрузки.
            </p>

            <div class="download-grid">
              <div class="download-item">
                <span class="tag">Windows</span>
                <strong data-i18n="winTitle">Версия для Windows</strong>
                <span data-i18n="winDesc">Основная сборка для ПК.</span>
                <a class="primary-btn" href="#" data-i18n="downloadNow">Скачать</a>
              </div>

              <div class="download-item">
                <span class="tag">Android</span>
                <strong data-i18n="androidTitle">Версия для Android</strong>
                <span data-i18n="androidDesc">Удобно для мобильного прохождения.</span>
                <a class="secondary-btn" href="#" data-i18n="downloadNow">Скачать</a>
              </div>

              <div class="download-item">
                <span class="tag">Trailer</span>
                <strong data-i18n="trailerTitle">Трейлер / тизер</strong>
                <span data-i18n="trailerDesc">Можно поставить ссылку на YouTube.</span>
                <a class="secondary-btn" href="#" data-i18n="watchTrailer">Смотреть</a>
              </div>

              <div class="download-item">
                <span class="tag">Patch</span>
                <strong data-i18n="patchTitle">Патч / обновления</strong>
                <span data-i18n="patchDesc">Отдельная секция под фиксы и новые версии.</span>
                <a class="secondary-btn" href="#" data-i18n="openUpdates">Открыть</a>
              </div>
            </div>

            <p class="help" data-i18n="helpText">
              Подсказка: если хочешь, сюда легко добавить ещё скриншоты, описание
              персонажей, системные требования и changelog.
            </p>
          </div>

          <div class="panel lang-note" data-reveal>
            <div class="kicker" data-i18n="langKicker">локализация</div>
            <h2 data-i18n="langTitle">Поддержка трёх языков</h2>
            <p class="section-copy" data-i18n="langText">
              Сайт уже поддерживает русский, английский и польский. Это удобно,
              если ты хочешь выкладывать новеллу не только для своей аудитории.
            </p>

            <div class="lang-list">
              <div class="lang-row">
                <strong>🇷🇺 <span data-i18n="langRu">Русский</span></strong>
                <span data-i18n="langRuStatus">Готово</span>
              </div>
              <div class="lang-row">
                <strong>🇬🇧 <span data-i18n="langEn">English</span></strong>
                <span data-i18n="langEnStatus">Ready</span>
              </div>
              <div class="lang-row">
                <strong>🇵🇱 <span data-i18n="langPl">Polski</span></strong>
                <span data-i18n="langPlStatus">Gotowe</span>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer>
      <div class="container">
        <div class="footer-box">
          <div>
            <strong>The Limit of Looped Eternity</strong><br>
            <span data-i18n="footerText">Лендинг для скачивания визуальной новеллы.</span>
          </div>
          <a href="#top" class="ghost-btn" onclick="window.scrollTo({top:0,behavior:'smooth'}); return false;" data-i18n="backTop">Наверх</a>
        </div>
      </div>
    </footer>
  </div>

  <script>
    const i18n = {
      ru: {
        brandTop:"visual novel website",
        navDownload:"Скачать",
        eyebrow:"Мистическая визуальная новелла",
        title:"The Limit of<br>Looped Eternity",
        subtitle:"Город застрял в одном часе. Солнце не движется. Часы не идут. Но чем дольше ты остаёшься, тем сильнее забываешь, зачем пришёл.",
        ctaDownload:"Скачать игру",
        ctaStory:"О сюжете",
        stat1Value:"3 языка",
        stat1Label:"Русский, English, Polski",
        stat2Value:"Атмосфера",
        stat2Label:"Застывшее время и тайны",
        stat3Value:"Ren'Py",
        stat3Label:"Идеально для страницы новеллы",
        frozen:"time: frozen",
        aboutKicker:"о проекте",
        aboutTitle:"Дизайн под твою историю",
        aboutText:"Эта страница сделана как атмосферный лендинг для визуальной новеллы: неоновые блики, стеклянные панели, медленные анимации, селектор языка и блоки скачивания, чтобы сайт выглядел как реальная страница релиза.",
        card1Title:"Застывшее время",
        card1Text:"Центральная круговая композиция с часами и закатом подчёркивает идею города, который застрял в одном моменте.",
        card2Title:"Плавные анимации",
        card2Text:"Частицы, свечение, мягкий параллакс и появление блоков при прокрутке делают страницу более живой и современно выглядящей.",
        card3Title:"Выбор языка",
        card3Text:"Вверху есть переключатель RU / EN / PL. Текст страницы меняется без перезагрузки, что удобно для игроков из разных стран.",
        downloadKicker:"скачивание",
        downloadTitle:"Скачать новеллу",
        downloadText:"Ниже — готовые карточки под разные платформы. Просто замени ссылки внутри кнопок на свои реальные файлы или страницы загрузки.",
        winTitle:"Версия для Windows",
        winDesc:"Основная сборка для ПК.",
        androidTitle:"Версия для Android",
        androidDesc:"Удобно для мобильного прохождения.",
        trailerTitle:"Трейлер / тизер",
        trailerDesc:"Можно поставить ссылку на YouTube.",
        patchTitle:"Патч / обновления",
        patchDesc:"Отдельная секция под фиксы и новые версии.",
        downloadNow:"Скачать",
        watchTrailer:"Смотреть",
        openUpdates:"Открыть",
        helpText:"Подсказка: если хочешь, сюда легко добавить ещё скриншоты, описание персонажей, системные требования и changelog.",
        langKicker:"локализация",
        langTitle:"Поддержка трёх языков",
        langText:"Сайт уже поддерживает русский, английский и польский. Это удобно, если ты хочешь выкладывать новеллу не только для своей аудитории.",
        langRu:"Русский",
        langRuStatus:"Готово",
        langEn:"English",
        langEnStatus:"Ready",
        langPl:"Polski",
        langPlStatus:"Gotowe",
        footerText:"Лендинг для скачивания визуальной новеллы.",
        backTop:"Наверх"
      },
      en: {
        brandTop:"visual novel website",
        navDownload:"Download",
        eyebrow:"Mystery visual novel",
        title:"The Limit of<br>Looped Eternity",
        subtitle:"A city is trapped in a single hour. The sun does not move. The clocks do not tick. And the longer you stay, the more you forget why you came.",
        ctaDownload:"Download game",
        ctaStory:"About story",
        stat1Value:"3 languages",
        stat1Label:"Russian, English, Polish",
        stat2Value:"Atmosphere",
        stat2Label:"Frozen time and secrets",
        stat3Value:"Ren'Py",
        stat3Label:"Perfect for a VN landing page",
        frozen:"time: frozen",
        aboutKicker:"about project",
        aboutTitle:"A design built for your story",
        aboutText:"This page is made as an atmospheric landing page for a visual novel: neon glows, glassmorphism panels, slow ambient animation, a language selector, and download blocks so it feels like a real release page.",
        card1Title:"Frozen time",
        card1Text:"The circular composition with the clock and sunset highlights the idea of a city trapped in a single moment.",
        card2Title:"Smooth animation",
        card2Text:"Particles, glowing elements, soft parallax, and reveal-on-scroll make the page feel alive and more modern.",
        card3Title:"Language switch",
        card3Text:"There is a RU / EN / PL switch at the top. The page text changes instantly without reloading, which is great for players from different countries.",
        downloadKicker:"download",
        downloadTitle:"Download the novel",
        downloadText:"Below are ready-made platform cards. Just replace the button links with your real files or release pages.",
        winTitle:"Windows version",
        winDesc:"Main desktop build.",
        androidTitle:"Android version",
        androidDesc:"Comfortable for mobile playthrough.",
        trailerTitle:"Trailer / teaser",
        trailerDesc:"You can place a YouTube link here.",
        patchTitle:"Patch / updates",
        patchDesc:"A separate block for fixes and new versions.",
        downloadNow:"Download",
        watchTrailer:"Watch",
        openUpdates:"Open",
        helpText:"Tip: you can easily add screenshots, character descriptions, system requirements, and a changelog here.",
        langKicker:"localization",
        langTitle:"Support for three languages",
        langText:"The site already supports Russian, English, and Polish. That is useful if you want to release the novel beyond your main audience.",
        langRu:"Russian",
        langRuStatus:"Ready",
        langEn:"English",
        langEnStatus:"Ready",
        langPl:"Polish",
        langPlStatus:"Ready",
        footerText:"Landing page for downloading a visual novel.",
        backTop:"Back to top"
      },
      pl: {
        brandTop:"visual novel website",
        navDownload:"Pobierz",
        eyebrow:"Tajemnicza visual novel",
        title:"The Limit of<br>Looped Eternity",
        subtitle:"Miasto utknęło w jednej godzinie. Słońce się nie porusza. Zegary nie tykają. A im dłużej zostajesz, tym bardziej zapominasz, po co tu przyszedłeś.",
        ctaDownload:"Pobierz grę",
        ctaStory:"O historii",
        stat1Value:"3 języki",
        stat1Label:"Rosyjski, English, Polski",
        stat2Value:"Klimat",
        stat2Label:"Zatrzymany czas i tajemnice",
        stat3Value:"Ren'Py",
        stat3Label:"Idealne dla strony visual novel",
        frozen:"time: frozen",
        aboutKicker:"o projekcie",
        aboutTitle:"Projekt dopasowany do twojej historii",
        aboutText:"Ta strona została przygotowana jako klimatyczny landing page dla visual novel: neonowe poświaty, szklane panele, powolne animacje, wybór języka i bloki pobierania, żeby wyglądała jak prawdziwa strona premiery.",
        card1Title:"Zatrzymany czas",
        card1Text:"Centralna kompozycja z zegarem i zachodem słońca podkreśla ideę miasta uwięzionego w jednej chwili.",
        card2Title:"Płynne animacje",
        card2Text:"Cząsteczki, poświata, delikatny paralaks i pojawianie się sekcji przy przewijaniu sprawiają, że strona wygląda nowocześnie i żywo.",
        card3Title:"Wybór języka",
        card3Text:"Na górze znajduje się przełącznik RU / EN / PL. Tekst zmienia się bez przeładowania, co jest wygodne dla graczy z różnych krajów.",
        downloadKicker:"pobieranie",
        downloadTitle:"Pobierz nowelę",
        downloadText:"Poniżej są gotowe karty dla różnych platform. Wystarczy podmienić linki w przyciskach na prawdziwe pliki albo strony pobierania.",
        winTitle:"Wersja na Windows",
        winDesc:"Główna wersja na komputer.",
        androidTitle:"Wersja na Android",
        androidDesc:"Wygodna do grania na telefonie.",
        trailerTitle:"Trailer / teaser",
        trailerDesc:"Możesz tu dodać link do YouTube.",
        patchTitle:"Patch / aktualizacje",
        patchDesc:"Osobna sekcja na poprawki i nowe wersje.",
        downloadNow:"Pobierz",
        watchTrailer:"Oglądaj",
        openUpdates:"Otwórz",
        helpText:"Wskazówka: łatwo możesz tu dodać screeny, opisy postaci, wymagania systemowe i changelog.",
        langKicker:"lokalizacja",
        langTitle:"Obsługa trzech języków",
        langText:"Strona już obsługuje rosyjski, angielski i polski. To wygodne, jeśli chcesz udostępnić nowelę także poza swoją główną publicznością.",
        langRu:"Rosyjski",
        langRuStatus:"Gotowe",
        langEn:"English",
        langEnStatus:"Gotowe",
        langPl:"Polski",
        langPlStatus:"Gotowe",
        footerText:"Landing page do pobierania visual novel.",
        backTop:"Do góry"
      }
    };

    const setLanguage = (lang) => {
      document.documentElement.lang = lang;
      document.querySelectorAll('[data-i18n]').forEach(el => {
        const key = el.dataset.i18n;
        if (i18n[lang] && i18n[lang][key] !== undefined) {
          el.innerHTML = i18n[lang][key];
        }
      });
      document.querySelectorAll('.lang-btn').forEach(btn => {
        btn.classList.toggle('active', btn.dataset.lang === lang);
      });
      localStorage.setItem('tloe_lang', lang);
    };

    document.querySelectorAll('.lang-btn').forEach(btn => {
      btn.addEventListener('click', () => setLanguage(btn.dataset.lang));
    });

    setLanguage(localStorage.getItem('tloe_lang') || 'ru');

    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) entry.target.classList.add('visible');
      });
    }, { threshold: .14 });
    document.querySelectorAll('[data-reveal]').forEach(el => observer.observe(el));

    const particles = document.querySelector('.particles');
    for(let i = 0; i < 28; i++){
      const p = document.createElement('span');
      const size = 2 + Math.random() * 4;
      p.style.left = Math.random() * 100 + 'vw';
      p.style.bottom = (-10 - Math.random() * 100) + 'vh';
      p.style.width = size + 'px';
      p.style.height = size + 'px';
      p.style.animationDuration = (12 + Math.random() * 18) + 's';
      p.style.animationDelay = (-Math.random() * 25) + 's';
      particles.appendChild(p);
    }

    const runes = document.querySelector('.falling-runes');
    const chars = ['∞',':','·','✦','⟡','°','○','1','0'];
    for(let i = 0; i < 24; i++){
      const r = document.createElement('span');
      r.textContent = chars[Math.floor(Math.random() * chars.length)];
      r.style.left = (Math.random() * 100) + '%';
      r.style.animationDuration = (8 + Math.random() * 12) + 's';
      r.style.animationDelay = (-Math.random() * 10) + 's';
      r.style.fontSize = (12 + Math.random() * 14) + 'px';
      runes.appendChild(r);
    }

    window.addEventListener('mousemove', (e) => {
      const x = (e.clientX / window.innerWidth - .5) * 8;
      const y = (e.clientY / window.innerHeight - .5) * 8;
      document.querySelector('.scene').style.transform = `translate(${x * .4}px, ${y * .35}px)`;
      document.querySelector('.hero-copy').style.transform = `translate(${x * -.18}px, ${y * -.18}px)`;
    });

    window.addEventListener('mouseleave', () => {
      document.querySelector('.scene').style.transform = '';
      document.querySelector('.hero-copy').style.transform = '';
    });
  </script>
</body>
</html>
