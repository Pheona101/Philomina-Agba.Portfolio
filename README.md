# Philomina-Agba.Portfolio
Landing page for my MailerLite job application
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Philomina Agba – Product Designer</title>
<meta name="description" content="Philomina Agba, Product Designer with 6+ years across SaaS, FinTech, Healthcare and E-commerce. Application for MailerLite.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&family=Instrument+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#F1F6F3;--ink:#12211A;--muted:#51615A;--line:#D3DFD8;--card:#fff;--brand:#0BA55C;--soft:#DCF3E6;--sun:#FFC93C;--radius:14px;
--display:"Bricolage Grotesque","Trebuchet MS",system-ui,sans-serif;--body:"Instrument Sans",system-ui,-apple-system,"Segoe UI",sans-serif}
*{box-sizing:border-box}html{scroll-behavior:smooth;scroll-padding-top:70px}
body{margin:0;background:var(--bg);color:var(--ink);font:400 1.0625rem/1.65 var(--body);-webkit-font-smoothing:antialiased;overflow-x:hidden}
a{color:inherit}:focus-visible{outline:3px solid var(--ink);outline-offset:3px;border-radius:6px}
.wrap{width:min(1120px,100% - 2.5rem);margin-inline:auto}
#bar{position:fixed;top:0;left:0;height:4px;width:0;background:var(--brand);z-index:20;transition:width .1s}
header.top{position:sticky;top:0;z-index:10;background:color-mix(in srgb,var(--bg) 88%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
header.top .wrap{display:flex;align-items:center;justify-content:space-between;padding:.8rem 0;gap:1rem}
.logo{font:800 1.15rem var(--display);text-decoration:none;display:flex;align-items:center;gap:.5rem}
.logo i{display:grid;place-items:center;width:2rem;height:2rem;border-radius:50%;background:var(--brand);color:#fff;font:800 .85rem var(--display);font-style:normal;transition:transform .4s}
.logo:hover i{transform:rotate(360deg)}
nav{display:flex;gap:1.1rem;font-size:.95rem;font-weight:500;flex-wrap:wrap}
nav a{text-decoration:none;color:var(--muted);position:relative;padding:.1rem 0}
nav a::after{content:"";position:absolute;left:0;bottom:-2px;height:2px;width:100%;background:var(--brand);transform:scaleX(0);transform-origin:left;transition:transform .25s}
nav a:hover,nav a.on{color:var(--ink)}nav a:hover::after,nav a.on::after{transform:scaleX(1)}
h1,h2,h3{font-family:var(--display);line-height:1.05;margin:0;letter-spacing:-.02em}
h1{font-size:clamp(2.5rem,7vw,5.4rem);font-weight:800;max-width:17ch}
h2{font-size:clamp(1.9rem,4vw,3rem);font-weight:800;margin-bottom:1.2rem}
h3{font-size:1.25rem;font-weight:700;margin-bottom:.5rem;letter-spacing:-.01em}
p{margin:0 0 1rem;max-width:62ch}
section{padding:clamp(3rem,8vw,6rem) 0}
.hero{padding-top:clamp(2.5rem,6vw,5rem)}
.lead{font-size:1.2rem;color:var(--muted);margin-top:1.4rem;max-width:54ch}
.wave{display:inline-block;transform-origin:70% 70%;animation:wave 2.2s 1s 2}
@keyframes wave{0%,60%,100%{transform:rotate(0)}10%,30%{transform:rotate(14deg)}20%,40%{transform:rotate(-8deg)}50%{transform:rotate(10deg)}}
.btn{position:relative;overflow:hidden;display:inline-block;padding:.8rem 1.3rem;border-radius:var(--radius);background:var(--brand);color:#fff;font:600 1rem var(--body);text-decoration:none;border:2px solid var(--brand);cursor:pointer;transition:transform .15s,box-shadow .2s}
.btn:hover{transform:translateY(-2px);box-shadow:0 8px 18px -8px var(--brand)}.btn:active{transform:scale(.97)}
.btn.ghost{background:transparent;color:var(--ink);border-color:var(--ink);box-shadow:none}
.btn.ghost:hover{background:var(--ink);color:#fff}
.rip{position:absolute;border-radius:50%;background:rgba(255,255,255,.45);transform:scale(0);animation:rip .6s ease-out forwards;pointer-events:none}
@keyframes rip{to{transform:scale(4);opacity:0}}
.cta-row{display:flex;gap:.8rem;flex-wrap:wrap;margin-top:1.8rem}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:1rem;margin-top:3rem}
.stat{border-top:2px solid var(--ink);padding-top:.7rem}
.stat b{display:block;font:800 clamp(2rem,4vw,2.8rem)/1 var(--display)}
.stat span{font-size:.92rem;color:var(--muted)}
.lab{margin-top:3rem;display:grid;grid-template-columns:1fr 1fr;gap:1.2rem;background:var(--ink);color:#EAF3EE;border-radius:calc(var(--radius) + 10px);padding:clamp(1.2rem,3vw,2rem)}
.lab h2{font-size:1.5rem;color:#fff;margin-bottom:.4rem}.lab p{color:#B9CCC2;font-size:.98rem}
.ctrl{display:grid;gap:1rem;margin-top:1rem}.ctrl label{font-size:.9rem;font-weight:600;display:block;margin-bottom:.4rem}
.sw{display:flex;gap:.6rem;flex-wrap:wrap}
.sw button{width:2.4rem;height:2.4rem;border-radius:50%;border:3px solid transparent;cursor:pointer;padding:0;transition:transform .2s}
.sw button:hover{transform:scale(1.15)}.sw button[aria-pressed="true"]{border-color:#fff;box-shadow:0 0 0 2px var(--ink) inset}
input[type=range]{width:100%;accent-color:var(--sun)}
.preview{background:var(--bg);color:var(--ink);border-radius:var(--radius);padding:1.2rem;display:grid;gap:.9rem;align-content:center}
.pv-card{background:#fff;border:1px solid var(--line);border-radius:var(--radius);padding:1rem}
.pv-card strong{font:700 1.1rem var(--display)}
.pv-input{width:100%;padding:.7rem .9rem;border:2px solid var(--line);border-radius:var(--radius);font:inherit;background:#fff;transition:border-color .2s,box-shadow .2s}
.pv-input:focus{border-color:var(--brand);box-shadow:0 0 0 4px var(--soft);outline:none}
.pv-tag{display:inline-block;background:var(--soft);padding:.15rem .7rem;border-radius:calc(var(--radius)*4);font-size:.85rem;font-weight:600}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(min(100%,300px),1fr));gap:1.2rem}
.card{position:relative;background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:1.5rem;transition:transform .25s,box-shadow .25s,border-color .25s;--x:50%;--y:50%}
.card::before{content:"";position:absolute;inset:0;border-radius:inherit;background:radial-gradient(260px circle at var(--x) var(--y),var(--soft),transparent 70%);opacity:0;transition:opacity .25s;pointer-events:none}
.card:hover{transform:translateY(-4px);border-color:var(--brand);box-shadow:0 14px 28px -18px rgba(18,33,26,.5)}.card:hover::before{opacity:1}
.card>*{position:relative}.card p:last-child{margin-bottom:0}
.split{display:grid;grid-template-columns:.8fr 1.2fr;gap:clamp(1.5rem,5vw,4rem);align-items:start}
.band{background:var(--soft);border-block:1px solid var(--line)}
.proj{border-top:2px solid var(--ink);padding:1.5rem 0;display:grid;grid-template-columns:.7fr 1.3fr;gap:1.5rem}
.proj:last-child{border-bottom:2px solid var(--ink)}.proj h3{margin:0}
.meta{color:var(--muted);font-size:.92rem}
.result{display:inline-block;background:var(--ink);color:#fff;border-radius:99px;padding:.2rem .85rem;font-weight:600;font-size:.92rem;margin-bottom:.8rem}
.pills{display:flex;flex-wrap:wrap;gap:.5rem;margin:.6rem 0 0;padding:0;list-style:none}
.pills li{border:1px solid var(--ink);border-radius:99px;padding:.15rem .75rem;font-size:.88rem;font-weight:500;transition:background .2s,color .2s}
.pills li:hover{background:var(--ink);color:#fff}
.link{display:inline-block;margin-top:.8rem;font-weight:600;text-decoration:none;border-bottom:2px solid var(--brand)}
.link:hover{background:var(--soft)}
.link span{display:inline-block;transition:transform .2s}.link:hover span{transform:translate(3px,-3px)}
.stack{display:grid;gap:1.1rem}
.stack div{display:grid;grid-template-columns:9rem 1fr;gap:1rem;padding-bottom:1.1rem;border-bottom:1px solid var(--line)}
.stack div:last-child{border:0}.stack b{font:700 1.05rem var(--display)}
.joy{background:var(--sun);border-radius:calc(var(--radius) + 14px);padding:clamp(1.5rem,5vw,3.5rem);text-align:left;position:relative;overflow:hidden}
.joy p{max-width:56ch}.joy .btn{background:var(--ink);border-color:var(--ink)}
.bit{position:fixed;width:10px;height:14px;pointer-events:none;z-index:30;animation:fall 1.4s ease-out forwards}
@keyframes fall{to{transform:translate(var(--dx),var(--dy)) rotate(var(--r));opacity:0}}
footer{padding:3rem 0 4rem}footer .big{font:800 clamp(2rem,5vw,3.6rem)/1.05 var(--display);letter-spacing:-.02em;margin-bottom:1.4rem;max-width:20ch}
footer small{display:block;margin-top:2.5rem;color:var(--muted)}
#toast{position:fixed;left:50%;bottom:1.5rem;transform:translate(-50%,120%);background:var(--ink);color:#fff;padding:.7rem 1.2rem;border-radius:99px;z-index:40;transition:transform .35s cubic-bezier(.2,.9,.3,1.2);font-weight:500}
#toast.show{transform:translate(-50%,0)}
.rev{opacity:0;transform:translateY(16px);transition:opacity .6s,transform .6s}.rev.in{opacity:1;transform:none}
@media (max-width:820px){.lab,.split,.proj{grid-template-columns:1fr}.stack div{grid-template-columns:1fr;gap:.2rem}nav{font-size:.86rem;gap:.7rem}.logo span{display:none}}
@media (prefers-reduced-motion:reduce){*,*::before{transition:none!important;animation:none!important}.rev{opacity:1;transform:none}html{scroll-behavior:auto}}
</style>
</head>
<body>
<div id="bar"></div>
<header class="top"><div class="wrap">
<a class="logo" href="#top"><i>PA</i><span>Philomina Agba</span></a>
<nav aria-label="Sections"><a href="#work">Work</a><a href="#how">How I work</a><a href="#system">Design systems</a><a href="#joy">Joy</a><a href="#contact">Contact</a></nav>
</div></header>

<main id="top">
<section class="hero"><div class="wrap">
<h1>I turn complex workflows into products people finish.</h1>
<p class="lead"><span class="wave" aria-hidden="true">👋</span> Hi MailerLite, I'm Philomina, a Senior Product Designer with 6+ years across SaaS, FinTech, Healthcare and E-commerce. This page is my application, built the way I build products: clear, responsive and a little delightful.</p>
<div class="cta-row"><a class="btn" href="#work">See my results</a><button class="btn ghost" id="copy" type="button" data-email="philominaagba2@gmail.com">Copy my email</button></div>

<div class="stats">
<div class="stat"><b data-n="6" data-s="+">0</b><span>years designing products</span></div>
<div class="stat"><b data-n="20" data-s="+">0</b><span>client engagements led</span></div>
<div class="stat"><b data-n="45" data-s="%">0</b><span>checkout completion lift on Habitual</span></div>
<div class="stat"><b data-n="20" data-s="+">0</b><span>designers mentored</span></div>
</div>

<div class="lab" aria-labelledby="lab-title">
<div><h2 id="lab-title">Try a design system</h2>
<p>Two tokens drive every component here. Change them and watch the whole preview follow. That is why I build systems.</p>
<div class="ctrl">
<div><label id="l-accent">Brand color</label><div class="sw" role="group" aria-labelledby="l-accent" id="swatches"></div></div>
<div><label for="radius">Corner radius: <output id="rv">14</output>px</label><input id="radius" type="range" min="0" max="28" value="14"></div>
</div></div>
<div class="preview" aria-live="polite">
<div class="pv-card"><span class="pv-tag">Draft</span><br><strong>Welcome series</strong><p style="margin:.3rem 0 0;font-size:.95rem;color:var(--muted)">3 emails, sent after sign-up.</p></div>
<input class="pv-input" aria-label="Email subject" value="Welcome aboard">
<button class="btn" type="button">Publish campaign</button>
</div></div>
</div></section>

<section id="work" class="band"><div class="wrap">
<h2 class="rev">Work and results</h2>
<article class="proj rev"><div><h3>MedSync</h3><p class="meta">Healthcare platform · Sole product designer</p></div>
<div><span class="result">Onboarding completion 60% → 80%</span>
<p>Patients were dropping off at login and onboarding. I ran 10 user interviews and usability tests, found the friction points and redesigned the flow. I owned everything from research and information architecture to high-fidelity UI, prototyping and developer handoff, and designed to WCAG 2.1 AA.</p>
<ul class="pills"><li>User interviews</li><li>Usability testing</li><li>WCAG 2.1 AA</li><li>Mobile</li></ul>
<a class="link" href="https://dribbble.com/shots/27611678-MedSync-End-to-End-Healthcare-Mobile-App-UX-UI-Case-Study" target="_blank" rel="noopener">View case study <span>↗</span></a></div></article>

<article class="proj rev"><div><h3>Habitual</h3><p class="meta">Mobile e-commerce app · Senior product designer</p></div>
<div><span class="result">Checkout 7 screens → 4, completion +45%</span>
<p>Shoppers struggled to discover, compare and buy. I ran research and competitor analysis, then designed user flows, information architecture, wireframes and prototypes. The completion lift was measured in usability testing, and I prepared developer-ready specs.</p>
<ul class="pills"><li>Mobile app</li><li>User flows</li><li>Prototyping</li><li>Handoff</li></ul>
<a class="link" href="https://dribbble.com/shots/27384017-Habitual-E-Commerce-Mobile-App-Case-Study" target="_blank" rel="noopener">View case study <span>↗</span></a></div></article>

<article class="proj rev"><div><h3>Nexora</h3><p class="meta">SaaS financial analytics dashboard</p></div>
<div><span class="result">Workflow visibility for business users</span>
<p>A dashboard focused on information architecture and clarity, with reusable components, responsive layouts and interactive prototypes built to support scalable development.</p>
<ul class="pills"><li>SaaS</li><li>Dashboards</li><li>Components</li><li>Responsive</li></ul>
<a class="link" href="https://dribbble.com/shots/27383640-Nexora-SaaS-Financial-Investment-Analytics-Dashboard" target="_blank" rel="noopener">View case study <span>↗</span></a></div></article>

<article class="proj rev"><div><h3>NanoVMs redesign</h3><p class="meta">Website concept · UX audit</p></div>
<div><span class="result">Clearer navigation for technical users</span>
<p>The existing site had navigation and information-hierarchy problems. I audited the UX, analyzed user journeys, restructured navigation and content, and documented the design rationale.</p>
<ul class="pills"><li>UX audit</li><li>Information architecture</li><li>Responsive</li></ul></div></article>
</div></section>

<section id="how"><div class="wrap split">
<div class="rev"><h2>How I work with others</h2><p>Design only counts when it ships well. These are my habits across 20+ engagements.</p></div>
<div class="grid">
<div class="card rev"><h3>With engineers</h3><p>I bring them in before designs are final, then hand off with developer-ready specs and reusable components. I stay for implementation review so what ships matches what was designed. I work in Figma, FigJam and Miro, inside Agile and Scrum.</p></div>
<div class="card rev"><h3>With product managers</h3><p>We turn business goals into clear problems, then I run discovery workshops and propose options with trade-offs. Jira and Notion keep scope and decisions visible, and design reviews keep everyone aligned.</p></div>
<div class="card rev"><h3>With users</h3><p>I use stakeholder interviews, user interviews, competitor analysis, heuristic evaluations, UX audits, journey mapping, usability testing and A/B testing. I validate with prototypes before development to avoid costly late revisions.</p></div>
<div class="card rev"><h3>With AI</h3><p>I use ChatGPT, Claude, Gemini and Relume to synthesize research, draft UX copy and explore early concepts quickly. Every output is checked against real user evidence. AI speeds up the work, but users make the decisions.</p></div>
</div></div></section>

<section id="system" class="band"><div class="wrap">
<h2 class="rev">Design systems: yes, I build and maintain them</h2>
<p class="rev">At Techpem I maintain design systems and component libraries across concurrent client products, which reduces inconsistency and speeds up handoff. At Ohayo I kept a shared, documented UI library across several projects at once.</p>
<div class="stack">
<div class="rev"><b>Foundations</b><span>Color, type, spacing and radius defined once and reused everywhere, like the live demo at the top of this page.</span></div>
<div class="rev"><b>Components</b><span>Reusable components with states, documentation and WCAG accessibility in mind.</span></div>
<div class="rev"><b>Handoff</b><span>Specs and libraries that engineers can build from, so design and code stay consistent.</span></div>
<div class="rev"><b>Mobile and responsive</b><span>I design for web and mobile, from Habitual and MedSync on phones to Nexora dashboards on large screens. I'm keen to go deeper into PWA patterns like installability and offline states.</span></div>
</div></div></section>

<section id="joy"><div class="wrap"><div class="joy rev">
<h2>What sparks joy for me</h2>
<p>The quiet moment in a usability test when someone stops hesitating and just gets it. And watching designers I've mentored (20+ so far) land their first great portfolio piece.</p>
<p>Want to share the feeling?</p>
<button class="btn" id="spark" type="button">Spark some joy ✨</button>
</div></div></section>
</main>

<footer id="contact"><div class="wrap">
<div class="big">Let's build something people enjoy using.</div>
<div class="cta-row">
<a class="btn" href="mailto:philominaagba2@gmail.com">philominaagba2@gmail.com</a>
<a class="btn ghost" href="https://dribbble.com/philomina-agba" target="_blank" rel="noopener">Dribbble</a>
<a class="btn ghost" href="https://www.behance.net/philominaagba2" target="_blank" rel="noopener">Behance</a>
</div>
<small>Made in Abuja, Nigeria for my MailerLite Product Designer application.</small>
</div></footer>
<div id="toast" role="status" aria-live="polite"></div>

<script>
(function(){
var d=document,root=d.documentElement,reduce=matchMedia('(prefers-reduced-motion:reduce)').matches;
function toast(t){var e=d.getElementById('toast');e.textContent=t;e.classList.add('show');clearTimeout(toast.t);toast.t=setTimeout(function(){e.classList.remove('show')},2200)}
/* token playground */
var box=d.getElementById('swatches');
[['Green','#0BA55C'],['Violet','#6B4EFF'],['Coral','#E8503A'],['Blue','#1877F2'],['Ink','#12211A']].forEach(function(c,i){
var b=d.createElement('button');b.type='button';b.style.background=c[1];b.setAttribute('aria-label',c[0]);b.setAttribute('aria-pressed',i===0);
b.onclick=function(){root.style.setProperty('--brand',c[1]);root.style.setProperty('--soft',c[1]+'22');[].forEach.call(box.children,function(x){x.setAttribute('aria-pressed',x===b)});toast('Brand color: '+c[0])};
box.appendChild(b)});
var r=d.getElementById('radius'),o=d.getElementById('rv');
r.oninput=function(){root.style.setProperty('--radius',r.value+'px');o.textContent=r.value};
/* ripple */
d.addEventListener('click',function(e){var b=e.target.closest('.btn');if(!b||reduce)return;var s=b.getBoundingClientRect(),z=Math.max(s.width,s.height)/2,p=d.createElement('span');
p.className='rip';p.style.cssText='width:'+z+'px;height:'+z+'px;left:'+(e.clientX-s.left-z/2)+'px;top:'+(e.clientY-s.top-z/2)+'px';b.appendChild(p);setTimeout(function(){p.remove()},600)});
/* card glow */
[].forEach.call(d.querySelectorAll('.card'),function(c){c.addEventListener('pointermove',function(e){var s=c.getBoundingClientRect();c.style.setProperty('--x',(e.clientX-s.left)+'px');c.style.setProperty('--y',(e.clientY-s.top)+'px')})});
/* copy email */
d.getElementById('copy').onclick=function(){var m=this.dataset.email;(navigator.clipboard?navigator.clipboard.writeText(m):Promise.reject()).then(function(){toast('Email copied. Talk soon!')},function(){toast(m)})};
/* scroll progress + active nav */
var bar=d.getElementById('bar'),links=[].slice.call(d.querySelectorAll('nav a'));
addEventListener('scroll',function(){var h=root.scrollHeight-innerHeight;bar.style.width=(h>0?scrollY/h*100:0)+'%'},{passive:true});
var secs=links.map(function(a){return d.querySelector(a.getAttribute('href'))});
if('IntersectionObserver' in window){
new IntersectionObserver(function(es){es.forEach(function(e){if(e.isIntersecting){links.forEach(function(a){a.classList.toggle('on',a.getAttribute('href')==='#'+e.target.id)})}})},{rootMargin:'-45% 0px -50% 0px'}).observe&&secs.forEach(function(s,i){if(!s)return;new IntersectionObserver(function(es){if(es[0].isIntersecting)links.forEach(function(a,j){a.classList.toggle('on',i===j)})},{rootMargin:'-45% 0px -50% 0px'}).observe(s)});
/* reveal */
var io=new IntersectionObserver(function(es){es.forEach(function(e){if(e.isIntersecting){e.target.classList.add('in');io.unobserve(e.target)}})},{threshold:.15});
[].forEach.call(d.querySelectorAll('.rev'),function(n,i){n.style.transitionDelay=(i%4)*70+'ms';io.observe(n)});
/* count up */
var co=new IntersectionObserver(function(es){es.forEach(function(e){if(!e.isIntersecting)return;co.unobserve(e.target);var n=+e.target.dataset.n,s=e.target.dataset.s,t=0;
if(reduce){e.target.textContent=n+s;return}
var iv=setInterval(function(){t+=1;var v=Math.round(n*(1-Math.pow(1-t/40,3)));e.target.textContent=v+s;if(t>=40)clearInterval(iv)},25)})},{threshold:.6});
[].forEach.call(d.querySelectorAll('[data-n]'),function(n){co.observe(n)});
}else{[].forEach.call(d.querySelectorAll('.rev'),function(n){n.classList.add('in')});[].forEach.call(d.querySelectorAll('[data-n]'),function(n){n.textContent=n.dataset.n+n.dataset.s})}
/* confetti */
d.getElementById('spark').onclick=function(e){toast('That feeling. Thanks for reading! 💚');if(reduce)return;
var cols=['#0BA55C','#FFC93C','#6B4EFF','#E8503A','#1877F2'],s=this.getBoundingClientRect(),x=s.left+s.width/2,y=s.top+s.height/2;
for(var i=0;i<36;i++){var b=d.createElement('i');b.className='bit';b.style.cssText='left:'+x+'px;top:'+y+'px;background:'+cols[i%5]+';--dx:'+((Math.random()-.5)*420)+'px;--dy:'+(-80-Math.random()*260)+'px;--r:'+(Math.random()*720)+'deg';d.body.appendChild(b);(function(n){setTimeout(function(){n.remove()},1400)})(b)}};
})();
</script>
</body>
</html>
