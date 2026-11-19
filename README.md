
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy 21st Birthday, Meri Pyari Jigglu (Janu) 🎂✨</title>
    <!-- Google Fonts: Great Vibes, Playfair Display & Quicksand -->
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:ital,wght@0,600;0,700;1,600&family=Quicksand:wght@400;500;600;700&display=swap" rel="stylesheet">

    <style>
        /* ==============================================================
           1. TWILIGHT STARLIGHT & ROSE-GOLD THEME VARIABLES
           ============================================================== */
        :root {
            --bg-night: #0f081e;
            --bg-twilight: #21113b;
            --bg-plum: #3d163b;
            --rose-gold: #f472b6;
            --rose-soft: #fbcfe8;
            --champagne: #fde68a;
            --amber-glow: #f59e0b;
            --cream-text: #fffbeb;
            --lavender-text: #f3e8ff;
            --glass-surface: rgba(28, 15, 52, 0.76);
            --glass-border: rgba(253, 230, 138, 0.32);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            font-family: 'Quicksand', sans-serif;
            background: radial-gradient(circle at 80% 10%, var(--bg-plum) 0%, var(--bg-twilight) 48%, var(--bg-night) 100%);
            color: var(--cream-text);
            min-height: 100vh;
            overflow-x: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 64px 16px 28px;
            position: relative;
        }

        .font-script {
            font-family: 'Great Vibes', cursive;
        }

        .font-serif {
            font-family: 'Playfair Display', serif;
        }

        /* Background Twinkling Starlight & Floating Hearts Canvas */
        #starlight-canvas {
            position: fixed;
            inset: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 0;
        }

        /* Top Floating Music & Sound Toggle Bar */
        .top-audio-bar {
            position: fixed;
            top: 14px;
            right: 16px;
            left: 16px;
            max-width: 450px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 50;
            pointer-events: none;
        }

        .stage-pill {
            pointer-events: auto;
            background: rgba(24, 12, 46, 0.78);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(253, 230, 138, 0.3);
            color: var(--champagne);
            font-size: 0.72rem;
            font-weight: 700;
            padding: 7px 13px;
            border-radius: 999px;
            letter-spacing: 0.05em;
        }

        .sound-toggle-btn {
            pointer-events: auto;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            background: linear-gradient(135deg, rgba(244, 114, 182, 0.25), rgba(245, 158, 11, 0.25));
            backdrop-filter: blur(12px);
            border: 1px solid rgba(253, 230, 138, 0.45);
            color: var(--cream-text);
            font-family: 'Quicksand', sans-serif;
            font-size: 0.76rem;
            font-weight: 700;
            padding: 7px 14px;
            border-radius: 999px;
            cursor: pointer;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.35);
            transition: all 0.25s ease;
        }

        .sound-toggle-btn:hover {
            transform: scale(1.04);
            border-color: var(--champagne);
        }

        .sound-wave {
            display: inline-flex;
            align-items: flex-end;
            gap: 2px;
            height: 12px;
        }

        .sound-wave span {
            width: 2.5px;
            height: 5px;
            background: var(--champagne);
            border-radius: 2px;
            transition: height 0.2s ease;
        }

        .sound-wave.playing span:nth-child(1) { animation: eqBar 0.6s infinite alternate; }
        .sound-wave.playing span:nth-child(2) { animation: eqBar 0.45s infinite alternate 0.15s; }
        .sound-wave.playing span:nth-child(3) { animation: eqBar 0.7s infinite alternate 0.3s; }

        @keyframes eqBar {
            from { height: 4px; }
            to { height: 12px; }
        }

        /* Main Glassmorphic App Container */
        .app-container {
            width: 100%;
            max-width: 450px;
            z-index: 10;
            position: relative;
        }

        .glass-stage {
            background: var(--glass-surface);
            backdrop-filter: blur(22px);
            -webkit-backdrop-filter: blur(22px);
            border: 1.5px solid var(--glass-border);
            border-radius: 30px;
            padding: 28px 22px;
            box-shadow: 0 28px 65px rgba(0, 0, 0, 0.6), 0 0 35px rgba(244, 114, 182, 0.18);
            text-align: center;
            animation: smoothEntrance 0.65s cubic-bezier(0.16, 1, 0.3, 1) forwards;
        }

        @keyframes smoothEntrance {
            from { opacity: 0; transform: translateY(26px) scale(0.96); }
            to { opacity: 1; transform: translateY(0) scale(1); }
        }

        .hidden {
            display: none !important;
        }

        /* Badges & Gradients */
        .royal-badge {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            padding: 6px 15px;
            border-radius: 999px;
            background: linear-gradient(135deg, rgba(245, 158, 11, 0.22), rgba(244, 114, 182, 0.24));
            border: 1px solid rgba(253, 230, 138, 0.45);
            color: var(--champagne);
            font-size: 0.75rem;
            font-weight: 700;
            letter-spacing: 0.08em;
            text-transform: uppercase;
            margin-bottom: 14px;
        }

        .rose-gold-heading {
            background: linear-gradient(135deg, #fffbeb 5%, #fde68a 45%, #f472b6 92%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Primary CTA Button */
        .btn-celestial {
            width: 100%;
            padding: 15px 22px;
            border: none;
            border-radius: 18px;
            background: linear-gradient(135deg, #f59e0b 0%, #ec4899 52%, #9333ea 100%);
            color: #ffffff;
            font-family: 'Quicksand', sans-serif;
            font-size: 1rem;
            font-weight: 700;
            cursor: pointer;
            box-shadow: 0 12px 28px rgba(236, 72, 153, 0.42);
            transition: transform 0.2s cubic-bezier(0.34, 1.56, 0.64, 1), box-shadow 0.2s ease;
        }

        .btn-celestial:hover {
            transform: translateY(-2px) scale(1.01);
            box-shadow: 0 16px 34px rgba(236, 72, 153, 0.56);
        }

        .btn-celestial:active {
            transform: scale(0.96);
        }

        /* ==============================================================
           2. STAGE 1: CELESTIAL PORTAL ENTRANCE
           ============================================================== */
        .celestial-portal {
            width: 164px;
            height: 164px;
            margin: 10px auto 18px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(244, 114, 182, 0.32) 0%, rgba(245, 158, 11, 0.14) 55%, transparent 74%);
            border: 1.5px dashed rgba(253, 230, 138, 0.6);
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            cursor: pointer;
            animation: orbitRotate 18s linear infinite;
        }

        .celestial-portal::before {
            content: "✨";
            position: absolute;
            top: -10px;
            font-size: 1.1rem;
        }

        .celestial-portal::after {
            content: "💖";
            position: absolute;
            bottom: -10px;
            font-size: 1rem;
        }

        .portal-emblem {
            animation: counterOrbit 18s linear infinite, hoverFloat 2.6s ease-in-out infinite;
            font-size: 4.3rem;
            filter: drop-shadow(0 10px 22px rgba(245, 158, 11, 0.5));
        }

        @keyframes orbitRotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        @keyframes counterOrbit {
            from { transform: rotate(0deg); }
            to { transform: rotate(-360deg); }
        }

        @keyframes hoverFloat {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-9px); }
        }

        .nickname-ticker {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 6px;
            margin: 14px 0 22px;
        }

        .nick-chip {
            font-size: 0.72rem;
            font-weight: 700;
            padding: 4px 10px;
            border-radius: 999px;
            background: rgba(255, 255, 255, 0.09);
            border: 1px solid rgba(244, 114, 182, 0.35);
            color: var(--rose-soft);
        }

        /* ==============================================================
           3. STAGE 2: MULTI-TIER ROSE-GOLD & CREAM 21ST CAKE
           ============================================================== */
        .cake-arena {
            position: relative;
            height: 255px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-end;
            margin: 10px 0 16px;
            padding-bottom: 10px;
        }

        .topper-21-crown {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 2px;
            animation: crownGlow 2.2s infinite alternate;
        }

        .topper-21-num {
            font-family: 'Playfair Display', serif;
            font-size: 2.25rem;
            font-weight: 700;
            line-height: 1;
            color: #fde68a;
            text-shadow: 0 0 14px rgba(245, 158, 11, 0.95), 0 0 26px rgba(244, 114, 182, 0.8);
        }

        @keyframes crownGlow {
            from { transform: scale(1); }
            to { transform: scale(1.07); }
        }

        .candles-group {
            display: flex;
            gap: 28px;
            z-index: 6;
            margin-bottom: -4px;
        }

        .candle-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            padding: 4px 8px;
            position: relative;
            transition: transform 0.2s ease;
        }

        .candle-item:hover {
            transform: scale(1.1);
        }

        .candle-flame {
            width: 14px;
            height: 23px;
            background: radial-gradient(circle at 50% 75%, #ffffff 12%, #fde047 48%, #f97316 86%, transparent 100%);
            border-radius: 50% 50% 35% 35%;
            box-shadow: 0 0 14px #fbbf24, 0 0 28px #f97316;
            animation: flameDance 0.32s infinite alternate ease-in-out;
            transform-origin: bottom center;
            margin-bottom: 3px;
        }

        .candle-flame.extinguished {
            opacity: 0;
            transform: scale(0.1) translateY(-14px);
            transition: all 0.35s ease-out;
        }

        /* Smoke Puff when blown out */
        .smoke-puff {
            position: absolute;
            top: -8px;
            width: 14px;
            height: 14px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.65);
            filter: blur(3px);
            animation: smokeRise 1.1s ease-out forwards;
            pointer-events: none;
        }

        @keyframes smokeRise {
            0% { opacity: 0.85; transform: translateY(0) scale(0.7); }
            100% { opacity: 0; transform: translateY(-34px) scale(2.2); }
        }

        @keyframes flameDance {
            0% { transform: scale(1) rotate(-3deg); }
            100% { transform: scale(1.08, 0.93) rotate(3deg); }
        }

        .candle-body {
            width: 10px;
            height: 36px;
            border-radius: 4px;
            background: repeating-linear-gradient(45deg, #fffbeb, #fffbeb 5px, #f472b6 5px, #f472b6 10px);
            border: 1px solid rgba(253, 230, 138, 0.7);
        }

        /* Rose-Gold & Cream Tiers */
        .tier-top {
            width: 144px;
            height: 48px;
            background: linear-gradient(180deg, #fffbeb 0%, #fbcfe8 45%, #f472b6 100%);
            border-radius: 16px 16px 6px 6px;
            position: relative;
            box-shadow: inset 0 6px 0 rgba(255, 255, 255, 0.7), 0 5px 14px rgba(0, 0, 0, 0.28);
            transition: transform 0.65s cubic-bezier(0.34, 1.56, 0.64, 1);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .tier-top::after {
            content: "Janu 👑";
            font-size: 0.68rem;
            font-weight: 700;
            color: #831843;
        }

        .tier-bottom {
            width: 210px;
            height: 60px;
            background: linear-gradient(180deg, #fde68a 0%, #f9a8d4 45%, #db2777 100%);
            border-radius: 16px 16px 10px 10px;
            position: relative;
            box-shadow: inset 0 7px 0 rgba(255, 255, 255, 0.65), 0 10px 22px rgba(0, 0, 0, 0.38);
            transition: transform 0.65s cubic-bezier(0.34, 1.56, 0.64, 1);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .tier-bottom::after {
            content: "✨ Pyari Jigglu • 21 ✨";
            font-size: 0.75rem;
            font-weight: 700;
            color: #4c0519;
            letter-spacing: 0.4px;
        }

        .cake-stand {
            width: 244px;
            height: 12px;
            background: linear-gradient(90deg, #d97706, #fef3c7, #f59e0b);
            border-radius: 999px;
            box-shadow: 0 8px 18px rgba(0, 0, 0, 0.5);
        }

        .cake-cut-active .tier-top {
            transform: translateX(-10px) rotate(-2.5deg);
        }

        .cake-cut-active .tier-bottom {
            transform: translateX(10px) rotate(2deg);
        }

        /* ==============================================================
           4. STAGE 3: NICKNAME & ROMANTIC COMPLIMENT CONSTELLATION
           ============================================================== */
        .constellation-bar {
            width: 100%;
            height: 10px;
            background: rgba(255, 255, 255, 0.12);
            border-radius: 999px;
            overflow: hidden;
            margin: 10px 0 16px;
            border: 1px solid rgba(253, 230, 138, 0.3);
        }

        .constellation-fill {
            height: 100%;
            width: 0%;
            background: linear-gradient(90deg, #fde68a, #f472b6, #a855f7);
            transition: width 0.45s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .orbs-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 11px;
            margin-bottom: 16px;
        }

        .orb-card {
            min-height: 124px;
            border-radius: 22px;
            padding: 12px 10px;
            background: radial-gradient(circle at top left, rgba(244, 114, 182, 0.26), rgba(88, 28, 135, 0.32));
            border: 1.5px solid rgba(253, 230, 138, 0.38);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.25), inset 0 0 16px rgba(244, 114, 182, 0.15);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.32s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .orb-card:hover {
            transform: translateY(-4px) scale(1.03);
            border-color: var(--champagne);
            box-shadow: 0 12px 26px rgba(244, 114, 182, 0.35);
        }

        .orb-card.revealed {
            background: linear-gradient(145deg, rgba(255, 251, 235, 0.14), rgba(244, 114, 182, 0.22));
            border-color: #f472b6;
            cursor: default;
            transform: scale(1);
        }

        .orb-sphere {
            width: 46px;
            height: 46px;
            border-radius: 50%;
            background: radial-gradient(circle at 30% 30%, #ffffff, #fbcfe8 35%, #ec4899 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.4rem;
            margin-bottom: 7px;
            box-shadow: 0 0 18px rgba(244, 114, 182, 0.65);
            animation: orbBob 2.8s ease-in-out infinite;
        }

        .orb-card:nth-child(even) .orb-sphere {
            animation-delay: 0.9s;
        }

        @keyframes orbBob {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }

        .orb-shayari {
            font-size: 0.76rem;
            line-height: 1.45;
            color: #fffbeb;
            font-weight: 600;
            animation: fadeScaleIn 0.4s ease forwards;
        }

        @keyframes fadeScaleIn {
            from { opacity: 0; transform: scale(0.86); }
            to { opacity: 1; transform: scale(1); }
        }

        /* ==============================================================
           5. STAGE 4: DIL KI BAATEIN (INTERACTIVE SCRATCH & DECK)
           ============================================================== */
        .scratch-container {
            position: relative;
            width: 100%;
            height: 165px;
            border-radius: 22px;
            overflow: hidden;
            margin: 14px 0 16px;
            border: 2px solid rgba(253, 230, 138, 0.55);
            box-shadow: 0 12px 30px rgba(0, 0, 0, 0.4);
            user-select: none;
            touch-action: none;
        }

        .scratch-secret-layer {
            position: absolute;
            inset: 0;
            background: linear-gradient(135deg, #4c0519 0%, #701a75 50%, #3b0764 100%);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 16px;
            text-align: center;
        }

        #scratch-canvas {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            cursor: crosshair;
            transition: opacity 0.5s ease;
        }

        .shayari-deck-card {
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(244, 114, 182, 0.38);
            border-radius: 20px;
            padding: 16px 14px;
            margin-bottom: 16px;
            min-height: 112px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }

        .btn-deck-next {
            background: rgba(253, 230, 138, 0.16);
            border: 1px solid rgba(253, 230, 138, 0.5);
            color: var(--champagne);
            font-family: 'Quicksand', sans-serif;
            font-size: 0.8rem;
            font-weight: 700;
            padding: 8px 16px;
            border-radius: 999px;
            cursor: pointer;
            margin-top: 10px;
            transition: all 0.2s ease;
        }

        .btn-deck-next:hover {
            background: rgba(253, 230, 138, 0.28);
        }

        /* ==============================================================
           6. STAGE 5: ROYAL 21ST LETTER & GOLDEN VIP PASS
           ============================================================== */
        .royal-letter-box {
            background: rgba(15, 8, 30, 0.68);
            border: 1px solid rgba(253, 230, 138, 0.32);
            border-radius: 22px;
            padding: 18px 16px;
            text-align: left;
            font-size: 0.85rem;
            line-height: 1.65;
            color: var(--lavender-text);
            margin: 12px 0 16px;
            max-height: 270px;
            overflow-y: auto;
        }

        .royal-letter-box p {
            margin-bottom: 11px;
        }

        .royal-letter-box p:last-child {
            margin-bottom: 0;
        }

        .royal-letter-box::-webkit-scrollbar {
            width: 5px;
        }
        .royal-letter-box::-webkit-scrollbar-thumb {
            background: rgba(244, 114, 182, 0.55);
            border-radius: 10px;
        }

        .golden-vip-card {
            margin-top: 14px;
            background: linear-gradient(135deg, #fef3c7 0%, #fde68a 45%, #fbcfe8 100%);
            color: #3b0764;
            border-radius: 24px;
            padding: 4px;
            box-shadow: 0 16px 38px rgba(245, 158, 11, 0.4);
            animation: smoothEntrance 0.6s ease forwards;
        }

        .golden-vip-inner {
            border: 2px dashed #b45309;
            border-radius: 20px;
            padding: 18px 14px;
            background: rgba(255, 255, 255, 0.62);
        }

        .vip-pill {
            display: inline-block;
            background: #701a75;
            color: #fde68a;
            font-size: 0.66rem;
            font-weight: 700;
            letter-spacing: 0.1em;
            text-transform: uppercase;
            padding: 4px 12px;
            border-radius: 999px;
            margin-bottom: 8px;
        }

        .btn-replay-outline {
            margin-top: 12px;
            width: 100%;
            padding: 12px 16px;
            border-radius: 16px;
            background: rgba(255, 255, 255, 0.12);
            border: 1px solid rgba(253, 230, 138, 0.45);
            color: var(--champagne);
            font-family: 'Quicksand', sans-serif;
            font-size: 0.88rem;
            font-weight: 700;
            cursor: pointer;
            transition: background 0.2s ease;
        }

        .btn-replay-outline:hover {
            background: rgba(255, 255, 255, 0.22);
        }

        /* Floating Confetti Burst DOM */
        .burst-particle {
            position: fixed;
            pointer-events: none;
            z-index: 99;
            font-size: 1.45rem;
            animation: burstOut 1.65s cubic-bezier(0.16, 1, 0.3, 1) forwards;
        }

        @keyframes burstOut {
            0% { transform: translate(0, 0) scale(0.4) rotate(0deg); opacity: 1; }
            100% { transform: translate(var(--bx), var(--by)) scale(1.35) rotate(var(--brot)); opacity: 0; }
        }
    </style>
</head>
<body>

    <!-- Twinkling Starlight & Floating Hearts Background Canvas -->
    <canvas id="starlight-canvas"></canvas>

    <!-- Top Floating Stage Indicator & Synthesized Music Toggle -->
    <header class="top-audio-bar">
        <span id="stage-indicator" class="stage-pill">24 Dec • 21st Edition ✨</span>
        <button id="music-toggle-btn" class="sound-toggle-btn" onclick="toggleBackgroundMusic()">
            <span id="music-label">Music: Off</span>
            <span id="sound-wave" class="sound-wave">
                <span></span><span></span><span></span>
            </span>
        </button>
    </header>

    <!-- Main Mobile-First Interactive Container -->
    <main class="app-container">

        <!-- ==========================================================
             STAGE 1: MAGICAL 24 DECEMBER 21ST ENTRANCE
             ========================================================== -->
        <section id="stage-1" class="glass-stage">
            <div class="royal-badge">
                ✨ 24 December • Turning 21 ✨
            </div>

            <div class="celestial-portal" onclick="startExperience()">
                <div class="portal-emblem">👑</div>
            </div>

            <h1 class="font-script rose-gold-heading" style="font-size: 2.55rem; line-height: 1.18; margin-bottom: 8px;">
                Happy 21st Birthday, Meri Pyari Jigglu (Janu)! 🎂✨
            </h1>

            <p style="font-size: 0.88rem; color: var(--lavender-text); line-height: 1.6;">
                Aaj 24 December hai—meri duniya ki sabse pyari Queen ka 21st Birthday! Aapke Bhondu ne aapke liye ek khaas starlight surprise banaya hai 💖
            </p>

            <!-- Cute Nicknames Preview Chips -->
            <div class="nickname-ticker">
                <span class="nick-chip">Pyari Jigglu 🌸</span>
                <span class="nick-chip">Janu ❤️</span>
                <span class="nick-chip">Meri Protein 💪</span>
                <span class="nick-chip">Kaju Barfi 💎</span>
                <span class="nick-chip">Soan Papdi 🍯</span>
                <span class="nick-chip">Mera Sona Baccha 🧸</span>
            </div>

            <button class="btn-celestial" onclick="startExperience()">
                Start Your 21st Surprise ✨
            </button>
        </section>

        <!-- ==========================================================
             STAGE 2: INTERACTIVE 21ST BIRTHDAY CAKE CEREMONY
             ========================================================== -->
        <section id="stage-2" class="glass-stage hidden">
            <div class="royal-badge">
                🕯️ Stage 1 of 4 • Make A Wish
            </div>

            <h2 class="font-serif rose-gold-heading" style="font-size: 1.65rem; margin-bottom: 6px;">
                Mera Sona Baccha Ka 21st Cake 🎂
            </h2>

            <p id="cake-guide" style="font-size: 0.83rem; color: var(--lavender-text); line-height: 1.55;">
                Janu, apni aankhein band karke ek pyari si wish maango, aur teeno candles par tap karke unhe bujhao! 🕯️✨
            </p>

            <!-- Multi-Tier Rose-Gold & Cream Cake -->
            <div id="cake-arena" class="cake-arena">
                <div class="topper-21-crown">
                    <span style="font-size: 1.2rem;">👑</span>
                    <span class="topper-21-num">21</span>
                </div>

                <!-- 3 Interactive Candles -->
                <div class="candles-group">
                    <div class="candle-item" onclick="blowOutCandle(0, event)">
                        <div id="c-flame-0" class="candle-flame"></div>
                        <div class="candle-body"></div>
                    </div>
                    <div class="candle-item" onclick="blowOutCandle(1, event)">
                        <div id="c-flame-1" class="candle-flame"></div>
                        <div class="candle-body"></div>
                    </div>
                    <div class="candle-item" onclick="blowOutCandle(2, event)">
                        <div id="c-flame-2" class="candle-flame"></div>
                        <div class="candle-body"></div>
                    </div>
                </div>

                <div class="tier-top"></div>
                <div class="tier-bottom"></div>
                <div class="cake-stand"></div>
            </div>

            <p id="candle-counter-text" style="font-size: 0.78rem; color: var(--champagne); font-weight: 700; margin-bottom: 14px;">
                Candles lit: 3 / 3 🔥 (Har candle par tap karein)
            </p>

            <button id="cut-cake-btn" class="btn-celestial hidden" onclick="performCakeCut(event)">
                Cut the Cake 🔪✨
            </button>

            <button id="to-stage3-btn" class="btn-celestial hidden" onclick="goToStage3()">
                Explore Your Nickname Constellation 🌟
            </button>
        </section>

        <!-- ==========================================================
             STAGE 3: NICKNAME & ROMANTIC COMPLIMENT CONSTELLATION
             ========================================================== -->
        <section id="stage-3" class="glass-stage hidden">
            <div class="royal-badge">
                🌟 Stage 2 of 4 • Nickname Constellation
            </div>

            <h2 class="font-serif rose-gold-heading" style="font-size: 1.55rem; margin-bottom: 4px;">
                Har Naam Mein Ek Kahani 💖
            </h2>
            <p style="font-size: 0.8rem; color: var(--lavender-text);">
                Har glowing orb par tap karke dekho aapka Bhondu aapko in pyare naamon se kyun bulata hai 👇
            </p>

            <!-- Constellation Unlock Progress -->
            <div style="display: flex; justify-content: space-between; font-size: 0.74rem; font-weight: 700; color: var(--champagne); margin-top: 10px;">
                <span>Stars Unlocked</span>
                <span id="constellation-count">0 / 6</span>
            </div>
            <div class="constellation-bar">
                <div id="constellation-fill" class="constellation-fill"></div>
            </div>

            <!-- 6 Interactive Glowing Orbs -->
            <div id="orbs-grid" class="orbs-grid"></div>

            <button id="to-stage4-btn" class="btn-celestial hidden" onclick="goToStage4()">
                Open Dil Ki Baatein 💌✨
            </button>
        </section>

        <!-- ==========================================================
             STAGE 4: SCRATCH-TO-REVEAL & ROMANTIC SHAYARI DECK
             ========================================================== -->
        <section id="stage-4" class="glass-stage hidden">
            <div class="royal-badge">
                💫 Stage 3 of 4 • Dil Ki Baatein
            </div>

            <h2 class="font-serif rose-gold-heading" style="font-size: 1.6rem; margin-bottom: 4px;">
                Janu Ke Liye Dil Se Shayari 🌹
            </h2>
            <p style="font-size: 0.79rem; color: var(--lavender-text);">
                Neeche diye gaye golden card ko apni ungli se scratch karke secret promise dekhein ✨
            </p>

            <!-- Interactive Scratch-to-Reveal Card -->
            <div class="scratch-container" id="scratch-box">
                <div class="scratch-secret-layer">
                    <span style="font-size: 1.4rem; margin-bottom: 4px;">💍❤️</span>
                    <p class="font-serif" style="font-size: 0.96rem; color: #fde68a; font-weight: 700; line-height: 1.45;">
                        "Mujhe ek hi janam mila hai, aur main bas tumhara banke rehna chahta hoon."
                    </p>
                    <span style="font-size: 0.7rem; color: #fbcfe8; margin-top: 4px;">— Forever &amp; Always, Aapka Krishna</span>
                </div>
                <canvas id="scratch-canvas"></canvas>
            </div>

            <!-- Interactive Romantic Shayari Deck -->
            <div class="shayari-deck-card">
                <span id="shayari-tag" style="font-size: 0.7rem; font-weight: 700; color: #f472b6; text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 6px;">
                    Shayari 1 of 4 • Meri Queen
                </span>
                <p id="shayari-text" class="font-serif" style="font-size: 0.92rem; color: #fffbeb; line-height: 1.55; font-style: italic;">
                    "Chaand ne bhi aaj aasmaan se jhaank kar dekha hoga, jab 24 December ko meri Pyari Jigglu ne is duniya mein kadam rakha hoga."
                </p>
                <button class="btn-deck-next" onclick="nextShayariCard()">
                    Next Romantic Line 💫 ➔
                </button>
            </div>

            <button class="btn-celestial" onclick="goToStage5()">
                Read Your Royal 21st Letter 👑
            </button>
        </section>

        <!-- ==========================================================
             STAGE 5: ROYAL 21ST BIRTHDAY LETTER & COLLECTIBLE VIP PASS
             ========================================================== -->
        <section id="stage-5" class="glass-stage hidden">
            <div class="royal-badge">
                👑 24 December • Happy 21st Birthday
            </div>

            <h2 class="font-script rose-gold-heading" style="font-size: 2.35rem; line-height: 1.15;">
                Meri Pyari Jigglu (Janu) Ke Naam 💌
            </h2>

            <div class="royal-letter-box">
                <p>
                    <strong>Happy 21st Birthday, meri jaan! 🎂✨</strong><br>
                    Aaj 24 December hai, aur aaj <strong>Mera Sona Baccha</strong> 21 saal ka ho gaya hai. Sach kahoon toh aapki is pyari si zindagi ka hissa banna mere liye sabse badi khushi hai.
                </p>
                <p>
                    Aap mere liye woh sab kuch ho jo lafzon mein bayan karna mushkil hai—kabhi meri rare <strong>Kaju Barfi</strong>, kabhi meethi si <strong>Soan Papdi</strong>, aur kabhi mere dil ko har din khush rakhne wali <strong>Meri Protein</strong> dose! 💪❤️
                </p>
                <p>
                    Aapki khoobsurati, aapki masumiyat, aur aapka saaf dil hi mujhe har roz aapse aur zyada pyaar karne par majboor karta hai. Aap apne har sapne mein khoob kamyab ho, aur har kadam par aapka yeh Bhondu aapke saath khada rahega.
                </p>
                <p style="text-align: right; color: var(--champagne); font-weight: 700; margin-top: 8px;">
                    Hamesha sirf aapka,<br>
                    Aapka Bhondu, Krishna ❤️
                </p>
            </div>

            <button id="reveal-vip-btn" class="btn-celestial" onclick="unlockVipPass(event)">
                Unlock Your Golden 21st VIP Pass 🎟️
            </button>

            <!-- Screenshot-Ready Collectible VIP Pass -->
            <div id="vip-pass-card" class="golden-vip-card hidden">
                <div class="golden-vip-inner">
                    <span class="vip-pill">✨ Official Royal 21st Collectible ✨</span>
                    <h3 class="font-serif" style="font-size: 1.25rem; color: #4c0519; margin-bottom: 6px;">
                        Golden 21st Birthday VIP Pass 👑
                    </h3>
                    <p style="font-size: 0.78rem; font-weight: 700; color: #3b0764; line-height: 1.5; margin-bottom: 8px;">
                        Valid for Lifetime • Unlimited Kaju Barfi, Sweet Soan Papdi, Tight Hugs, Daily Protein Happiness &amp; Forever Love ❤️
                    </p>
                    <p style="font-size: 0.68rem; color: #78350f; font-weight: 700;">
                        ISSUED TO: PYARI JIGGLU (JANU) • 24 DEC • NO EXPIRY
                    </p>
                </div>
            </div>

            <button id="replay-confetti-btn" class="btn-replay-outline hidden" onclick="triggerReplayCelebration(event)">
                Replay Celebration 🎉✨
            </button>
        </section>

    </main>

    <script>
        /* ==============================================================
           1. WEB AUDIO API SYNTHESIZER (MUSIC & MAGICAL SOUND EFFECTS)
           Zero external audio files needed — works 100% offline/anywhere!
           ============================================================== */
        let audioCtx = null;
        let isMusicPlaying = false;
        let melodyTimer = null;
        let melodyStep = 0;

        // Soft Romantic Music-Box Arpeggio Frequencies (F Major 9 / C Major 9 dreamy notes)
        const romanticMelody = [
            523.25, 659.25, 783.99, 987.77, // C5 E5 G5 B5
            880.00, 783.99, 659.25, 587.33, // A5 G5 E5 D5
            493.88, 587.33, 783.99, 880.00, // B4 D5 G5 A5
            783.99, 659.25, 523.25, 587.33  // G5 E5 C5 D5
        ];

        function initAudioContext() {
            if (!audioCtx) {
                const AudioContextClass = window.AudioContext || window.webkitAudioContext;
                audioCtx = new AudioContextClass();
            }
            if (audioCtx.state === 'suspended') {
                audioCtx.resume();
            }
        }

        function playTone(freq, duration = 0.6, type = 'sine', volume = 0.08, delay = 0) {
            if (!audioCtx) return;
            const now = audioCtx.currentTime + delay;
            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();

            osc.type = type;
            osc.frequency.setValueAtTime(freq, now);

            gain.gain.setValueAtTime(0.0001, now);
            gain.gain.exponentialRampToValueAtTime(volume, now + 0.04);
            gain.gain.exponentialRampToValueAtTime(0.0001, now + duration);

            osc.connect(gain);
            gain.connect(audioCtx.destination);

            osc.start(now);
            osc.stop(now + duration + 0.05);
        }

        function startBackgroundMusic() {
            initAudioContext();
            if (isMusicPlaying) return;
            isMusicPlaying = true;
            updateMusicUI();

            melodyTimer = setInterval(() => {
                if (!isMusicPlaying) return;
                const note = romanticMelody[melodyStep % romanticMelody.length];
                playTone(note, 1.35, 'sine', 0.055, 0);
                // Subtle harmonic shimmer on every 4th beat
                if (melodyStep % 4 === 0) {
                    playTone(note * 0.5, 1.8, 'triangle', 0.035, 0.05);
                }
                melodyStep++;
            }, 620);
        }

        function stopBackgroundMusic() {
            isMusicPlaying = false;
            if (melodyTimer) clearInterval(melodyTimer);
            updateMusicUI();
        }

        function toggleBackgroundMusic() {
            initAudioContext();
            if (isMusicPlaying) {
                stopBackgroundMusic();
            } else {
                startBackgroundMusic();
                playSparkleChime();
            }
        }

        function updateMusicUI() {
            const label = document.getElementById('music-label');
            const wave = document.getElementById('sound-wave');
            if (isMusicPlaying) {
                label.textContent = 'Music: On';
                wave.classList.add('playing');
            } else {
                label.textContent = 'Music: Off';
                wave.classList.remove('playing');
            }
        }

        // Sound Effect 1: Magical Sparkle Chime
        function playSparkleChime() {
            initAudioContext();
            const notes = [659.25, 880.00, 1046.50, 1318.51];
            notes.forEach((n, idx) => {
                playTone(n, 0.55, 'sine', 0.07, idx * 0.07);
            });
        }

        // Sound Effect 2: Soft Breeze Puff for Candle Blow
        function playCandleBlowSound() {
            initAudioContext();
            // Gentle descending soft chime + airy noise burst
            playTone(587.33, 0.35, 'triangle', 0.07, 0);
            playTone(440.00, 0.45, 'sine', 0.06, 0.08);
        }

        // Sound Effect 3: Happy Birthday Fanfare Chord for Cake Cut & VIP Pass
        function playCelebrationFanfare() {
            initAudioContext();
            const chord = [523.25, 659.25, 783.99, 1046.50, 1318.51];
            chord.forEach((n, i) => {
                playTone(n, 0.9, 'triangle', 0.08, i * 0.06);
            });
        }

        // Sound Effect 4: Pop & Musical Note for Nickname Orbs
        function playOrbPopNote(index) {
            initAudioContext();
            const scale = [523.25, 587.33, 659.25, 783.99, 880.00, 1046.50];
            const base = scale[index % scale.length];
            playTone(base, 0.45, 'sine', 0.09, 0);
            playTone(base * 1.5, 0.6, 'triangle', 0.06, 0.08);
        }

        /* ==============================================================
           2. TWINKLING STARLIGHT & FLOATING HEARTS CANVAS
           ============================================================== */
        const bgCanvas = document.getElementById('starlight-canvas');
        const bgCtx = bgCanvas.getContext('2d');
        let cw, ch;
        let starField = [];
        let floatingHearts = [];

        function resizeBgCanvas() {
            cw = bgCanvas.width = window.innerWidth;
            ch = bgCanvas.height = window.innerHeight;
        }
        window.addEventListener('resize', resizeBgCanvas);
        resizeBgCanvas();

        for (let i = 0; i < 70; i++) {
            starField.push({
                x: Math.random() * cw,
                y: Math.random() * ch,
                r: Math.random() * 1.8 + 0.5,
                alpha: Math.random(),
                speed: (Math.random() * 0.02 + 0.005) * (Math.random() < 0.5 ? 1 : -1)
            });
        }

        const heartSymbols = ['💖', '✨', '🌸', '💕', '👑', '💫'];
        for (let i = 0; i < 18; i++) {
            floatingHearts.push({
                x: Math.random() * cw,
                y: Math.random() * ch,
                size: Math.random() * 12 + 11,
                vy: Math.random() * 0.55 + 0.25,
                vx: (Math.random() - 0.5) * 0.35,
                sym: heartSymbols[Math.floor(Math.random() * heartSymbols.length)],
                alpha: Math.random() * 0.45 + 0.25
            });
        }

        function animateStarlight() {
            bgCtx.clearRect(0, 0, cw, ch);

            starField.forEach(s => {
                s.alpha += s.speed;
                if (s.alpha <= 0.15 || s.alpha >= 1) s.speed *= -1;
                bgCtx.beginPath();
                bgCtx.arc(s.x, s.y, s.r, 0, Math.PI * 2);
                bgCtx.fillStyle = `rgba(253, 230, 138, ${s.alpha})`;
                bgCtx.fill();
            });

            floatingHearts.forEach(h => {
                bgCtx.globalAlpha = h.alpha;
                bgCtx.font = `${h.size}px sans-serif`;
                bgCtx.fillText(h.sym, h.x, h.y);
                h.y -= h.vy;
                h.x += h.vx;
                if (h.y < -30) {
                    h.y = ch + 20;
                    h.x = Math.random() * cw;
                }
            });
            bgCtx.globalAlpha = 1;

            requestAnimationFrame(animateStarlight);
        }
        animateStarlight();

        /* ==============================================================
           3. CELEBRATION CONFETTI BURST HELPER
           ============================================================== */
        function spawnConfettiBurst(x, y, count = 24) {
            const emojis = ['🎂', '✨', '💖', '👑', '🌸', '🍬', '🍯', '🥳'];
            for (let i = 0; i < count; i++) {
                const el = document.createElement('div');
                el.className = 'burst-particle';
                el.textContent = emojis[Math.floor(Math.random() * emojis.length)];
                el.style.left = `${x}px`;
                el.style.top = `${y}px`;

                const angle = Math.random() * Math.PI * 2;
                const dist = 65 + Math.random() * 165;
                el.style.setProperty('--bx', `${Math.cos(angle) * dist}px`);
                el.style.setProperty('--by', `${Math.sin(angle) * dist - 45}px`);
                el.style.setProperty('--brot', `${(Math.random() - 0.5) * 360}deg`);

                document.body.appendChild(el);
                setTimeout(() => el.remove(), 1650);
            }
        }

        function showStage(hideId, showId, indicatorText) {
            document.getElementById(hideId).classList.add('hidden');
            document.getElementById(showId).classList.remove('hidden');
            if (indicatorText) {
                document.getElementById('stage-indicator').textContent = indicatorText;
            }
        }

        /* ==============================================================
           4. STAGE 1 -> STAGE 2 (CAKE CEREMONY)
           ============================================================== */
        function startExperience() {
            startBackgroundMusic();
            playSparkleChime();
            spawnConfettiBurst(window.innerWidth / 2, window.innerHeight / 2, 28);
            showStage('stage-1', 'stage-2', 'Stage 1/4 • 21st Cake 🎂');
        }

        let blownState = [false, false, false];

        function blowOutCandle(idx, event) {
            if (blownState[idx]) return;
            blownState[idx] = true;

            playCandleBlowSound();
            const flameEl = document.getElementById(`c-flame-${idx}`);
            flameEl.classList.add('extinguished');

            // Create smoke puff element
            const smoke = document.createElement('div');
            smoke.className = 'smoke-puff';
            flameEl.parentElement.appendChild(smoke);
            setTimeout(() => smoke.remove(), 1100);

            const cx = event.clientX || window.innerWidth / 2;
            const cy = event.clientY || window.innerHeight / 2;
            spawnConfettiBurst(cx, cy, 10);

            const leftCount = blownState.filter(v => !v).length;
            const statusText = document.getElementById('candle-counter-text');

            if (leftCount > 0) {
                statusText.textContent = `Candles lit: ${leftCount} / 3 🔥 (Baaki candles par tap karein)`;
            } else {
                statusText.textContent = `Saari candles bujh gayi! Wish poori ho gayi ✨💖`;
                document.getElementById('cake-guide').textContent = "Ab Meri Queen apne 21st Birthday ka cake cut karein! 🍰👑";
                document.getElementById('cut-cake-btn').classList.remove('hidden');
                playSparkleChime();
                spawnConfettiBurst(window.innerWidth / 2, window.innerHeight * 0.45, 30);
            }
        }

        function performCakeCut(event) {
            playCelebrationFanfare();
            document.getElementById('cake-arena').classList.add('cake-cut-active');

            const cx = event.clientX || window.innerWidth / 2;
            const cy = event.clientY || window.innerHeight / 2;
            spawnConfettiBurst(cx, cy, 36);

            document.getElementById('cut-cake-btn').classList.add('hidden');
            document.getElementById('candle-counter-text').textContent = "Happy 21st Birthday Meri Pyari Jigglu! 🎂🥂";
            document.getElementById('to-stage3-btn').classList.remove('hidden');
        }

        /* ==============================================================
           5. STAGE 3: NICKNAME & ROMANTIC COMPLIMENT CONSTELLATION
           ============================================================== */
        const nicknameOrbsData = [
            {
                icon: "💎",
                name: "Meri Kaju Barfi 💎",
                line: "Saari duniya mein bhale hi suji ka halwa ho, par mere paas toh sabse rare aur royal 'Kaju Barfi' hai—jise main hamesha sambhal kar rakhunga!"
            },
            {
                icon: "🍯",
                name: "Sweet Soan Papdi 🍯",
                line: "Bilkul meethi Soan Papdi ki tarah ho tum—jiski har ek baat aur muskaan dil mein mithaas ghol deti hai!"
            },
            {
                icon: "💪",
                name: "Daily Protein Dose 💪❤️",
                line: "Mere dil ki sabse zaroori 'Protein' ho tum—tumhari ek awaaz aur muskaan se mere poore din ki energy aur khushi double ho jati hai!"
            },
            {
                icon: "🌸",
                name: "Pyari Jigglu 🌸",
                line: "Meri Pyari Jigglu—tumhari masumiyat aur woh cute sa gussa hi toh hai jis par aapka Bhondu har roz apna dil haar baithta hai."
            },
            {
                icon: "🧸",
                name: "Mera Sona Baccha 🧸",
                line: "Duniya ke samne tum kitni bhi strong bano, par mere liye toh tum hamesha 'Mera Sona Baccha' hi rahogi—jise main hamesha pamper karunga!"
            },
            {
                icon: "👑",
                name: "Meri Janu 👑",
                line: "Meri Janu, meri Queen—21 saal ki is nayi shuruat mein tumhara har sapna poora ho, aur har kadam par tumhara Krishna tumhare saath rahega."
            }
        ];

        let orbsUnlocked = 0;

        function goToStage3() {
            playSparkleChime();
            showStage('stage-2', 'stage-3', 'Stage 2/4 • Nicknames 🌟');
            renderNicknameOrbs();
        }

        function renderNicknameOrbs() {
            const grid = document.getElementById('orbs-grid');
            grid.innerHTML = '';
            orbsUnlocked = 0;
            updateConstellationBar();

            nicknameOrbsData.forEach((item, index) => {
                const card = document.createElement('div');
                card.className = 'orb-card';
                card.innerHTML = `
                    <div class="orb-sphere">${item.icon}</div>
                    <span style="font-size: 0.78rem; font-weight: 700; color: #fde68a;">${item.name}</span>
                    <span style="font-size: 0.66rem; color: #f3e8ff; margin-top: 2px;">Tap Orb ✨</span>
                `;

                card.onclick = (e) => {
                    if (card.classList.contains('revealed')) return;
                    card.classList.add('revealed');
                    card.innerHTML = `<p class="orb-shayari">${item.line}</p>`;

                    playOrbPopNote(index);
                    const rect = card.getBoundingClientRect();
                    spawnConfettiBurst(
                        e.clientX || rect.left + rect.width / 2,
                        e.clientY || rect.top + rect.height / 2,
                        14
                    );

                    orbsUnlocked++;
                    updateConstellationBar();

                    if (orbsUnlocked === nicknameOrbsData.length) {
                        setTimeout(() => {
                            playSparkleChime();
                            document.getElementById('to-stage4-btn').classList.remove('hidden');
                            spawnConfettiBurst(window.innerWidth / 2, window.innerHeight * 0.72, 26);
                        }, 320);
                    }
                };

                grid.appendChild(card);
            });
        }

        function updateConstellationBar() {
            document.getElementById('constellation-count').textContent = `${orbsUnlocked} / 6`;
            const pct = (orbsUnlocked / nicknameOrbsData.length) * 100;
            document.getElementById('constellation-fill').style.width = `${pct}%`;
        }

        /* ==============================================================
           6. STAGE 4: SCRATCH-TO-REVEAL & ROMANTIC SHAYARI DECK
           ============================================================== */
        const romanticShayaris = [
            {
                tag: "Shayari 1 of 4 • 24 December Magic",
                text: "\"Chaand ne bhi aaj aasmaan se jhaank kar dekha hoga, jab 24 December ko meri Pyari Jigglu ne is duniya mein kadam rakha hoga.\""
            },
            {
                tag: "Shayari 2 of 4 • Eternal Loyalty",
                text: "\"Mujhe ek hi janam mila hai, aur main bas tumhara banke rehna chahta hoon—har khushi mein, har sapne mein, sirf tumhara.\""
            },
            {
                tag: "Shayari 3 of 4 • Meri Kaju Barfi",
                text: "\"Hazaron chehron ki bheed mein bhi nazrein sirf tum par aakar rukti hain, kyunki meri Kaju Barfi ki chamak sabse alag hai.\""
            },
            {
                tag: "Shayari 4 of 4 • Mera Sona Baccha",
                text: "\"Tumhari ek muskaan meri saari thakan mita deti hai, Janu—21st Birthday par bas yahi dua hai ki tum hamesha aise hi khush raho.\""
            }
        ];

        let currentShayariIdx = 0;
        let scratchRevealed = false;

        function goToStage4() {
            playSparkleChime();
            showStage('stage-3', 'stage-4', 'Stage 3/4 • Dil Ki Baatein 💫');
            setTimeout(setupScratchCard, 80);
        }

        function nextShayariCard() {
            playOrbPopNote(currentShayariIdx + 1);
            currentShayariIdx = (currentShayariIdx + 1) % romanticShayaris.length;
            const item = romanticShayaris[currentShayariIdx];
            document.getElementById('shayari-tag').textContent = item.tag;
            document.getElementById('shayari-text').textContent = item.text;
        }

        function setupScratchCard() {
            const box = document.getElementById('scratch-box');
            const canvas = document.getElementById('scratch-canvas');
            const ctx = canvas.getContext('2d');
            scratchRevealed = false;
            canvas.style.opacity = '1';
            canvas.style.pointerEvents = 'auto';

            const rect = box.getBoundingClientRect();
            canvas.width = rect.width || 360;
            canvas.height = rect.height || 165;

            // Rose-Gold Shimmer Foil Layer
            const grad = ctx.createLinearGradient(0, 0, canvas.width, canvas.height);
            grad.addColorStop(0, '#f59e0b');
            grad.addColorStop(0.5, '#f472b6');
            grad.addColorStop(1, '#d97706');
            ctx.fillStyle = grad;
            ctx.fillRect(0, 0, canvas.width, canvas.height);

            // Decorative Foil Text
            ctx.fillStyle = '#fffbeb';
            ctx.font = 'bold 16px Quicksand, sans-serif';
            ctx.textAlign = 'center';
            ctx.textBaseline = 'middle';
            ctx.fillText('✨ Scratch Here Janu (Ungli Se Ghisein) ✨', canvas.width / 2, canvas.height / 2);

            let isDrawing = false;
            let scratchMoves = 0;

            function scratchAt(clientX, clientY) {
                const bounds = canvas.getBoundingClientRect();
                const x = clientX - bounds.left;
                const y = clientY - bounds.top;

                ctx.globalCompositeOperation = 'destination-out';
                ctx.beginPath();
                ctx.arc(x, y, 24, 0, Math.PI * 2);
                ctx.fill();

                scratchMoves++;
                if (scratchMoves > 22 && !scratchRevealed) {
                    scratchRevealed = true;
                    canvas.style.opacity = '0';
                    canvas.style.pointerEvents = 'none';
                    playSparkleChime();
                    spawnConfettiBurst(bounds.left + bounds.width / 2, bounds.top + bounds.height / 2, 24);
                }
            }

            canvas.onmousedown = (e) => { isDrawing = true; scratchAt(e.clientX, e.clientY); };
            canvas.onmousemove = (e) => { if (isDrawing) scratchAt(e.clientX, e.clientY); };
            window.onmouseup = () => { isDrawing = false; };

            canvas.ontouchstart = (e) => {
                isDrawing = true;
                const t = e.touches[0];
                scratchAt(t.clientX, t.clientY);
            };
            canvas.ontouchmove = (e) => {
                if (!isDrawing) return;
                const t = e.touches[0];
                scratchAt(t.clientX, t.clientY);
            };
            canvas.ontouchend = () => { isDrawing = false; };
        }

        /* ==============================================================
           7. STAGE 5: ROYAL 21ST LETTER & COLLECTIBLE VIP PASS
           ============================================================== */
        function goToStage5() {
            playSparkleChime();
            showStage('stage-4', 'stage-5', 'Stage 4/4 • Royal Letter 👑');
            spawnConfettiBurst(window.innerWidth / 2, window.innerHeight * 0.3, 28);
        }

        function unlockVipPass(event) {
            playCelebrationFanfare();
            document.getElementById('reveal-vip-btn').classList.add('hidden');
            document.getElementById('vip-pass-card').classList.remove('hidden');
            document.getElementById('replay-confetti-btn').classList.remove('hidden');

            const cx = event.clientX || window.innerWidth / 2;
            const cy = event.clientY || window.innerHeight / 2;
            spawnConfettiBurst(cx, cy, 38);
            setTimeout(() => spawnConfettiBurst(window.innerWidth * 0.25, window.innerHeight * 0.5, 22), 220);
            setTimeout(() => spawnConfettiBurst(window.innerWidth * 0.75, window.innerHeight * 0.5, 22), 420);
        }

        function triggerReplayCelebration(event) {
            playCelebrationFanfare();
            const cx = event.clientX || window.innerWidth / 2;
            const cy = event.clientY || window.innerHeight / 2;
            spawnConfettiBurst(cx, cy, 45);
            setTimeout(() => spawnConfettiBurst(window.innerWidth * 0.5, window.innerHeight * 0.35, 35), 250);
        }
    </script>
</body>
</html>
