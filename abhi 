<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abhishek Yadav | Web Developer & Cybersecurity Enthusiast</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
<style>
  :root{
    --bg:#0a0a0c;
    --bg-alt:#111114;
    --panel:#16161a;
    --line:#28282d;
    --gold:#c9a15a;
    --gold-bright:#e8c887;
    --cyan:#5fd4c8;
    --violet:#b98bf0;
    --coral:#f0876b;
    --steel:#8a94a6;
    --text:#efece4;
    --muted:#93938f;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    background:
      radial-gradient(ellipse 60% 40% at 20% 0%, rgba(201,161,90,0.08), transparent 60%),
      var(--bg);
    color:var(--text);
    font-family:'Inter',-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;
    overflow-x:hidden;
  }
  h1,h2,h3,.display{font-family:'Fraunces','Georgia',serif;letter-spacing:-0.01em;font-weight:500;}
  a{color:inherit;text-decoration:none;}
  img{display:block;max-width:100%;}

  nav{
    position:fixed;top:0;left:0;right:0;z-index:60;
    display:flex;justify-content:space-between;align-items:center;
    padding:26px 6%;
    background:linear-gradient(to bottom, rgba(10,10,12,0.92), transparent);
  }
  nav .mark{font-family:'Fraunces',serif;font-weight:500;font-size:1.2rem;letter-spacing:0.02em;}
  nav .mark span{color:var(--gold);}
  nav ul{display:flex;gap:38px;list-style:none;}
  nav ul li a{font-size:0.9rem;color:var(--muted);transition:color .25s;}
  nav ul li a:hover{color:var(--gold-bright);}
  @media(max-width:720px){nav ul{gap:16px;} nav ul li a{font-size:0.76rem;}}

  /* floating action buttons */
  .fab-stack{
    position:fixed;right:22px;bottom:28px;z-index:70;
    display:flex;flex-direction:column;gap:14px;align-items:center;
  }
  .fab{
    width:52px;height:52px;border-radius:50%;
    display:flex;align-items:center;justify-content:center;
    background:rgba(22,22,26,0.9);
    border:1px solid var(--line);
    backdrop-filter:blur(6px);
    transition:transform .2s, border-color .2s;
    font-size:1.2rem;
  }
  .fab:hover{transform:translateY(-3px);border-color:var(--gold);}
  .fab.whatsapp{color:#3ddc97;border-color:rgba(61,220,151,0.35);}
  .fab.top{color:var(--cyan);border-color:rgba(95,212,200,0.35);}

  /* HERO */
  #hero{
    position:relative;min-height:100svh;display:flex;align-items:center;
    overflow:hidden;border-bottom:1px solid var(--line);padding-top:90px;
  }
  #hero-canvas{position:absolute;inset:0;z-index:0;opacity:0.75;}
  .hero-wrap{
    position:relative;z-index:2;padding:0 6%;width:100%;
    display:grid;grid-template-columns:1.3fr 0.7fr;gap:60px;align-items:center;
  }
  .eyebrow{color:var(--steel);font-size:0.95rem;margin-bottom:20px;letter-spacing:0.02em;}
  .hero-content h1{font-size:clamp(2.2rem,4.8vw,3.9rem);line-height:1.1;margin-bottom:22px;}
  .hero-content h1 em{font-style:italic;color:var(--gold-bright);}
  .hero-content p{font-size:1.08rem;color:var(--muted);max-width:540px;line-height:1.65;margin-bottom:28px;}
  .hero-content p b{color:var(--text);}
  .hero-content p .accent{color:var(--cyan);}
  .pill-row{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:34px;}
  .pill{border:1px solid var(--line);color:var(--muted);font-size:0.82rem;padding:7px 16px;border-radius:20px;}
  .pill.c-gold{border-color:rgba(201,161,90,0.5);color:var(--gold-bright);}
  .pill.c-cyan{border-color:rgba(95,212,200,0.5);color:var(--cyan);}
  .pill.c-violet{border-color:rgba(185,139,240,0.5);color:var(--violet);}
  .pill.c-coral{border-color:rgba(240,135,107,0.5);color:var(--coral);}
  .hero-actions{display:flex;gap:16px;flex-wrap:wrap;}
  .btn{display:inline-block;padding:15px 30px;border-radius:2px;font-size:0.95rem;font-weight:500;transition:all .25s;border:1px solid transparent;}
  .btn-primary{background:linear-gradient(135deg,var(--gold-bright),var(--gold));color:#161310;}
  .btn-primary:hover{filter:brightness(1.1);transform:translateY(-1px);}
  .btn-secondary{border-color:var(--line);color:var(--text);}
  .btn-secondary:hover{border-color:var(--gold);color:var(--gold-bright);}

  .portrait-frame{position:relative;justify-self:center;width:min(300px,80%);aspect-ratio:1/1;}
  .portrait-ring{position:absolute;inset:-14px;border:1px solid var(--gold);border-radius:50%;opacity:0.55;}
  .portrait-ring.outer{inset:-28px;opacity:0.25;}
  .portrait-frame img{width:100%;height:100%;border-radius:50%;object-fit:cover;
    box-shadow:0 30px 60px -20px rgba(0,0,0,0.7), 0 0 0 1px rgba(201,161,90,0.15);
    animation:spin-slow 14s linear infinite;}
  @keyframes spin-slow{from{transform:rotate(0deg);}to{transform:rotate(360deg);}}
  .portrait-ring{animation:spin-slow 22s linear infinite reverse;}
  .portrait-ring.outer{animation:spin-slow 30s linear infinite;}
  .cap-badge{
    position:absolute;top:-16px;left:50%;transform:translateX(-50%) rotate(-4deg);
    background:linear-gradient(135deg,#1c1c20,#0d0d0f);
    border:1px solid var(--gold);color:var(--gold-bright);
    font-family:'Fraunces',serif;font-weight:600;font-size:0.95rem;
    padding:8px 20px;border-radius:6px 6px 4px 4px;
    box-shadow:0 8px 20px rgba(0,0,0,0.5);
    letter-spacing:0.03em;z-index:3;
  }
  .cap-badge::after{
    content:'';position:absolute;bottom:-6px;left:50%;transform:translateX(-50%);
    width:36px;height:6px;background:inherit;border-radius:0 0 8px 8px;border:1px solid var(--gold);border-top:none;
  }
  @media(max-width:820px){
    .hero-wrap{grid-template-columns:1fr;text-align:left;}
    .portrait-frame{order:-1;width:180px;margin-bottom:30px;}
  }

  section{padding:120px 6%;max-width:1180px;margin:0 auto;}
  .section-head{margin-bottom:56px;max-width:600px;}
  .section-head .tag{color:var(--gold);font-size:0.9rem;margin-bottom:14px;letter-spacing:0.02em;}
  .section-head h2{font-size:clamp(1.9rem,3.4vw,2.7rem);line-height:1.2;}
  .section-head p{color:var(--muted);margin-top:18px;line-height:1.6;}

  /* CERTIFICATES */
  .cert-grid{display:grid;grid-template-columns:1.1fr 0.9fr;gap:40px;align-items:start;}
  .cert-card{border:1px solid var(--line);border-radius:10px;overflow:hidden;background:var(--bg-alt);}
  .cert-card img{width:100%;}
  .cert-side{display:flex;flex-direction:column;gap:18px;}
  .cert-mini{border:1px solid var(--line);border-radius:8px;padding:24px;background:var(--bg-alt);}
  .cert-mini .cname{font-family:'Fraunces',serif;font-size:1.1rem;margin-bottom:6px;}
  .cert-mini .cissuer{color:var(--gold);font-size:0.85rem;}
  .cert-mini .cnote{color:var(--muted);font-size:0.85rem;margin-top:8px;}
  @media(max-width:820px){.cert-grid{grid-template-columns:1fr;}}

  /* TECH BUBBLES */
  .bubble-field{
    position:relative;min-height:340px;display:flex;flex-wrap:wrap;
    gap:26px;align-items:center;justify-content:center;padding:20px 0;
  }
  .bubble{
    width:74px;height:74px;border-radius:50%;
    background:radial-gradient(circle at 32% 28%, #2a2a30, #131316 70%);
    border:1px solid var(--line);
    display:flex;align-items:center;justify-content:center;font-size:1.7rem;
    animation:float 5s ease-in-out infinite;
    box-shadow:0 10px 26px rgba(0,0,0,0.5);
  }
  .bubble:nth-child(2n){animation-duration:6.2s;animation-delay:.4s;}
  .bubble:nth-child(3n){animation-duration:4.4s;animation-delay:.8s;}
  .bubble:nth-child(4n){animation-duration:7s;animation-delay:.2s;}
  @keyframes float{0%,100%{transform:translateY(0);}50%{transform:translateY(-16px);}}
  .bubble.r-gold{border-color:rgba(201,161,90,0.55);box-shadow:0 10px 26px rgba(201,161,90,0.15);}
  .bubble.r-cyan{border-color:rgba(95,212,200,0.55);box-shadow:0 10px 26px rgba(95,212,200,0.15);}
  .bubble.r-violet{border-color:rgba(185,139,240,0.55);box-shadow:0 10px 26px rgba(185,139,240,0.15);}
  .bubble.r-coral{border-color:rgba(240,135,107,0.55);box-shadow:0 10px 26px rgba(240,135,107,0.15);}
  .bubble-label{font-size:0.7rem;font-weight:600;letter-spacing:0.03em;}

  /* EDUCATION */
  .edu-item{display:grid;grid-template-columns:70px 1fr;gap:28px;padding:36px 0;border-top:1px solid var(--line);}
  .edu-item:last-child{border-bottom:1px solid var(--line);}
  .edu-num{font-family:'Fraunces',serif;font-size:2.2rem;color:var(--line);}
  .edu-item h3{font-size:1.4rem;margin-bottom:6px;}
  .edu-school{color:var(--steel);margin-bottom:14px;}
  .badge-row{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:16px;}
  .badge{border:1px solid var(--line);color:var(--cyan);font-size:0.82rem;padding:6px 14px;border-radius:16px;}
  .edu-item:nth-of-type(2) .badge{color:var(--violet);}
  .edu-item:nth-of-type(3) .badge{color:var(--coral);}
  .edu-item ul{list-style:none;color:var(--muted);font-size:0.92rem;line-height:1.9;}
  .edu-item ul li::before{content:'✓ ';color:var(--cyan);}
  @media(max-width:600px){.edu-item{grid-template-columns:1fr;}}

  /* PROJECTS */
  .project-card{
    border:1px solid var(--line);border-radius:10px;padding:36px;margin-bottom:28px;
    background:var(--bg-alt);
  }
  .project-card .pname{font-family:'Fraunces',serif;font-size:1.5rem;margin-bottom:14px;}
  .project-card .pdesc{color:var(--muted);line-height:1.7;font-size:0.98rem;margin-bottom:18px;}
  .project-card .ptags{display:flex;gap:10px;flex-wrap:wrap;}
  .project-card .ptags span{font-size:0.78rem;color:var(--gold);border:1px solid var(--line);padding:5px 12px;border-radius:2px;}
  .project-card .ptags span:nth-child(2){color:var(--cyan);}
  .project-card .ptags span:nth-child(3){color:var(--violet);}

  /* CONTACT */
  #contact{border-top:1px solid var(--line);}
  #contact h2{font-size:clamp(2.1rem,4.6vw,3.4rem);max-width:700px;line-height:1.15;}
  .contact-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:var(--line);border:1px solid var(--line);margin:50px 0;}
  .contact-cell{background:var(--bg-alt);padding:30px;}
  .contact-cell .clabel{color:var(--steel);font-size:0.82rem;letter-spacing:0.05em;margin-bottom:10px;}
  .contact-cell .cval{font-size:1.02rem;}
  @media(max-width:820px){.contact-grid{grid-template-columns:1fr;}}
  .contact-links{display:flex;gap:16px;flex-wrap:wrap;}
  .contact-links a{display:inline-flex;align-items:center;gap:10px;border:1px solid var(--line);padding:13px 22px;border-radius:2px;font-size:0.95rem;transition:all .25s;}
  .contact-links a:hover{border-color:var(--gold);color:var(--gold-bright);transform:translateY(-2px);}

  footer{padding:34px 6%;color:var(--muted);font-size:0.85rem;display:flex;justify-content:space-between;border-top:1px solid var(--line);}
  @media(max-width:600px){footer{flex-direction:column;gap:8px;}}
</style>
</head>
<body>

<nav>
  <div class="mark">abhishek<span>.</span></div>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Work</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<div class="fab-stack">
  <a class="fab top" href="#hero" title="Back to top">↑</a>
  <a class="fab whatsapp" href="https://wa.me/919610525830" target="_blank" title="WhatsApp">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="currentColor"><path d="M17.5 14.4c-.3-.1-1.7-.9-2-1-.3-.1-.5-.1-.7.1-.2.3-.7 1-.9 1.2-.2.2-.3.2-.6.1-.3-.1-1.3-.5-2.4-1.5-.9-.8-1.5-1.8-1.7-2.1-.2-.3 0-.5.1-.6.1-.1.3-.3.4-.5.1-.1.2-.3.3-.5.1-.2 0-.4 0-.5C10 9 9.5 7.6 9.3 7c-.2-.5-.4-.5-.6-.5h-.5c-.2 0-.5.1-.7.3-.2.3-.9.9-.9 2.2s1 2.6 1.1 2.7c.1.2 2 3 4.7 4.2.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.5-.1 1.7-.7 1.9-1.4.2-.7.2-1.2.2-1.3-.1-.1-.3-.2-.6-.3z"/><path d="M12 2C6.5 2 2 6.5 2 12c0 1.9.5 3.7 1.5 5.3L2 22l4.9-1.3c1.5.8 3.2 1.3 5.1 1.3 5.5 0 10-4.5 10-10S17.5 2 12 2zm0 18.3c-1.7 0-3.4-.5-4.8-1.3l-.3-.2-3.4.9.9-3.3-.2-.3C3.5 14.6 3 13.3 3 12c0-4.9 4-8.9 9-8.9s9 4 9 8.9-4 9-9 9z"/></svg>
  </a>
  <a class="fab" href="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAYEBQYFBAYGBQYHBwYIChAKCgkJChQODwwQFxQYGBcUFhYaHSUfGhsjHBYWICwgIyYnKSopGR8tMC0oMCUoKSj/2wBDAQcHBwoIChMKChMoGhYaKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCj/wAARCAWIA4QDASIAAhEBAxEB/8QAHAABAAIDAQEBAAAAAAAAAAAAAAQGAwUHAgEI/8QAVBAAAQQCAAMECAQCCAQDBQIPAQACAwQFEQYSIRMUMUEHIlFSU2FxkRUygZIj0QgWM0JWYpShNHKxwRckQ3N0grPhGDU2N7LwJWN1oiZVZXaEpPH/xAAYAQEBAQEBAAAAAAAAAAAAAAAAAQIDBP/EACoRAQACAgEDBAEFAQEBAQAAAAABEQISIRMxUgNBodFRBCJhgfAUMiNC/9oADAMBAAIRAxEAPwD9MoiKoIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZORvuj7JZSAin8jfdH2Tkb7o+yWUgIp/I33R9k5G+6PsllICKfyN90fZEsp9REUUREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQE2irPpJ4hZwtwVlcs4t7SGF3ZNP96QjTQrEXwkzXLmnEf9ILGYfim5im4qaeGrY7u+y2bQ6HTnAa8Au2U7EdupDZgdzQzMbIx3taRsFfhDH8H3Mr6Ps5xY50jm0rLGu317Vjvzu+ocQF+nv6N/E5z/AKO69axJz3MY81ZCT1I8Wn6aIH6Lt6npxEXi5ennMzUtt6WvSRD6Pa2Plmx8l0W3uYAyTk5eXXy+a5r/APaaog6dgJh//kj+S+/0v/8A7s4e/wDay/8ARq3HolPAH/h7h/xocMd+7I9r3psJl3s/m5uqRjjGETMWTlO1RKZwr/SD4VzFuOtfjtYySRwa2SUB0Wz7XDw+y65etNq46xbA7RsUTpdA/mABPivx/wD0gZ+DrWcx0XA8VbvQDmWu5M5YnE/kDQOhdvfgv0pwzWu1PRHSr5Rr23YsRyTB/iHCI7B+aznhEREwuGUzMxKt+i/0x1+O+InYqHEy1HNiMvaOl5h08taXVZ5OyhfIRvlaXa+g2vxz/RsytDD8fyWMpcgpwGq5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