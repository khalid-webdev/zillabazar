<script setup>

</script>

<template>

<footer>

  <!-- ① Marquee -->
  <div class="marquee-wrap" aria-hidden="true">
    <div class="marquee-inner">
      <span>Free Shipping Over $80</span><span class="sep">✦</span>
      <span>30-Day Easy Returns</span><span class="sep">✦</span>
      <span>New Drops Every Friday</span><span class="sep">✦</span>
      <span>Sustainably Crafted</span><span class="sep">✦</span>
      <span>Members Save 20%</span><span class="sep">✦</span>
      <span>Carbon Neutral Shipping</span><span class="sep">✦</span>
      <!-- duplicate for seamless loop -->
      <span>Free Shipping Over $80</span><span class="sep">✦</span>
      <span>30-Day Easy Returns</span><span class="sep">✦</span>
      <span>New Drops Every Friday</span><span class="sep">✦</span>
      <span>Sustainably Crafted</span><span class="sep">✦</span>
      <span>Members Save 20%</span><span class="sep">✦</span>
      <span>Carbon Neutral Shipping</span><span class="sep">✦</span>
    </div>
  </div>

  <!-- ② Newsletter Band -->
  <div class="nl-band">
    <div class="nl-text">
      <h2 class="nl-headline">
        Stay         <em>ahead</em> of the season.<br>

      </h2>
      <p class="nl-sub">Weekly curations, early access to new arrivals, and stories from the makers behind every piece.</p>
    </div>

    <div class="nl-form-wrap">
      <label class="nl-form-label" for="email-sub">Your email address</label>
      <form class="nl-form" action="#" method="post">
        <input type="email" id="email-sub" name="email" placeholder="hello@yourdomain.com" autocomplete="email" required/>
        <button type="submit">Subscribe</button>
      </form>
    </div>
  </div>

  <!-- ③ Main Grid -->
  <div class="footer-main">

    <!-- Brand -->
    <div class="brand-col">
      <div class="logo">Zillabazar<span class="logo-accent"></span></div>
      <div class="brand-sub">Rooted in Nature</div>
      <p class="brand-desc">
        Clothing inspired by land and light. Every piece is ethically made using natural fibres, low-impact dyes, and the hands of independent craftspeople.
      </p>

      <div class="trust">
        <div class="trust-row">
          <svg viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg>
          Free returns within 30 days
        </div>
        <div class="trust-row">
          <svg viewBox="0 0 24 24"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
          SSL-secured checkout
        </div>
        <div class="trust-row">
          <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 8v4l3 3"/></svg>
          Dispatched in 2–4 business days
        </div>
        <div class="trust-row">
          <svg viewBox="0 0 24 24"><path d="M3.5 18.5l6-6 4 4L21 7"/></svg>
          Carbon-neutral delivery
        </div>
      </div>

      <div class="socials">
        <a class="soc" href="#" aria-label="Instagram">
          <svg viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
        </a>
        <a class="soc" href="#" aria-label="Pinterest">
          <svg viewBox="0 0 24 24"><path d="M12 0C5.373 0 0 5.373 0 12c0 5.084 3.163 9.426 7.627 11.174-.105-.949-.2-2.405.042-3.441.218-.937 1.407-5.965 1.407-5.965s-.359-.719-.359-1.782c0-1.668.967-2.914 2.171-2.914 1.023 0 1.518.769 1.518 1.69 0 1.029-.655 2.568-.994 3.995-.283 1.194.599 2.169 1.777 2.169 2.133 0 3.772-2.249 3.772-5.495 0-2.873-2.064-4.882-5.012-4.882-3.414 0-5.418 2.561-5.418 5.207 0 1.031.397 2.138.893 2.738a.36.36 0 0 1 .083.345l-.333 1.36c-.053.22-.174.267-.402.161-1.499-.698-2.436-2.889-2.436-4.649 0-3.785 2.75-7.262 7.929-7.262 4.163 0 7.398 2.967 7.398 6.931 0 4.136-2.607 7.464-6.227 7.464-1.216 0-2.359-.632-2.75-1.378l-.748 2.853c-.271 1.043-1.002 2.35-1.492 3.146C9.57 23.812 10.763 24 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0z"/></svg>
        </a>
        <a class="soc" href="#" aria-label="TikTok">
          <svg viewBox="0 0 24 24"><path d="M19.59 6.69a4.83 4.83 0 0 1-3.77-4.25V2h-3.45v13.67a2.89 2.89 0 0 1-2.88 2.5 2.89 2.89 0 0 1-2.89-2.89 2.89 2.89 0 0 1 2.89-2.89c.28 0 .54.04.79.1V9.01a6.27 6.27 0 0 0-.79-.05 6.34 6.34 0 0 0-6.34 6.34 6.34 6.34 0 0 0 6.34 6.34 6.34 6.34 0 0 0 6.33-6.34V8.69a8.18 8.18 0 0 0 4.78 1.52V6.75a4.85 4.85 0 0 1-1.01-.06z"/></svg>
        </a>
        <a class="soc" href="#" aria-label="YouTube">
          <svg viewBox="0 0 24 24"><path d="M23.495 6.205a3.007 3.007 0 0 0-2.088-2.088c-1.87-.501-9.396-.501-9.396-.501s-7.507-.01-9.396.501A3.007 3.007 0 0 0 .527 6.205a31.247 31.247 0 0 0-.522 5.805 31.247 31.247 0 0 0 .522 5.783 3.007 3.007 0 0 0 2.088 2.088c1.868.502 9.396.502 9.396.502s7.506 0 9.396-.502a3.007 3.007 0 0 0 2.088-2.088 31.247 31.247 0 0 0 .5-5.783 31.247 31.247 0 0 0-.5-5.805zM9.609 15.601V8.408l6.264 3.602z"/></svg>
        </a>
      </div>
    </div>

    <!-- Shop -->
    <nav class="nav-col" aria-label="Shop">
      <h4>Shop</h4>
      <ul>
        <li><a href="#">New Arrivals<span class="chip chip-new">New</span><span class="arr">→</span></a></li>
        <li><a href="#">Women<span class="arr">→</span></a></li>
        <li><a href="#">Men<span class="arr">→</span></a></li>
        <li><a href="#">Accessories<span class="arr">→</span></a></li>
        <li><a href="#">Footwear<span class="arr">→</span></a></li>
        <li><a href="#">Homeware<span class="arr">→</span></a></li>
        <li><a href="#">Sale<span class="chip chip-sale">Sale</span><span class="arr">→</span></a></li>
        <li><a href="#">Gift Cards<span class="arr">→</span></a></li>
      </ul>
    </nav>

    <!-- Help -->
    <nav class="nav-col" aria-label="Customer Care">
      <h4>Customer Care</h4>
      <ul>
        <li><a href="#">Track My Order<span class="arr">→</span></a></li>
        <li><a href="#">Returns & Exchanges<span class="arr">→</span></a></li>
        <li><a href="#">Shipping Info<span class="arr">→</span></a></li>
        <li><a href="#">Size Guide<span class="arr">→</span></a></li>
        <li><a href="#">FAQs<span class="arr">→</span></a></li>
        <li><a href="#">Contact Us<span class="arr">→</span></a></li>
        <li><a href="#">Live Chat<span class="arr">→</span></a></li>
      </ul>
    </nav>

    <!-- Company -->
    <nav class="nav-col" aria-label="Company">
      <h4>Company</h4>
      <ul>
        <li><a href="#">Our Story<span class="arr">→</span></a></li>
        <li><a href="#">Sustainability<span class="arr">→</span></a></li>
        <li><a href="#">Press & Media<span class="arr">→</span></a></li>
        <li><a href="#">Careers<span class="arr">→</span></a></li>
        <li><a href="#">Affiliates<span class="arr">→</span></a></li>
        <li><a href="#">Store Locator<span class="arr">→</span></a></li>
        <li><a href="#">Privacy Policy<span class="arr">→</span></a></li>
      </ul>
    </nav>

  </div>

  <!-- ornamental divider -->
  <div class="ornament">✦ &nbsp; ✦ &nbsp; ✦</div>

  <!-- ④ Bottom Bar -->
  <div class="footer-bottom">
    <div class="pay-row">
      <span class="pay-lbl">We accept</span>
      <span class="pay-pill">Visa</span>
      <span class="pay-pill">Mastercard</span>
      <span class="pay-pill">PayPal</span>
      <span class="pay-pill">Apple Pay</span>
      <span class="pay-pill">Google Pay</span>
    </div>
    <div class="bottom-right">
      <div class="legal">
        <a href="#">Terms</a>
        <a href="#">Privacy</a>
        <a href="#">Cookies</a>
        <a href="#">Accessibility</a>
      </div>
      <div class="copy">© 2025 ZILLABAZAR Store. All rights reserved.</div>
    </div>
  </div>

</footer>
</template>

<style scoped>

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

:root {
  --bg:        #f7f3ee;
  --surface:   #efe9e0;
  --ink:       #ff8c00;
  --ink2:      #3b2f1e;
  --muted:     #9a8a76;
  --line:      #f30c0c;
  --moss:      #3d5c3a;
  --moss-lt:   #527a4e;
  --sand:      #c4a87a;
  --sand-lt:   #dcc49a;
  --white:     #ffffff;
  --ff-disp:   'Fraunces', Georgia, serif;
  --ff-body:   'Syne', sans-serif;
}

html { scroll-behavior: smooth; }

body {
  background: #e8e2d8;
  font-family: var(--ff-body);
  color: var(--ink);
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}

/* ════════════════════════════════
   MARQUEE  — pure CSS
════════════════════════════════ */
.marquee-wrap {
  background: var(--moss);
  overflow: hidden;
  padding: 11px 0;
  border-top: 1px solid #2d4429;
  border-bottom: 2px solid var(--sand);
}
.marquee-inner {
  display: flex;
  width: max-content;
  animation: slide 30s linear infinite;
}
.marquee-inner:hover { animation-play-state: paused; }

.marquee-inner span {
  font-family: var(--ff-body);
  font-size: 1.2rem;
  font-weight: 700;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: #d4edcc;
  padding: 0 28px;
  white-space: nowrap;
}
.marquee-inner span.sep {
  color: var(--sand);
  padding: 0 4px;
  letter-spacing: 0;
  font-size: .85rem;
}
@keyframes slide {
  from { transform: translateX(0); }
  to   { transform: translateX(-50%); }
}

/* ════════════════════════════════
   NEWSLETTER BAND
════════════════════════════════ */
.nl-band {
  background: var(--secondary);
  padding: 70px 64px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 48px;
  flex-wrap: wrap;
  position: relative;
  overflow: hidden;
}
.nl-band::before {
  content: '';
  position: absolute;
  width: 520px; height: 520px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(61,92,58,0.35) 0%, transparent 70%);
  top: -160px; right: -80px;
  pointer-events: none;
}
.nl-band::after {
  content: '';
  position: absolute;
  width: 300px; height: 300px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(196,168,122,0.12) 0%, transparent 70%);
  bottom: -100px; left: 40px;
  pointer-events: none;
}

.nl-text { position: relative; z-index: 1; }

.nl-eyebrow {
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.28em;
  text-transform: uppercase;
  color: var(--line);
  margin-bottom: 16px;
  display: flex;
  align-items: center;
  gap: 12px;
}
.nl-eyebrow::before {
  content: '';
  display: block;
  width: 30px; height: 1px;
  background: var(--sand);
  opacity: 0.6;
}

.nl-headline {
  font-family: var(--ff-disp);
  font-size: clamp(2.6rem, 5vw, 5rem);
  font-weight: 300;
  line-height: 1.0;
  letter-spacing: -0.02em;
  color:var(--grayFont);
}
.nl-headline em {
  font-style: italic;
  font-weight: 600;
  color:  var(--primary);
}

.nl-sub {
  margin-top: 14px;
  font-size: 1.4rem;
  font-weight: 300;
  color: #afafaf;
  letter-spacing: 0.04em;
  line-height: 1.7;
  max-width: 320px;
}

/* email form — CSS-only focus/valid state */
.nl-form-wrap { position: relative; z-index: 1; flex-shrink: 0; }

.nl-form-label {
  display: block;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: #afafaf;
  margin-bottom: 10px;
}

.nl-form {
  display: flex;
  border: 1px solid #afafaf;
  width: 380px;
  max-width: 100%;
  transition: border-color 0.3s;
}
.nl-form:focus-within { border-color: white; }

.nl-form input[type="email"] {
  flex: 1;
  min-width: 0;
  background: var(--grayFont);
  border: none;
  padding: 15px 18px;
  font-family: var(--ff-body);
  font-size: 1.5rem;
  font-weight: 300;
  color: var(--secondary);
  letter-spacing: 0.06em;
  outline: none;
}
.nl-form input[type="email"]::placeholder { color: #3a2a18; }

.nl-form button[type="submit"] {
  background: var(--moss);
  border: none;
  padding: 15px 22px;
  cursor: pointer;
  font-family: var(--ff-body);
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: #d4edcc;
  white-space: nowrap;
  transition: background 0.25s;
  flex-shrink: 0;
}
.nl-form button[type="submit"]:hover { background: var(--moss-lt); }
.nl-form button[type="submit"]:active { transform: scale(0.97); }

/* ════════════════════════════════
   MAIN GRID
════════════════════════════════ */
footer{
background: var(--paragraph);
}
.footer-main {
  background: var(--grayFont);
  padding: 72px 64px 56px;
  display: grid;
  grid-template-columns: 1.9fr 1fr 1fr 1fr;
  gap: 52px 40px;
  border-top: 3px solid var(--ink);
}

/* ── Brand column ── */
.brand-col .logo {
  font-family: var(--ff-disp);
  font-size: 3.8rem;
  font-weight: 900;
  letter-spacing: 0.06em;
  color: var(--ink);
  text-transform: uppercase;
  line-height: 1;
  position: relative;
  display: inline-block;
}
.logo-accent {
  display: inline-block;
  width: 8px; height: 8px;
  background: var(--moss);
  border-radius: 50%;
  margin-left: 4px;
  vertical-align: super;
  animation: blink 3s ease-in-out infinite;
}
@keyframes blink {
  0%,100% { opacity: 1; transform: scale(1); }
  50%      { opacity: 0.4; transform: scale(0.7); }
}

.brand-sub {
  margin-top: 8px;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.3em;
  text-transform: uppercase;
  color: var(--muted);
}

.brand-desc {
  margin-top: 20px;
  font-size: 1.5rem;
  font-weight: 300;
  line-height: 1.85;
  color: var(--ink2);
  max-width: 270px;
}

/* trust badges */
.trust {
  margin-top: 28px;
  display: flex;
  flex-direction: column;
  gap: 9px;
}
.trust-row {
  display: flex;
  align-items: center;
  gap: 9px;
  font-size: 1.3rem;
  font-weight: 400;
  color: var(--ink2);
  letter-spacing: 0.02em;
}
.trust-row svg {
  width: 14px; height: 14px;
  flex-shrink: 0;
  stroke: var(--moss);
  fill: none;
  stroke-width: 2.2;
  stroke-linecap: round;
  stroke-linejoin: round;
}

/* socials */
.socials {
  margin-top: 28px;
  display: flex;
  gap: 9px;
  flex-wrap: wrap;
}
.soc {
  width: 38px; height: 38px;
  border: 1px solid var(--line);
  display: flex; align-items: center; justify-content: center;
  text-decoration: none;
  color: var(--muted);
  transition: border-color 0.22s, color 0.22s, background 0.22s, transform 0.2s;
}
.soc:hover {
  border-color: var(--moss);
  color: var(--moss);
  background: rgba(61,92,58,0.07);
  transform: translateY(-3px);
}
.soc svg { width: 15px; height: 15px; fill: currentColor; }

/* ── Nav columns ── */
.nav-col h4 {
  font-family: var(--ff-body);
  font-size: 1.1rem;
  font-weight: 700;
  letter-spacing: 0.28em;
  text-transform: uppercase;
  color: var(--moss);
  margin-bottom: 22px;
  padding-bottom: 12px;
  border-bottom: 1px solid var(--line);
}

.nav-col ul { list-style: none; }
.nav-col ul li { margin-bottom: 12px; }

.nav-col ul li a {
  text-decoration: none;
  font-size: 1.45rem;
  font-weight: 400;
  color: var(--ink2);
  letter-spacing: 0.03em;
  display: inline-flex;
  align-items: center;
  gap: 0px;
  transition: color 0.2s, gap 0.22s, letter-spacing 0.22s;
}
.nav-col ul li a:hover {
  color: var(--moss);
  gap: 8px;
  letter-spacing: 0.06em;
}
.nav-col ul li a .arr {
  font-size: 1.2rem;
  opacity: 0;
  transform: translateX(-4px);
  transition: opacity 0.2s, transform 0.22s;
  color: var(--moss);
}
.nav-col ul li a:hover .arr { opacity: 1; transform: translateX(0); }

.chip {
  display: inline-block;
  font-size: .855rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  padding: 2px 7px;
  text-transform: uppercase;
  vertical-align: middle;
  margin-left: 6px;
  border-radius: 2px;
}
.chip-new { background: rgba(61,92,58,0.12); color: var(--moss); }
.chip-sale { background: rgba(196,80,50,0.12); color: #c45032; }

/* ════════════════════════════════
   BOTTOM BAR
════════════════════════════════ */
.footer-bottom {
  background: var(--surface);
  border-top: 1px solid var(--line);
  padding: 20px 64px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 16px;
}

.pay-row {
  display: flex;
  align-items: center;
  gap: 7px;
  flex-wrap: wrap;
}
.pay-lbl {
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--grayFont);
  margin-right: 6px;
}
.pay-pill {
  border: 1px solid var(--secondary);
  padding: 4px 11px;
  font-size: 0.96rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  color: var(--grayFont);
  text-transform: uppercase;
  border-radius: 2px;
  cursor: default;
  transition: border-color 0.2s, color 0.2s, transform 0.15s;
}
.pay-pill:hover { border-color: var(--primary); color: var(--primary); transform: translateY(-1px); }

.bottom-right {
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
}
.legal {
  display: flex;
  gap: 14px;
}
.legal a {
  font-size: 1.3rem;
  font-weight: 400;
  color: var(--grayFont);
  text-decoration: none;
  letter-spacing: 0.06em;
  transition: color 0.2s;
}
.legal a:hover { color: var(--ink2); }

.copy {
  font-size: 1.3rem;
  font-weight: 300;
  color: #c0b4a4;
  letter-spacing: 0.06em;
}

/* ════════════════════════════════
   DECORATIVE DIVIDER
════════════════════════════════ */
.ornament {
  text-align: center;
  background: var(--bg);
  padding: 10px 0 0;
  font-family: var(--ff-disp);
  font-size: 2.1rem;
  color: var(--primary);
  letter-spacing: 0.4em;
  line-height: 1;
  border-top: 1px solid var(--line);
}

/* ════════════════════════════════
   CSS ENTRANCE ANIMATIONS
════════════════════════════════ */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(24px); }
  to   { opacity: 1; transform: translateY(0); }
}

.nl-text    { animation: fadeUp 0.8s ease both; }
.nl-form-wrap { animation: fadeUp 0.8s 0.15s ease both; }
.brand-col  { animation: fadeUp 0.8s 0.05s ease both; }
.nav-col:nth-child(2) { animation: fadeUp 0.8s 0.15s ease both; }
.nav-col:nth-child(3) { animation: fadeUp 0.8s 0.25s ease both; }
.nav-col:nth-child(4) { animation: fadeUp 0.8s 0.35s ease both; }

/* ════════════════════════════════
   RESPONSIVE
════════════════════════════════ */
@media (max-width: 1000px) {
  .footer-main { grid-template-columns: 1fr 1fr; padding: 56px 40px 48px; }
  .nl-band { padding: 56px 40px; }
  .footer-bottom { padding: 20px 40px; }
}
@media (max-width: 600px) {
  .footer-main { grid-template-columns: 1fr; padding: 48px 24px 36px; }
  .nl-band { padding: 48px 24px; flex-direction: column; }
  .footer-bottom { padding: 20px 24px; flex-direction: column; align-items: flex-start; }
  .nl-form { width: 100%; }
}
</style>
