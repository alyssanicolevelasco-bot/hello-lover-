<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Monthsary, my lover!! :p</title>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&amp;family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400;1,500&amp;family=Caveat:wght@600;700&amp;display=swap" rel="stylesheet">
  <style>
    :root {
      --cream: #fff8f2;
      --paper: #fffdf9;
      --blush: #f6d9d4;
      --rose: #eab7b1;
      --burgundy: #641d32;
      --wine: #421321;
      --gold: #c99749;
      --ink: #4b2630;
      --pink-card: #fde8e9;
      --pink-pen: #e07a93;
    }

    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }

    body {
      width: 100%;
      min-height: 100vh;
      margin: 0;
      color: var(--ink);
      background: var(--cream);
      font-family: "DM Sans", sans-serif;
      overflow-x: hidden;
    }

    button, a, input, textarea { font: inherit; }

    .app-shell {
      width: 100%;
      min-height: 100vh;
      position: relative;
      isolation: isolate;
      overflow: hidden;
      padding: clamp(1rem, 4vw, 3rem);
      background-image: radial-gradient(rgba(100, 29, 50, .05) .7px, transparent .7px);
      background-size: 13px 13px;
    }

    .page-header {
      width: min(100%, 74rem);
      margin: 0 auto 1rem;
      display: flex;
      justify-content: center;
    }

    .brand-mark {
      display: inline-flex;
      align-items: center;
      gap: .5rem;
      color: var(--burgundy);
      font-family: "Playfair Display", serif;
      font-style: italic;
      font-size: .95rem;
    }

    .cover-main {
      width: min(100%, 74rem);
      margin: 0 auto;
    }

    .cover-card {
      position: relative;
      overflow: hidden;
      padding: clamp(1.5rem, 5vw, 4.25rem);
      border: 1px solid rgba(100, 29, 50, .15);
      border-radius: 2rem;
      box-shadow: 0 26px 70px rgba(91, 31, 46, .14);
      text-align: center;
      backdrop-filter: blur(9px);
    }

    .eyebrow {
      margin: 0;
      color: var(--gold);
      font-size: .72rem;
      font-weight: 700;
      letter-spacing: .2em;
      text-transform: uppercase;
    }

    .title {
      max-width: 48rem;
      margin: .75rem auto .55rem;
      color: var(--burgundy);
      font-family: "Playfair Display", serif;
      font-weight: 500;
      line-height: 1.03;
    }

    .subtitle {
      max-width: 36rem;
      margin: 0 auto;
      color: #6b3b47;
      line-height: 1.65;
    }

    .primary-button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: .65rem;
      min-height: 50px;
      margin-top: 1.6rem;
      padding: .84rem 1.35rem;
      border: 1px solid var(--burgundy);
      border-radius: 999px;
      box-shadow: 0 9px 20px rgba(100, 29, 50, .18);
      cursor: pointer;
      text-decoration: none;
      transition: transform .22s ease;
    }

    .primary-button:hover {
      transform: translateY(-3px);
    }

    .toc-section {
      max-width: 62rem;
      margin: clamp(2.5rem, 6vw, 4.5rem) auto 0;
    }

    .toc-heading {
      margin: 0;
      color: var(--burgundy);
      font-family: "Playfair Display", serif;
      font-size: 2rem;
      text-align: center;
    }

    .toc-helper {
      margin: .55rem auto 1.55rem;
      color: #704451;
      text-align: center;
    }

    .chapter-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1rem;
    }

    .chapter-link {
      display: flex;
      min-height: 140px;
      flex-direction: column;
      justify-content: space-between;
      padding: 1.15rem;
      border: 1px solid rgba(100, 29, 50, .15);
      border-radius: 1.35rem;
      color: var(--burgundy);
      text-decoration: none;
      transition: transform .22s ease;
      background: var(--paper);
    }

    .chapter-link:hover {
      transform: translateY(-4px);
    }

    .content-section {
      max-width: 62rem;
      margin: 4rem auto 0;
      padding: 2.5rem clamp(1rem, 4vw, 2.5rem);
      background: rgba(255, 253, 249, 0.95);
      border: 1px solid rgba(100, 29, 50, 0.15);
      border-radius: 1.8rem;
      box-shadow: 0 15px 40px rgba(91, 31, 46, 0.08);
      scroll-margin-top: 2rem;
    }

    .section-subtitle {
      color: var(--gold);
      font-weight: 700;
      text-transform: uppercase;
      font-size: 0.75rem;
      letter-spacing: 0.15rem;
      margin-bottom: 0.5rem;
    }

    /* POLAROID STYLING FOR CH 1 */
    .polaroid-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }

    .polaroid-card {
      background: white;
      padding: 1rem 1rem 1.5rem;
      border-radius: 0.5rem;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
      border: 1px solid #eaeaea;
      text-align: center;
      transform: rotate(-1.5deg);
      transition: transform 0.3s ease;
    }

    .polaroid-card:nth-child(even) {
      transform: rotate(2deg);
    }

    .polaroid-card:hover {
      transform: rotate(0deg) scale(1.02);
    }

    .polaroid-img-box {
      width: 100%;
      height: 260px;
      background: #f4f4f4;
      border-radius: 0.25rem;
      overflow: hidden;
      position: relative;
    }

    .polaroid-img-box img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    /* BUTTONS & MODALS */
    .btn-action {
      background: var(--burgundy);
      color: var(--cream);
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 999px;
      cursor: pointer;
      font-weight: 600;
      margin-top: 0.8rem;
      transition: all 0.2s ease;
    }

    .btn-action:hover {
      background: var(--wine);
      transform: translateY(-2px);
    }

    .letter-container {
      margin-top: 1.5rem;
      padding: 1.5rem;
      background: var(--paper);
      border: 1px dashed rgba(100, 29, 50, 0.25);
      border-radius: 1rem;
      display: none;
      animation: fadeIn 0.4s ease;
    }

    .letter-container.active {
      display: block;
    }

    .quiz-option {
      display: block;
      width: 100%;
      text-align: left;
      padding: 0.8rem 1rem;
      margin: 0.5rem 0;
      background: var(--paper);
      border: 1px solid rgba(100, 29, 50, 0.18);
      border-radius: 0.75rem;
      cursor: pointer;
    }

    .quiz-option.correct {
      background: #d4edda;
      border-color: #28a745;
      color: #155724;
    }

    .quiz-option.incorrect {
      background: #f8d7da;
      border-color: #dc3545;
      color: #721c24;
    }

    /* CHAPTER 6 POSTCARD & SPIDER-MAN STICKERS */
    .postcard {
      background: var(--pink-card);
      border: 2px dashed var(--rose);
      border-radius: 1.5rem;
      padding: 2.5rem;
      position: relative;
      margin-top: 2rem;
      box-shadow: 0 15px 30px rgba(100, 29, 50, 0.1);
    }

    .spidey-sticker-wrapper {
      position: absolute;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      padding: 6px;
      border: 2px dashed var(--pink-pen);
      border-radius: 16px;
      background: rgba(255, 255, 255, 0.6);
      user-select: none;
      filter: drop-shadow(0 4px 6px rgba(0,0,0,0.06));
    }

    .spidey-top-right {
      top: -24px;
      right: -12px;
      transform: rotate(12deg);
    }

    .spidey-bottom-left {
      bottom: -24px;
      left: -12px;
      transform: rotate(-10deg);
    }

    .spidey-badge {
      display: flex;
      align-items: center;
      gap: 4px;
      background: #fff;
      padding: 6px 10px;
      border-radius: 12px;
      font-size: 1.6rem;
    }

    .modal-overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      background: rgba(66, 19, 33, 0.6);
      backdrop-filter: blur(4px);
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 100;
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.3s ease;
    }

    .modal-overlay.active {
      opacity: 1;
      pointer-events: auto;
    }

    .modal-content {
      background: var(--paper);
      padding: 2rem;
      border-radius: 1.5rem;
      max-width: 30rem;
      width: 90%;
      text-align: center;
      border: 1px solid var(--rose);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(8px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.577.0/dist/umd/lucide.min.js"></script>
</head>
<body>
  <div class="app-shell">
    <header class="page-header">
      <div class="brand-mark">our little love story</div>
    </header>

    <main class="cover-main">
      <section class="cover-card" style="background: rgba(255, 253, 249, 0.88);">
        <p class="eyebrow">A sweet little celebration</p>
        <h1 class="title">Happy Monthsary, my lover!! :p</h1>
        <p class="subtitle">Soft moments, sweet laughter, and a thousand reasons to smile.</p>
        <button id="open-story-button" type="button" class="primary-button" style="background: rgb(100, 29, 50); color: rgb(255, 248, 242);">Open Our Love Story</button>
      </section>

      <!-- CHAPTER MENU -->
      <section id="table-of-contents" class="toc-section">
        <h2 class="toc-heading">Choose a chapter, my love</h2>
        <p class="toc-helper">Every chapter opens a little piece of us.</p>

        <nav class="chapter-grid">
          <a href="#our-memories" class="chapter-link">
            <div>
              <span style="font-style: italic;">01</span>
              <h3 style="margin-top: 0.5rem; font-family: 'Playfair Display', serif;">Our Memories</h3>
            </div>
          </a>
          <a href="#two-letters" class="chapter-link">
            <div>
              <span style="font-style: italic;">02</span>
              <h3 style="margin-top: 0.5rem; font-family: 'Playfair Display', serif;">Two Letters</h3>
            </div>
          </a>
          <a href="#two-flowers" class="chapter-link">
            <div>
              <span style="font-style: italic;">03</span>
              <h3 style="margin-top: 0.5rem; font-family: 'Playfair Display', serif;">Two Flowers</h3>
            </div>
          </a>
          <a href="#two-songs" class="chapter-link">
            <div>
              <span style="font-style: italic;">04</span>
              <h3 style="margin-top: 0.5rem; font-family: 'Playfair Display', serif;">Two Songs</h3>
            </div>
          </a>
          <a href="#two-games" class="chapter-link">
            <div>
              <span style="font-style: italic;">05</span>
              <h3 style="margin-top: 0.5rem; font-family: 'Playfair Display', serif;">Two Games</h3>
            </div>
          </a>
          <a href="#our-ending" class="chapter-link">
            <div>
              <span style="font-style: italic;">06</span>
              <h3 style="margin-top: 0.5rem; font-family: 'Playfair Display', serif;">Our Ending</h3>
            </div>
          </a>
        </nav>
      </section>

      <!-- CHAPTER 1: OUR MEMORIES (POLAROIDS) -->
      <section id="our-memories" class="content-section">
        <p class="section-subtitle">Chapter 01</p>
        <h2 style="font-family: 'Playfair Display', serif; color: var(--burgundy);">Our Memories</h2>
        
        <div class="polaroid-grid">
          <!-- Polaroid 1 -->
          <div class="polaroid-card">
            <div class="polaroid-img-box">
              <img src="IMG_20260901_130031_520.jpg" alt="Memory 1">
            </div>
          </div>

          <!-- Polaroid 2 -->
          <div class="polaroid-card">
            <div class="polaroid-img-box">
              <img src="IMG_20260822_143258_367.jpg" alt="Memory 2">
            </div>
          </div>

          <!-- Polaroid 3 -->
          <div class="polaroid-card">
            <div class="polaroid-img-box">
              <img src="IMG_20260817_182522_884.webp" alt="Memory 3">
            </div>
          </div>
        </div>
      </section>

      <!-- CHAPTER 2: TWO LETTERS -->
      <section id="two-letters" class="content-section">
        <p class="section-subtitle">Chapter 02</p>
        <h2 style="font-family: 'Playfair Display', serif; color: var(--burgundy);">Two Letters</h2>
        <p style="color: #6b3b47;">Choose a letter button below to open and read them one by one:</p>

        <div style="display: flex; gap: 1rem; flex-wrap: wrap; margin-top: 1rem;">
          <button type="button" class="btn-action" onclick="showLetter(1)">Read Letter 1: Looking Back ✉️</button>
          <button type="button" class="btn-action" onclick="showLetter(2)">Read Letter 2: Looking Ahead 💌</button>
        </div>

        <div id="letter-1" class="letter-container">
          <h3 style="font-family: 'Playfair Display', serif; color: var(--burgundy); margin-top: 0;">Letter 1: Looking Back</h3>
          <p>Dearest Yumi,</p>
          <p>Looking back at our time together, I’m constantly reminded of how gentle and beautiful our connection is. From where we started to where we are now, every quiet talk, every laugh, and every small detail has meant the world to me. Thank you for entering my life and making it so much brighter.</p>
        </div>

        <div id="letter-2" class="letter-container">
          <h3 style="font-family: 'Playfair Display', serif; color: var(--burgundy); margin-top: 0;">Letter 2: Looking Ahead</h3>
          <p>My Love,</p>
          <p>As we step into another month together, my heart is full of excitement for all the simple, sweet milestones waiting for us. I promise to keep listening, caring, and cherishing you more with every passing day. Here's to us and everything ahead.</p>
        </div>
      </section>

      <!-- CHAPTER 3: TWO FLOWERS -->
      <section id="two-flowers" class="content-section">
        <p class="section-subtitle">Chapter 03</p>
        <h2 style="font-family: 'Playfair Display', serif; color: var(--burgundy);">Two Flowers</h2>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1.5rem; margin-top: 1.5rem;">
          <!-- Blue Hydrangea -->
          <div style="background: var(--paper); border: 1px solid rgba(100, 29, 50, 0.12); padding: 1.5rem; border-radius: 1rem;">
            <div style="font-size: 2.5rem; text-align: center;">🪻</div>
            <h3 style="font-family: 'Playfair Display', serif; color: var(--burgundy); text-align: center; margin-top: 0.5rem;">Blue Hydrangea</h3>
            <p style="font-weight: 600; color: var(--gold); font-size: 0.85rem; text-align: center;">MEANING: Deep Understanding & Heartfelt Gratitude</p>
            <p style="color: #6b3b47; font-size: 0.95rem; margin-top: 1rem; line-height: 1.6;">
              <strong>Why I dedicate this to you:</strong> I chose the blue hydrangea for you because it represents sincere emotion, patience, and true understanding. You bring a calming, comforting presence into my life that makes me feel completely understood and at peace.
            </p>
          </div>

          <!-- Pink Roses -->
          <div style="background: var(--paper); border: 1px solid rgba(100, 29, 50, 0.12); padding: 1.5rem; border-radius: 1rem;">
            <div style="font-size: 2.5rem; text-align: center;">🌹</div>
            <h3 style="font-family: 'Playfair Display', serif; color: var(--burgundy); text-align: center; margin-top: 0.5rem;">Pink Roses</h3>
            <p style="font-weight: 600; color: var(--gold); font-size: 0.85rem; text-align: center;">MEANING: Gentleness, Admiration & Sweet Joy</p>
            <p style="color: #6b3b47; font-size: 0.95rem; margin-top: 1rem; line-height: 1.6;">
              <strong>Why I dedicate this to you:</strong> Pink roses symbolize grace, sweetness, and admiration. Every time I see you or hear your voice, you bring out the softest, happiest version of me. Dedicating this to you is my little way of celebrating how lovely you are inside and out.
            </p>
          </div>
        </div>
      </section>

      <!-- CHAPTER 4: TWO SONGS -->
      <section id="two-songs" class="content-section">
        <p class="section-subtitle">Chapter 04</p>
        <h2 style="font-family: 'Playfair Display', serif; color: var(--burgundy);">Two Songs</h2>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1.5rem; margin-top: 1.5rem;">
          <!-- Song 1: Tsunami by NIKI -->
          <div style="background: var(--paper); border: 1px solid rgba(100, 29, 50, 0.12); padding: 1.5rem; border-radius: 1rem;">
            <i data-lucide="music" style="color: var(--gold);"></i>
            <h3 style="font-family: 'Playfair Display', serif; color: var(--burgundy); margin-top: 0.5rem;">1. Tsunami — NIKI</h3>
            <p style="font-size: 0.9rem; color: #6b3b47; margin-top: 0.5rem; line-height: 1.6;">
              <em>"Subtle and soft, but completely overwhelming in the sweetest way."</em>
            </p>
            <p style="font-size: 0.9rem; color: #704451; margin-top: 0.8rem;">
              This song reminds me of how naturally and deeply my feelings for you grew. It felt effortless, calm, yet impossibly strong all at once.
            </p>
          </div>

          <!-- Song 2: Bawat Daan by Ebe Dancel -->
          <div style="background: var(--paper); border: 1px solid rgba(100, 29, 50, 0.12); padding: 1.5rem; border-radius: 1rem;">
            <i data-lucide="heart-handshake" style="color: var(--gold);"></i>
            <h3 style="font-family: 'Playfair Display', serif; color: var(--burgundy); margin-top: 0.5rem;">2. Bawat Daan — Ebe Dancel</h3>
            <p style="font-size: 0.9rem; color: #6b3b47; margin-top: 0.5rem; line-height: 1.6;">
              <em>"Kung saan-saan man mapadpad, sa'yo pa rin ang uwi."</em>
            </p>
            <p style="font-size: 0.9rem; color: #704451; margin-top: 0.8rem;">
              No matter where life takes us or what roads we cross, you feel like home to me. You are my quiet destination and my happiest choice.
            </p>
          </div>
        </div>
      </section>

      <!-- CHAPTER 5: TWO GAMES -->
      <section id="two-games" class="content-section">
        <p class="section-subtitle">Chapter 05</p>
        <h2 style="font-family: 'Playfair Display', serif; color: var(--burgundy);">Two Games</h2>

        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; margin-top: 1.5rem;">
          <!-- Quiz -->
          <div style="background: var(--paper); border: 1px solid rgba(100, 29, 50, 0.12); padding: 1.5rem; border-radius: 1rem;">
            <h3 style="font-family: 'Playfair Display', serif; color: var(--burgundy);">Game 1: How Well Do You Know Us?</h3>
            <div id="quiz-container" style="margin-top: 1rem;">
              <p id="quiz-q" style="font-weight: 600; color: var(--burgundy);">Question 1: What makes our bond so special?</p>
              <div id="quiz-opts" style="margin-top: 0.5rem;">
                <button class="quiz-option" onclick="checkAnswer(true, this)">A) Our soft, genuine connection and mutual understanding ♥</button>
                <button class="quiz-option" onclick="checkAnswer(false, this)">B) Total randomness!</button>
              </div>
              <p id="quiz-msg" style="margin-top: 0.5rem; font-weight: 600; color: var(--burgundy);"></p>
            </div>
          </div>

          <!-- Open When Cards -->
          <div style="background: var(--paper); border: 1px solid rgba(100, 29, 50, 0.12); padding: 1.5rem; border-radius: 1rem;">
            <h3 style="font-family: 'Playfair Display', serif; color: var(--burgundy);">Game 2: Open When Notes</h3>
            <p style="font-size: 0.9rem; color: #6b3b47; margin-top: 0.5rem;">Click a card whenever you need a sweet reminder from me:</p>
            <div style="display: flex; flex-direction: column; gap: 0.5rem; margin-top: 1rem;">
              <button type="button" class="btn-action" onclick="openModal('miss')">Click when you miss me 💌</button>
              <button type="button" class="btn-action" onclick="openModal('hug')">Click when you need a hug 🫂</button>
            </div>
          </div>
        </div>
      </section>

      <!-- CHAPTER 6: OUR ENDING (PINK POSTCARD + SPIDEY STICKERS & PINK DASHED OUTLINES) -->
      <section id="our-ending" class="content-section" style="text-align: center;">
        <p class="section-subtitle">Chapter 06</p>
        <h2 style="font-family: 'Playfair Display', serif; color: var(--burgundy);">Our Ending</h2>

        <div class="postcard">
          <!-- Spider-Man Cute Sticker Top Right -->
          <div class="spidey-sticker-wrapper spidey-top-right">
            <div class="spidey-badge">
              <svg width="28" height="28" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <!-- Spider Mask SVG -->
                <path d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2Z" fill="#E53935"/>
                <path d="M7 9C6.5 11 8 13.5 10 13C10 11 9 9 7 9Z" fill="white" stroke="#212121" stroke-width="1.2"/>
                <path d="M17 9C17.5 11 16 13.5 14 13C14 11 15 9 17 9Z" fill="white" stroke="#212121" stroke-width="1.2"/>
              </svg>
              <span>🕸️</span>
            </div>
          </div>

          <!-- Spider-Man Cute Sticker Bottom Left -->
          <div class="spidey-sticker-wrapper spidey-bottom-left">
            <div class="spidey-badge">
              <span>🕷️</span>
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <!-- Web Heart -->
                <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z" fill="#E83E8C"/>
              </svg>
            </div>
          </div>

          <p style="font-family: 'Playfair Display', serif; font-size: 1.3rem; color: var(--burgundy); line-height: 1.7; margin: 0;">
            "A lifetime of sweet moments to go. Thank you for being my favorite part of every single day. I love you, Yumi."
          </p>
          <p style="margin-top: 1.5rem; font-family: 'Caveat', cursive; font-size: 1.6rem; color: var(--burgundy);">
            — Forever yours ♥
          </p>
        </div>
      </section>
    </main>

    <!-- MODAL POPUP FOR OPEN-WHEN CARDS -->
    <div id="note-modal" class="modal-overlay">
      <div class="modal-content">
        <h3 id="modal-title" style="font-family: 'Playfair Display', serif; color: var(--burgundy); font-size: 1.5rem;"></h3>
        <p id="modal-text" style="margin-top: 1rem; color: #6b3b47; line-height: 1.6;"></p>
        <button type="button" class="btn-action" onclick="closeModal()" style="margin-top: 1.5rem;">Close Note ♥</button>
      </div>
    </div>

    <footer style="margin-top: 4rem; text-align: center; color: #9a6941; font-family: 'Playfair Display', serif; font-style: italic; font-size: 0.9rem;">
      Made with all my love, especially for Yumi
    </footer>
  </div>

  <script>
    document.addEventListener("DOMContentLoaded", () => {
      if (window.lucide) { lucide.createIcons(); }

      const openBtn = document.getElementById("open-story-button");
      const toc = document.getElementById("table-of-contents");
      if (openBtn && toc) {
        openBtn.addEventListener("click", () => {
          toc.scrollIntoView({ behavior: "smooth" });
        });
      }
    });

    /* CHAPTER 2: LETTERS JS */
    function showLetter(num) {
      document.getElementById("letter-1").classList.remove("active");
      document.getElementById("letter-2").classList.remove("active");
      const target = document.getElementById(`letter-${num}`);
      if (target) target.classList.add("active");
    }

    /* CHAPTER 5: QUIZ JS */
    function checkAnswer(isCorrect, btn) {
      const msg = document.getElementById("quiz-msg");
      const allBtns = document.querySelectorAll("#quiz-opts .quiz-option");
      allBtns.forEach(b => b.classList.remove("correct", "incorrect"));

      if (isCorrect) {
        btn.classList.add("correct");
        msg.textContent = "Correct! You are my favorite part of every day! ♥";
      } else {
        btn.classList.add("incorrect");
        msg.textContent = "Try again, my love!";
      }
    }

    /* CHAPTER 5: OPEN-WHEN MODAL JS */
    const notes = {
      miss: {
        title: "When You Miss Me 💌",
        text: "Whenever you miss me, remember that I'm always thinking of you too. Send me a quick text, and I'll be right there!"
      },
      hug: {
        title: "When You Need a Hug 🫂",
        text: "Close your eyes, take a slow breath, and know that I am wrapping you in the warmest, tightest hug right now. You are safe and loved!"
      }
    };

    function openModal(key) {
      if (notes[key]) {
        document.getElementById("modal-title").textContent = notes[key].title;
        document.getElementById("modal-text").textContent = notes[key].text;
        document.getElementById("note-modal").classList.add("active");
      }
    }

    function closeModal() {
      document.getElementById("note-modal").classList.remove("active");
    }
  </script>
</body>
</html>
