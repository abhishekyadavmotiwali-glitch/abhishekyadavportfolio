
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TheHomeoVibe — Homeopathy Pharmacy | Dr. Vijay Reswal (BHMS)</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=Work+Sans:wght@400;500;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap');

:root{
  --ink-green:#1F3D2B;
  --ink-green-light:#2C5540;
  --amber:#C97C3D;
  --amber-dark:#A85F27;
  --parchment:#F6F1E4;
  --cream:#FBF8F1;
  --leaf:#7A9B6A;
  --charcoal:#2A2622;
  --line:rgba(42,38,34,0.12);
  --red:#B5432E;
  --whatsapp:#25D366;
}
*{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{background:var(--parchment);color:var(--charcoal);font-family:'Work Sans',sans-serif;line-height:1.55;-webkit-font-smoothing:antialiased;}
h1,h2,h3{font-family:'Fraunces',serif;font-weight:600;color:var(--ink-green);letter-spacing:-0.01em;}
a{text-decoration:none;color:inherit;}
img{max-width:100%;display:block;}
.wrap{max-width:1180px;margin:0 auto;padding:0 28px;}
.mono{font-family:'IBM Plex Mono',monospace;}

header{position:sticky;top:0;z-index:50;background:rgba(251,248,241,0.94);backdrop-filter:blur(8px);border-bottom:1px solid var(--line);}
.header-inner{display:flex;align-items:center;justify-content:space-between;padding:14px 28px;max-width:1180px;margin:0 auto;}
.logo{display:flex;align-items:center;gap:10px;}
.logo-mark{width:36px;height:36px;border-radius:50% 50% 50% 4px;background:var(--amber);position:relative;flex-shrink:0;}
.logo-mark::after{content:"";position:absolute;inset:8px;border-radius:50%;background:var(--cream);}
.logo-text{font-family:'Fraunces',serif;font-weight:700;font-size:1.3rem;color:var(--ink-green);line-height:1;}
.logo-text span{color:var(--amber-dark);}
.logo-sub{font-size:0.65rem;color:#736c61;letter-spacing:0.08em;text-transform:uppercase;font-weight:600;margin-top:2px;}
nav{display:flex;gap:28px;font-weight:500;font-size:0.9rem;}
nav a:hover{color:var(--amber-dark);}
.wa-header-btn{display:flex;align-items:center;gap:7px;background:var(--whatsapp);color:#fff;padding:9px 16px;border-radius:24px;font-size:0.85rem;font-weight:600;}
@media(max-width:900px){nav{display:none;}}

.hero{position:relative;overflow:hidden;padding:64px 0 50px;background:radial-gradient(ellipse at 78% 20%, rgba(122,155,106,0.18), transparent 55%),radial-gradient(ellipse at 15% 80%, rgba(201,124,61,0.14), transparent 50%);}
.hero-inner{display:grid;grid-template-columns:1.05fr 0.95fr;gap:46px;align-items:center;}
.eyebrow{font-family:'IBM Plex Mono',monospace;font-size:0.76rem;font-weight:600;letter-spacing:0.13em;text-transform:uppercase;color:var(--amber-dark);display:inline-flex;align-items:center;gap:8px;margin-bottom:14px;}
.eyebrow::before{content:"";width:22px;height:1px;background:var(--amber-dark);}
.hero h1{font-size:clamp(2rem,3.8vw,3rem);line-height:1.12;margin-bottom:16px;}
.hero h1 em{font-style:italic;color:var(--amber-dark);}
.hero p{font-size:1.02rem;color:#4a453f;max-width:480px;margin-bottom:24px;}
.hero-ctas{display:flex;gap:12px;flex-wrap:wrap;}
.btn-primary{background:var(--amber);color:var(--cream);padding:13px 24px;border-radius:30px;font-weight:600;font-size:0.9rem;border:none;cursor:pointer;box-shadow:0 8px 20px rgba(168,95,39,0.28);}
.btn-primary:hover{background:var(--amber-dark);}
.btn-whatsapp{display:inline-flex;align-items:center;gap:8px;background:var(--whatsapp);color:#fff;padding:13px 24px;border-radius:30px;font-weight:600;font-size:0.9rem;border:none;cursor:pointer;box-shadow:0 8px 20px rgba(37,211,102,0.3);}
.btn-whatsapp:hover{background:#1ebe57;}
.doc-card{background:var(--cream);border:1px solid var(--line);border-radius:16px;padding:18px 20px;display:flex;align-items:center;gap:14px;max-width:440px;}
.doc-avatar{width:56px;height:56px;border-radius:50%;background:linear-gradient(160deg,var(--leaf),var(--ink-green));flex-shrink:0;display:flex;align-items:center;justify-content:center;color:var(--cream);font-family:'Fraunces',serif;font-weight:700;font-size:1.3rem;}
.doc-name{font-weight:700;color:var(--ink-green);font-size:0.98rem;}
.doc-meta{font-size:0.78rem;color:#736c61;margin-top:2px;}
.doc-actions{display:flex;gap:8px;margin-top:10px;}
.mini-link{font-size:0.74rem;color:var(--ink-green);font-weight:600;display:flex;align-items:center;gap:4px;}
@media(max-width:900px){.hero-inner{grid-template-columns:1fr;}}

.trust-strip{background:var(--ink-green);color:var(--cream);padding:18px 0;}
.trust-inner{display:flex;justify-content:space-between;flex-wrap:wrap;gap:14px;font-size:0.82rem;font-weight:500;}
.trust-inner div{display:flex;align-items:center;gap:8px;}
.trust-inner div::before{content:"◆";color:var(--amber);font-size:0.65rem;}

section.block{padding:64px 0;}
.section-head{display:flex;justify-content:space-between;align-items:flex-end;margin-bottom:32px;flex-wrap:wrap;gap:16px;}
.section-head h2{font-size:clamp(1.5rem,2.2vw,2rem);}
.section-head p{color:#6b6459;max-width:440px;font-size:0.9rem;}

.cond-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;}
.cond-card{background:var(--cream);border:1px solid var(--line);border-radius:16px;overflow:hidden;cursor:pointer;transition:transform .2s;}
.cond-card:hover{transform:translateY(-4px);}
.cond-banner{height:80px;display:flex;align-items:center;justify-content:center;font-size:1.7rem;background:linear-gradient(135deg, rgba(181,67,46,0.14), rgba(122,155,106,0.16));}
.cond-body{padding:15px 17px;}
.cond-tag{font-size:0.68rem;color:var(--red);font-weight:700;text-transform:uppercase;letter-spacing:0.05em;}
.cond-body h3{font-size:1.02rem;margin:5px 0 6px;}
.cond-body p{font-size:0.8rem;color:#6b6459;}
@media(max-width:900px){.cond-grid{grid-template-columns:1fr 1fr;}}
@media(max-width:600px){.cond-grid{grid-template-columns:1fr;}}

.overlay{position:fixed;inset:0;background:rgba(31,25,20,0.55);z-index:200;display:none;align-items:flex-start;justify-content:center;padding:40px 16px;overflow-y:auto;}
.overlay.show{display:flex;}
.detail-sheet{background:var(--cream);border-radius:20px;max-width:840px;width:100%;padding:0;position:relative;box-shadow:0 40px 80px rgba(0,0,0,0.35);margin-bottom:40px;}
.detail-close{position:absolute;top:16px;right:16px;background:var(--ink-green);color:var(--cream);width:34px;height:34px;border-radius:50%;border:none;font-size:1.1rem;cursor:pointer;z-index:5;}
.detail-head{background:linear-gradient(135deg, var(--ink-green), var(--ink-green-light));color:var(--cream);padding:32px 32px 24px;border-radius:20px 20px 0 0;}
.detail-eyebrow{font-family:'IBM Plex Mono',monospace;font-size:0.7rem;letter-spacing:0.1em;text-transform:uppercase;color:var(--leaf);margin-bottom:8px;}
.detail-head h2{color:var(--cream);font-size:1.8rem;}
.detail-head .hindi{color:var(--amber);font-size:1rem;font-weight:500;margin-top:4px;}
.detail-body{padding:26px 32px 32px;}
.detail-intro{font-size:0.92rem;color:#4a453f;margin-bottom:20px;padding-bottom:20px;border-bottom:1px solid var(--line);}
.detail-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:20px;}
.info-box{background:var(--parchment);border:1px solid var(--line);border-radius:12px;padding:15px 17px;}
.info-box h4{font-size:0.83rem;color:var(--ink-green);margin-bottom:9px;display:flex;align-items:center;gap:6px;}
.info-box ul{list-style:none;font-size:0.8rem;color:#4a453f;}
.info-box li{padding:3px 0;padding-left:18px;position:relative;}
.info-box li::before{content:"✓";position:absolute;left:0;color:var(--leaf);font-weight:700;}
.remedy-strip{margin-top:6px;}
.remedy-strip h4{font-size:0.92rem;color:var(--ink-green);margin-bottom:11px;}
.remedy-row{display:grid;grid-template-columns:repeat(4,1fr);gap:9px;}
.remedy-chip{background:var(--parchment);border:1px solid var(--line);border-radius:10px;padding:11px 9px;text-align:center;}
.remedy-chip .mono{font-size:0.75rem;font-weight:700;color:var(--amber-dark);display:block;margin-bottom:4px;}
.remedy-chip span.desc{font-size:0.68rem;color:#736c59;}
.detail-note{font-size:0.74rem;color:#8a8378;margin-top:10px;font-style:italic;}
.doctor-alert{background:rgba(181,67,46,0.08);border:1px solid rgba(181,67,46,0.25);border-radius:12px;padding:13px 16px;margin-top:20px;font-size:0.8rem;color:var(--red);}
.consult-cta{display:flex;align-items:center;justify-content:space-between;background:var(--whatsapp);color:#fff;border-radius:14px;padding:15px 20px;margin-top:20px;flex-wrap:wrap;gap:12px;}
.consult-cta span{font-size:0.87rem;font-weight:600;}
.consult-cta button{background:#fff;color:var(--whatsapp);border:none;padding:10px 18px;border-radius:24px;font-weight:700;font-size:0.85rem;cursor:pointer;}
@media(max-width:640px){.detail-grid{grid-template-columns:1fr;}.remedy-row{grid-template-columns:repeat(2,1fr);}}

.why{background:var(--ink-green);color:var(--cream);}
.why .section-head h2,.why .section-head p{color:var(--cream);}
.why .section-head p{color:rgba(251,248,241,0.72);}
.why-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:20px;}
.why-card{background:rgba(251,248,241,0.06);border:1px solid rgba(251,248,241,0.14);border-radius:16px;padding:24px 18px;}
.why-num{font-family:'IBM Plex Mono',monospace;color:var(--amber);font-size:0.82rem;font-weight:600;margin-bottom:12px;}
.why-card h3{color:var(--cream);font-size:1rem;margin-bottom:8px;}
.why-card p{font-size:0.82rem;color:rgba(251,248,241,0.7);}
@media(max-width:900px){.why-grid{grid-template-columns:repeat(2,1fr);}}

/* Doctor / About */
.about-grid{display:grid;grid-template-columns:1fr 2fr;gap:30px;align-items:center;}
.about-photo{width:100%;aspect-ratio:1;border-radius:20px;background:linear-gradient(160deg,var(--leaf),var(--ink-green));display:flex;align-items:center;justify-content:center;color:var(--cream);font-family:'Fraunces',serif;font-size:3rem;font-weight:700;}
.about-text p{font-size:0.95rem;color:#4a453f;margin-bottom:14px;}
.about-badges{display:flex;gap:12px;flex-wrap:wrap;margin-top:16px;}
.about-badge{background:var(--cream);border:1px solid var(--line);border-radius:20px;padding:8px 16px;font-size:0.8rem;font-weight:600;color:var(--ink-green);}
@media(max-width:800px){.about-grid{grid-template-columns:1fr;}.about-photo{max-width:200px;margin:0 auto;}}

/* Contact section */
.contact-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;}
.contact-card{background:var(--cream);border:1px solid var(--line);border-radius:16px;padding:24px 20px;text-align:center;}
.contact-icon{width:48px;height:48px;border-radius:50%;background:rgba(122,155,106,0.18);display:flex;align-items:center;justify-content:center;font-size:1.4rem;margin:0 auto 14px;}
.contact-card h4{font-size:0.95rem;margin-bottom:6px;color:var(--ink-green);}
.contact-card p{font-size:0.85rem;color:#6b6459;}
.contact-card a.mono{color:var(--amber-dark);font-weight:700;font-size:0.9rem;}
@media(max-width:800px){.contact-grid{grid-template-columns:1fr;}}

footer{background:#17281c;color:rgba(251,248,241,0.75);padding:50px 0 24px;}
.foot-grid{display:grid;grid-template-columns:1.4fr 1fr 1fr 1.2fr;gap:32px;margin-bottom:36px;}
.foot-grid h4{color:var(--cream);font-family:'Fraunces',serif;font-size:1rem;margin-bottom:14px;}
.foot-grid p,.foot-grid li{font-size:0.84rem;line-height:1.9;}
.foot-grid ul{list-style:none;}
.foot-grid a:hover{color:var(--amber);}
.foot-bottom{border-top:1px solid rgba(251,248,241,0.12);padding-top:20px;display:flex;justify-content:space-between;font-size:0.78rem;color:rgba(251,248,241,0.5);flex-wrap:wrap;gap:10px;}
@media(max-width:820px){.foot-grid{grid-template-columns:1fr 1fr;}}

.wa-float{position:fixed;bottom:24px;right:24px;background:var(--whatsapp);color:#fff;width:58px;height:58px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:1.6rem;box-shadow:0 10px 30px rgba(37,211,102,0.45);z-index:150;transition:transform .2s;}
.wa-float:hover{transform:scale(1.08);}

a:focus-visible,button:focus-visible{outline:2px solid var(--amber-dark);outline-offset:3px;}
</style>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="logo">
      <div class="logo-mark"></div>
      <div>
        <div class="logo-text">The<span>Homeo</span>Vibe</div>
        <div class="logo-sub">Homeopathy Pharmacy</div>
      </div>
    </div>
    <nav>
      <a href="#library">बीमारियाँ व इलाज</a>
      <a href="#about">डॉक्टर के बारे में</a>
      <a href="#why">क्यों चुनें</a>
      <a href="#contact">संपर्क करें</a>
    </nav>
    <a class="wa-header-btn" href="https://wa.me/918764306828?text=Namaste%2C%20mujhe%20apni%20samasya%20ke%20baare%20mein%20consultation%20chahiye" target="_blank" rel="noopener">
      💬 WhatsApp
    </a>
  </div>
</header>

<section class="hero">
  <div class="wrap hero-inner">
    <div>
      <div class="eyebrow">Natural • Safe • Effective</div>
      <h1>होम्योपैथी से पाएं<br><em>जड़ से राहत</em>, बिना साइड इफेक्ट</h1>
      <p>TheHomeoVibe पर हर बीमारी की सही जानकारी और प्राकृतिक होम्योपैथिक इलाज — Dr. Vijay Reswal (BHMS) की विशेषज्ञ सलाह के साथ।</p>
      <div class="hero-ctas">
        <a class="btn-whatsapp" href="https://wa.me/918764306828?text=Namaste%2C%20mujhe%20consultation%20chahiye" target="_blank" rel="noopener">💬 अभी WhatsApp करें</a>
        <button class="btn-primary" onclick="document.getElementById('library').scrollIntoView({behavior:'smooth'})">बीमारियाँ देखें</button>
      </div>
    </div>
    <div class="doc-card">
      <div class="doc-avatar">VR</div>
      <div>
        <div class="doc-name">Dr. Vijay Reswal (BHMS)</div>
        <div class="doc-meta">📍 Near No. 2 School, Todabhim (Rajasthan)</div>
        <div class="doc-meta">🕐 परामर्श समय: 10:00 AM – 5:00 PM</div>
        <div class="doc-actions">
          <a class="mini-link" href="https://wa.me/918764306828" target="_blank" rel="noopener">📞 8764306828</a>
          <a class="mini-link" href="https://instagram.com/TheHomeoVibe" target="_blank" rel="noopener">📷 @TheHomeoVibe</a>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="trust-strip">
  <div class="wrap trust-inner">
    <div>100% प्राकृतिक व सुरक्षित</div>
    <div>कोई साइड इफेक्ट नहीं</div>
    <div>जड़ से इलाज</div>
    <div>गोपनीय व भरोसेमंद परामर्श</div>
  </div>
</div>

<section class="block" id="library">
  <div class="wrap">
    <div class="section-head">
      <div>
        <h2>बीमारियाँ व होम्योपैथिक इलाज</h2>
        <p>लक्षण, कारण और होम्योपैथी से सुरक्षित समाधान — किसी भी बीमारी पर क्लिक करें।</p>
      </div>
    </div>
    <div class="cond-grid" id="condGrid"></div>
  </div>
</section>

<section class="block" id="about" style="padding-top:0;">
  <div class="wrap">
    <div class="section-head"><div><h2>डॉक्टर के बारे में</h2></div></div>
    <div class="about-grid">
      <div class="about-photo">VR</div>
      <div class="about-text">
        <p><strong>Dr. Vijay Reswal (BHMS)</strong> — TheHomeoVibe Homeopathy Pharmacy के संस्थापक व मुख्य चिकित्सक, जो Todabhim (Rajasthan) में मरीज़ों को प्राकृतिक, सुरक्षित व असरदार होम्योपैथिक इलाज देते हैं।</p>
        <p>यहां दर्द, ज्वर, त्वचा, पाचन, महिला व पुरुष स्वास्थ्य समस्याओं से लेकर लिवर व एलर्जी तक — हर तरह की बीमारी का जड़ से इलाज किया जाता है, बिना किसी साइड इफेक्ट के।</p>
        <div class="about-badges">
          <span class="about-badge">✔ 100% प्राकृतिक</span>
          <span class="about-badge">✔ No Side Effects</span>
          <span class="about-badge">✔ गोपनीय परामर्श</span>
          <span class="about-badge">✔ जड़ से इलाज</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="block why" id="why">
  <div class="wrap">
    <div class="section-head"><div><h2>TheHomeoVibe क्यों चुनें</h2><p>हर मरीज़ के लिए सुरक्षित व असरदार इलाज की गारंटी।</p></div></div>
    <div class="why-grid">
      <div class="why-card"><div class="why-num mono">०१</div><h3>100% प्राकृतिक</h3><p>बिना किसी रासायनिक साइड इफेक्ट के सुरक्षित इलाज।</p></div>
      <div class="why-card"><div class="why-num mono">०२</div><h3>जड़ से इलाज</h3><p>सिर्फ लक्षण नहीं, बीमारी के मूल कारण पर काम।</p></div>
      <div class="why-card"><div class="why-num mono">०३</div><h3>गोपनीय परामर्श</h3><p>व्यक्तिगत समस्याओं पर भरोसेमंद व निजी सलाह।</p></div>
      <div class="why-card"><div class="why-num mono">०४</div><h3>दीर्घकालिक राहत</h3><p>स्थायी परिणाम, बार-बार दवा पर निर्भरता नहीं।</p></div>
    </div>
  </div>
</section>

<section class="block" id="contact">
  <div class="wrap">
    <div class="section-head"><div><h2>संपर्क करें</h2><p>अपॉइंटमेंट या ऑनलाइन परामर्श के लिए नीचे दिए गए किसी भी माध्यम से संपर्क करें।</p></div></div>
    <div class="contact-grid">
      <div class="contact-card">
        <div class="contact-icon">📍</div>
        <h4>क्लिनिक का पता</h4>
        <p>Homeopathy Pharmacy<br>Near No. 2 School, Todabhim (Rajasthan)</p>
      </div>
      <div class="contact-card">
        <div class="contact-icon">📞</div>
        <h4>कॉल / WhatsApp</h4>
        <a class="mono" href="https://wa.me/918764306828" target="_blank" rel="noopener">8764306828</a>
        <p style="margin-top:6px;">परामर्श समय: 10:00 AM – 5:00 PM</p>
      </div>
      <div class="contact-card">
        <div class="contact-icon">📷</div>
        <h4>Instagram पर Follow करें</h4>
        <a class="mono" href="https://instagram.com/TheHomeoVibe" target="_blank" rel="noopener">@TheHomeoVibe</a>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    <div class="foot-grid">
      <div>
        <div class="logo" style="margin-bottom:14px;">
          <div class="logo-mark"></div>
          <div><div class="logo-text" style="color:var(--cream);">The<span>Homeo</span>Vibe</div></div>
        </div>
        <p>प्रकृति की शक्ति, होम्योपैथी की भक्ति — Natural, Safe, Effective.</p>
      </div>
      <div><h4>बीमारियाँ</h4><ul><li><a href="#library">स्वास्थ्य जानकारी</a></li><li><a href="#about">डॉक्टर</a></li></ul></div>
      <div><h4>कंपनी</h4><ul><li><a href="#why">क्यों चुनें</a></li><li><a href="#contact">संपर्क</a></li></ul></div>
      <div><h4>संपर्क करें</h4><p>📞 8764306828<br>📍 Todabhim (Rajasthan)<br>📷 @TheHomeoVibe</p></div>
    </div>
    <div class="foot-bottom">
      <span>© 2026 TheHomeoVibe Homeopathy Pharmacy.</span>
      <span>यह एक डेमो वेबसाइट है।</span>
    </div>
  </div>
</footer>

<a class="wa-float" href="https://wa.me/918764306828?text=Namaste%2C%20mujhe%20consultation%20chahiye" target="_blank" rel="noopener" aria-label="WhatsApp पर संपर्क करें">💬</a>

<div class="overlay" id="condOverlay"><div class="detail-sheet" id="condSheet"></div></div>

<script>
const WA_NUMBER = "918764306828";
function waLink(text){ return `https://wa.me/${WA_NUMBER}?text=${encodeURIComponent(text)}`; }

const conditions = [
  {
    id:"diabetes-bp", icon:"🩸", tag:"डायबिटीज व बी.पी.", name:"डायबिटीज और बी.पी.",
    hindi:"ब्लड शुगर व ब्लड प्रेशर की समस्या",
    intro:"डायबिटीज (मधुमेह) में ब्लड शुगर लेवल असंतुलित हो जाता है, वहीं बी.पी. (उच्च या निम्न) में ब्लड प्रेशर स्तर बिगड़ जाता है। होम्योपैथी दोनों को जड़ से नियंत्रित करने में सुरक्षित रूप से मदद करती है, बिना साइड इफेक्ट के।",
    symptoms:["बार-बार प्यास व पेशाब आना","थकान व कमजोरी","पैरों में जलन, झुनझुनाहट","सिरदर्द, चक्कर आना (बी.पी.)","धड़कन तेज होना, धुंधला दिखना"],
    causes:["अनियमित खानपान","तनाव व चिंता","शारीरिक गतिविधि की कमी","मोटापा","पारिवारिक इतिहास"],
    remedies:[["Syzygium","ब्लड शुगर नियंत्रण"],["Uranium Nit","अधिक पेशाब व प्यास"],["Rauwolfia","हाई बी.पी. नियंत्रण"],["Crataegus","हृदय व बी.पी. संतुलन"]]
  },
  {
    id:"ringworm", icon:"🧴", tag:"त्वचा रोग", name:"दाद (Ringworm)",
    hindi:"त्वचा, स्कैल्प व नाखूनों में फंगल संक्रमण",
    intro:"दाद (Ringworm) एक फंगल संक्रमण है जो त्वचा, स्कैल्प, नाखून व शरीर के किसी भी हिस्से पर हो सकता है। यह संक्रामक है पर पूरी तरह ठीक हो सकता है। होम्योपैथी जड़ से इलाज कर immunity भी बढ़ाती है।",
    symptoms:["लाल, गोल आकार के दाने","खुजली, जलन या जलन","पपड़ीदार त्वचा","किनारों पर फैलना","बालों का झड़ना (स्कैल्प में)"],
    causes:["फंगल संक्रमण","व्यक्तिगत सामान साझा करना","गीली जगहों पर नंगे पैर चलना","कमजोर प्रतिरक्षा प्रणाली"],
    remedies:[["Sulphur","खुजली, जलन व लालिमा"],["Psorinum","दुर्गंध व पुराने मामलों में"],["Natrum Mur","सूखी, पपड़ीदार त्वचा"],["Petroleum","सूखी, खुजलीदार त्वचा"]]
  },
  {
    id:"joint-sciatica", icon:"🦴", tag:"दर्द व सूजन", name:"जोड़ों का दर्द, सायटिका व गठिया",
    hindi:"जोड़ों में दर्द, सूजन व जकड़न",
    intro:"जोड़ों का दर्द, सायटिका (कमर से पैर तक जाने वाला दर्द) व गठिया आम समस्याएं हैं जो उम्र, चोट या गलत मुद्रा से होती हैं। होम्योपैथी दर्द व सूजन में राहत देकर लंबे समय तक असर दिखाती है।",
    symptoms:["जोड़ों में दर्द, सूजन व जकड़न","कमर से पैर तक दर्द (सायटिका)","उठने-बैठने में परेशानी","मौसम बदलने पर दर्द बढ़ना"],
    causes:["उम्र बढ़ना","वात बढ़ना","गलत बैठने या चलने की आदत","मोटापा व शारीरिक गतिविधि की कमी"],
    remedies:[["Rhus Tox","अकड़न, चलने से आराम"],["Kali Carb","कमर से पैर तक दर्द"],["Arnica","चोट व मोच से"],["Ruta Grav","मांसपेशी व टेंडन दर्द"]]
  },
  {
    id:"women-health", icon:"👩", tag:"महिला स्वास्थ्य", name:"महिला समस्याएं (PID, PCOS, VIT, Fibroid, Endometriosis)",
    hindi:"हार्मोनल व प्रजनन स्वास्थ्य समस्याएं",
    intro:"PID, PCOS, सफेद पानी (VIT), गर्भाशय की गांठ (Fibroid) व Endometriosis जैसी समस्याएं महिलाओं में आम हैं। होम्योपैथी हार्मोनल असंतुलन ठीक कर, बिना साइड इफेक्ट के प्रजनन स्वास्थ्य सुधारती है।",
    symptoms:["अनियमित पीरियड्स","पेट के निचले हिस्से में दर्द","सफेद पानी/दुर्गंधयुक्त स्राव","संभोग के समय दर्द","बार-बार यूरिन आना, थकान"],
    causes:["हार्मोनल असंतुलन","संक्रमण","तनाव","गलत खानपान व जीवनशैली"],
    remedies:[["Sepia","हार्मोनल असंतुलन व थकान"],["Pulsatilla","अनियमित पीरियड्स"],["Calc Carb","PCOS व वजन बढ़ना"],["Thuja","गांठ व सिस्ट"]]
  },
  {
    id:"warts", icon:"🖐️", tag:"त्वचा रोग", name:"मस्सा (Warts)",
    hindi:"त्वचा पर उभरे हुए दाने (HPV संक्रमण)",
    intro:"मस्सा (Warts) त्वचा पर होने वाली एक आम समस्या है जो HPV वायरस के कारण होती है। यह हाथ, पैर, चेहरे या शरीर के किसी भी हिस्से पर हो सकता है। होम्योपैथी जड़ से इलाज कर दोबारा होने से भी रोकती है।",
    symptoms:["त्वचा पर छोटा, खुरदरा उभार","स्पर्श करने पर कठोर महसूस होना","धीरे-धीरे आकार बढ़ना","दबाने पर तकलीफ (खासकर पादतल मस्से में)"],
    causes:["HPV वायरस का संक्रमण","त्वचा पर चोट या कट","संक्रमित व्यक्ति के संपर्क में आना","कमजोर प्रतिरक्षा प्रणाली"],
    remedies:[["Thuja","सामान्य मस्से, सबसे असरदार"],["Antim Crud","कठोर, मोटे मस्से"],["Causticum","चेहरे व पलकों के मस्से"],["Nitric Acid","खून बहने वाले मस्से"]]
  },
  {
    id:"men-health", icon:"👨", tag:"पुरुष स्वास्थ्य", name:"पुरुषों की गुप्त समस्याएं",
    hindi:"नपुंसकता, स्वप्नदोष व शीघ्रपतन",
    intro:"नपुंसकता (Impotency), स्वप्नदोष (Nightfall) व शीघ्रपतन (Rapid Ejaculation) पुरुषों में शर्म के कारण अक्सर छुपाई जाने वाली समस्याएं हैं। होम्योपैथी गोपनीय व सुरक्षित तरीके से जड़ से इलाज करती है।",
    symptoms:["लिंग में तनाव न आना या जल्दी ढीला पड़ना","नींद में वीर्य का निकलना","संभोग के 1-2 मिनट में वीर्यपतन","सेक्स इच्छा में कमी, आत्मविश्वास की कमी"],
    causes:["अधिक हस्तमैथुन","तनाव, चिंता व डिप्रेशन","कमजोर पाचन व अनियमित दिनचर्या","नशे का सेवन"],
    remedies:[["Damiana","यौन शक्ति व स्टेमिना"],["Lycopodium","आत्मविश्वास व नपुंसकता"],["Selenium","स्वप्नदोष व कमजोरी"],["Agnus Castus","यौन इच्छा में कमी"]]
  },
  {
    id:"allergy", icon:"🤧", tag:"एलर्जी", name:"एलर्जी (धूल, गेहूं, त्वचा)",
    hindi:"इम्यून सिस्टम की अतिसंवेदनशील प्रतिक्रिया",
    intro:"एलर्जी तब होती है जब शरीर का इम्यून सिस्टम किसी सामान्य पदार्थ को हानिकारक समझकर प्रतिक्रिया करता है — जैसे धूल-मिट्टी, गेहूं (ग्लूटेन) या त्वचा से जुड़ी एलर्जी। होम्योपैथी शरीर की प्रतिरोधक क्षमता बढ़ाकर स्थायी राहत देती है।",
    symptoms:["छींकें आना, नाक बहना","आँखों में जलन व खुजली","त्वचा पर लाल चकत्ते व खुजली","पेट दर्द, गैस, सूजन (गेहूं एलर्जी में)","सांस लेने में तकलीफ"],
    causes:["धूल, धुआं, पराग कण","गेहूं/ग्लूटेन प्रोटीन","केमिकल्स, साबुन, डिटर्जेंट","कमजोर प्रतिरक्षा प्रणाली"],
    remedies:[["Allium Cepa","नाक बहना, छींकें"],["Natrum Mur","त्वचा एलर्जी"],["Arsenicum Alb","धूल एलर्जी, सांस तकलीफ"],["Nux Vomica","पाचन से जुड़ी एलर्जी"]]
  },
  {
    id:"liver-spleen", icon:"🫀", tag:"लिवर व प्लीहा", name:"लिवर व प्लीहा वृद्धि",
    hindi:"यकृत व तिल्ली का आकार बढ़ना",
    intro:"जब लिवर या प्लीहा का आकार सामान्य से बड़ा हो जाता है, तो इसे क्रमशः Hepatomegaly व Splenomegaly कहते हैं। यह फैटी लिवर, हेपेटाइटिस, संक्रमण या अन्य कारणों से हो सकता है। होम्योपैथिक उपचार सुरक्षित व प्रभावी सहायता देता है।",
    symptoms:["पेट के दाहिने हिस्से में भारीपन या दर्द","भूख कम लगना, पेट फूलना","पीलिया (आँखों व त्वचा का पीला होना)","थकान, कमजोरी, वजन कम होना","बार-बार बुखार या संक्रमण"],
    causes:["फैटी लिवर","वायरल हेपेटाइटिस","शराब का सेवन","मलेरिया, डेंगू, टायफाइड","दवाइयों का असर"],
    remedies:[["Chelidonium","लिवर की सूजन व दर्द"],["Lycopodium","पाचन व लिवर कमजोरी"],["Ceanothus","प्लीहा वृद्धि"],["Cardus Mar","लिवर डिटॉक्स व सुरक्षा"]]
  },
  {
    id:"headache-migraine", icon:"🤕", tag:"सिरदर्द व नींद", name:"सिरदर्द, माइग्रेन व अनिद्रा",
    hindi:"बार-बार सिरदर्द व नींद न आने की समस्या",
    intro:"सिरदर्द, माइग्रेन व अनिद्रा तनाव, अनियमित दिनचर्या व अधिक स्क्रीन टाइम से जुड़ी आम समस्याएं हैं। होम्योपैथी समस्या की जड़ तक पहुंचकर मन को शांत करती है व गहरी नींद लाने में मदद करती है।",
    symptoms:["सिर के एक या दोनों तरफ दर्द","तेज रोशनी/आवाज़ से परेशानी, मितली","नींद न आना, बार-बार जागना","दिन में नींद आना, थकान, चिड़चिड़ापन"],
    causes:["अधिक तनाव व सोच-विचार","अनियमित नींद","मोबाइल/स्क्रीन का अधिक उपयोग","गलत खान-पान, व्यायाम की कमी"],
    remedies:[["Belladonna","धड़कता तेज सिरदर्द"],["Nux Vomica","तनाव व अनिद्रा"],["Coffea Cruda","विचारों की अधिकता से नींद न आना"],["Gelsemium","सुस्ती के साथ सिरदर्द"]]
  }
];

const condGrid = document.getElementById('condGrid');
conditions.forEach(c=>{
  const card=document.createElement('div');
  card.className='cond-card';
  card.innerHTML=`<div class="cond-banner">${c.icon}</div><div class="cond-body"><span class="cond-tag">${c.tag}</span><h3>${c.name}</h3><p>${c.hindi}</p></div>`;
  card.addEventListener('click',()=>openCondition(c.id));
  condGrid.appendChild(card);
});

function openCondition(id){
  const c=conditions.find(x=>x.id===id);
  const sheet=document.getElementById('condSheet');
  sheet.innerHTML=`
    <button class="detail-close" id="condClose">✕</button>
    <div class="detail-head">
      <div class="detail-eyebrow">${c.tag} • Safe & Gentle</div>
      <h2>${c.name}</h2>
      <div class="hindi">${c.hindi}</div>
    </div>
    <div class="detail-body">
      <p class="detail-intro">${c.intro}</p>
      <div class="detail-grid">
        <div class="info-box"><h4>🩺 सामान्य लक्षण</h4><ul>${c.symptoms.map(s=>`<li>${s}</li>`).join('')}</ul></div>
        <div class="info-box"><h4>⚙️ मुख्य कारण</h4><ul>${c.causes.map(s=>`<li>${s}</li>`).join('')}</ul></div>
      </div>
      <div class="remedy-strip">
        <h4>💊 होम्योपैथिक उपचार</h4>
        <div class="remedy-row">${c.remedies.map(r=>`<div class="remedy-chip"><span class="mono">${r[0]}</span><span class="desc">${r[1]}</span></div>`).join('')}</div>
        <p class="detail-note">नोट: सही दवा व पोटेंसी व्यक्तिगत लक्षणों पर निर्भर करती है — कृपया योग्य होम्योपैथिक चिकित्सक से सलाह ज़रूर लें।</p>
      </div>
      <div class="doctor-alert">⚠️ लक्षण गंभीर हों, लंबे समय से बने हों, या असहनीय दर्द/परेशानी हो — तुरंत डॉक्टर से संपर्क करें।</div>
      <div class="consult-cta">
        <span>💬 इस समस्या पर Dr. Vijay Reswal से मुफ्त सलाह लें</span>
        <a href="${waLink('Namaste Doctor, mujhe "'+c.name+'" ke baare mein salah chahiye.')}" target="_blank" rel="noopener"><button>WhatsApp करें</button></a>
      </div>
    </div>`;
  document.getElementById('condOverlay').classList.add('show');
  document.getElementById('condClose').addEventListener('click',()=>document.getElementById('condOverlay').classList.remove('show'));
}
document.getElementById('condOverlay').addEventListener('click',e=>{if(e.target.id==='condOverlay')e.target.classList.remove('show');});
</script>
</body>
</html>
