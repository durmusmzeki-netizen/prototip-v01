
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#0b0b0b">
<meta name="description" content="Osmanlı Devleti'nin tarihi, padişahları, savaşları ve fetihleri.">
<title>PROTOTİP V.01 | Osmanlı Tarihi</title>
<style>
:root {
  --gold: #d6b15e;
  --bg: #0b0b0b;
  --panel: #171717;
  --text: #f5f0e5;
  --muted: #c0b8a7;
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  margin: 0;
  background: var(--bg);
  color: var(--text);
  font-family: Georgia, "Times New Roman", serif;
  line-height: 1.7;
}
header {
  position: sticky;
  top: 0;
  z-index: 10;
  background: rgba(11,11,11,.96);
  border-bottom: 1px solid #55431f;
  padding: 12px 16px;
}
.brand {
  text-align: center;
  color: var(--gold);
  font-size: 21px;
  font-weight: bold;
  letter-spacing: 2px;
}
.brand small {
  display: block;
  color: var(--muted);
  font-size: 11px;
  letter-spacing: 3px;
}
nav {
  display: flex;
  justify-content: center;
  gap: 9px;
  flex-wrap: wrap;
  margin-top: 10px;
}
nav a {
  color: var(--text);
  text-decoration: none;
  font-family: Arial, sans-serif;
  font-size: 12px;
  padding: 6px 9px;
  border: 1px solid #4d4025;
  border-radius: 5px;
}
nav a:hover, .btn:hover {
  background: var(--gold);
  color: #111;
}
.hero {
  text-align: center;
  padding: 75px 20px 65px;
  background:
    radial-gradient(ellipse at top, #463719 0%, #1a160e 32%, #0b0b0b 72%);
  border-bottom: 1px solid #4d4025;
}
.eyebrow {
  color: var(--gold);
  letter-spacing: 4px;
  font: 12px Arial, sans-serif;
}
h1 {
  font-size: clamp(34px, 8vw, 58px);
  line-height: 1.15;
  color: var(--gold);
  margin: 18px 0;
}
.hero p {
  max-width: 620px;
  margin: 0 auto 25px;
  color: var(--muted);
}
.btn {
  display: inline-block;
  color: #111;
  background: var(--gold);
  padding: 10px 18px;
  text-decoration: none;
  border-radius: 5px;
  font-family: Arial, sans-serif;
  font-weight: bold;
}
main { max-width: 1000px; margin: auto; padding: 20px; }
section { padding: 38px 0; scroll-margin-top: 120px; }
.section-title {
  color: var(--gold);
  font-size: 29px;
  margin: 0 0 8px;
}
.intro { color: var(--muted); margin-top: 0; }
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(min(100%, 230px), 1fr));
  gap: 16px;
}
.card {
  background: var(--panel);
  border: 1px solid #44381f;
  border-radius: 9px;
  padding: 19px;
}
.card h3 { color: var(--gold); margin-top: 0; }
.date { color: var(--gold); font-size: 13px; }
.card p { color: var(--muted); }
details {
  border-top: 1px solid #44381f;
  padding: 10px 0;
}
summary { color: var(--gold); cursor: pointer; }
.timeline {
  border-left: 2px solid var(--gold);
  padding-left: 20px;
}
.timeline article { margin: 22px 0; }
footer {
  text-align: center;
  padding: 25px 16px;
  border-top: 1px solid #55431f;
  color: var(--muted);
  font: 12px Arial, sans-serif;
}
@media (max-width: 400px) {
  .brand { font-size: 18px; }
  nav { gap: 5px; }
  nav a { font-size: 11px; padding: 6px; }
  main { padding: 15px; }
}
</style>
</head>
<body>

<header>
  <div class="brand">
    PROTOTİP V.01
    <small>OSMANLI TARİHİ</small>
  </div>
  <nav aria-label="Ana menü">
    <a href="#anasayfa">Ana Sayfa</a>
    <a href="#kurulus">Kuruluş</a>
    <a href="#padisahlar">Padişahlar</a>
    <a href="#fetihler">Savaşlar ve Fetihler</a>
  </nav>
</header>

<div class="hero" id="anasayfa">
  <div class="eyebrow">1299 — 1922</div>
  <h1>Bir Cihan<br>Devletinin Hikâyesi</h1>
  <p>
    Osmanlı Devleti'nin kuruluşundan yükselişine,
    padişahlarından tarihe yön veren fetihlerine
    uzanan bir tarih yolculuğu.
  </p>
  <a class="btn" href="#kurulus">Tarih Yolculuğuna Başla</a>
</div>

<main>
<section id="kurulus">
  <h2 class="section-title">Osmanlı Devleti'nin Kuruluşu</h2>
  <p class="intro">
    Küçük bir uç beyliğinden geniş topraklara yayılan
    bir devlete uzanan tarih.
  </p>
  <div class="card">
    <span class="date">13. yüzyılın sonları</span>
    <h3>Osman Bey ve ilk yıllar</h3>
    <p>
      Osmanlı Beyliği, Osman Bey'in liderliğinde
      Anadolu'nun kuzeybatısında ortaya çıktı. Bölgedeki
      siyasi gelişmeler, Bizans sınırındaki konumu ve
      zaman içinde kurulan siyasi ilişkiler, beyliğin
      büyümesinde etkili oldu.
    </p>
    <details>
      <summary>Daha fazla bilgi oku</summary>
      <p>
        Osman Bey'in ardından Orhan Bey döneminde
        devletin teşkilatlanması güçlendi. Bursa'nın
        1326'da alınması, Osmanlı tarihindeki önemli
        dönüm noktalarından biri oldu.
      </p>
    </details>
  </div>
</section>

<section id="padisahlar">
  <h2 class="section-title">Padişahlar ve Hayatları</h2>
  <p class="intro">Osmanlı tarihine yön veren hükümdarları tanı.</p>
  <div class="grid">
    <article class="card">
      <span class="date">Osmanlı'nın kurucusu</span>
      <h3>Osman Bey</h3>
      <p>Osmanlı Beyliği'nin kurucusu kabul edilir. Beyliğin
      siyasi temelini attı ve çevresindeki topraklarda etkisini artırdı.</p>
    </article>
    <article class="card">
      <span class="date">1299–1922 geleneğinin erken dönemi</span>
      <h3>Orhan Bey</h3>
      <p>Bursa'nın alınması ve ilk Osmanlı kurumlarının
      gelişmesi onun döneminin önemli olayları arasındadır.</p>
    </article>
    <article class="card">
      <span class="date">1444–1446, 1451–1481</span>
      <h3>Fatih Sultan Mehmet</h3>
      <p>1453'te İstanbul'u fethetti. Bu olay, dünya tarihinin
      önemli dönüm noktalarından biri olarak kabul edilir.</p>
    </article>
    <article class="card">
      <span class="date">1520–1566</span>
      <h3>Kanuni Sultan Süleyman</h3>
      <p>Osmanlı Devleti'nin siyasi ve askerî gücünün
      zirveye ulaştığı dönemin hükümdarlarından biridir.
      Kanunlar ve sanat alanındaki gelişmelerle de anılır.</p>
    </article>
  </div>
  <p class="intro">
    Not: Osmanlı padişahlarının hükümdarlık tarihleri
    ve olaylar hakkında daha ayrıntılı bilgiler sonraki
    sürümlerde genişletilebilir.
  </p>
</section>

<section id="fetihler">
  <h2 class="section-title">Savaşlar ve Fetihler</h2>
  <p class="intro">Tarihte iz bırakan bazı önemli olaylar.</p>
  <div class="grid">
    <article class="card">
      <span class="date">1326</span>
      <h3>Bursa'nın alınması</h3>
      <p>Bursa, Osmanlı Devleti'nin önemli merkezlerinden
      biri hâline geldi ve erken dönem devletleşmesinde
      büyük rol oynadı.</p>
    </article>
    <article class="card">
      <span class="date">1453</span>
      <h3>İstanbul'un Fethi</h3>
      <p>Fatih Sultan Mehmet'in ordusu İstanbul'u aldı.
      Şehir, Osmanlı Devleti'nin başkenti oldu.</p>
    </article>
    <article class="card">
      <span class="date">1514</span>
      <h3>Çaldıran Savaşı</h3>
      <p>Yavuz Sultan Selim döneminde Osmanlı ve Safevi
      kuvvetleri arasında gerçekleşti. Doğu Anadolu'daki
      siyasi dengeleri etkiledi.</p>
    </article>
    <article class="card">
      <span class="date">1526</span>
      <h3>Mohaç Savaşı</h3>
      <p>Kanuni Sultan Süleyman döneminde Osmanlı ordusu
      Macar kuvvetlerini mağlup etti. Orta Avrupa'daki
      güç dengeleri üzerinde etkili oldu.</p>
    </article>
  </div>
</section>

<section id="zaman">
  <h2 class="section-title">Kısa Zaman Çizelgesi</h2>
  <div class="timeline">
    <article>
      <span class="date">1299 — geleneksel tarih</span>
      <div>Osmanlı Beyliği'nin kuruluşu</div>
    </article>
    <article>
      <span class="date">1453</span>
      <div>İstanbul'un fethi</div>
    </article>
    <article>
      <span class="date">1517</span>
      <div>Yavuz Sultan Selim döneminde Mısır'ın Osmanlı
      hâkimiyetine girmesi</div>
    </article>
    <article>
      <span class="date">1922</span>
      <div>Saltanatın kaldırılması</div>
    </article>
  </div>
</section>
</main>

<footer>
  <p>PROTOTİP V.01 · Osmanlı Tarihi</p>
  <p>Eğitim ve tarih meraklıları için hazırlanmış bağımsız bir projedir.</p>
</footer>

</body>
</html>
# prototip-v01
Osmanlı Tarihi - Prototip V.01
