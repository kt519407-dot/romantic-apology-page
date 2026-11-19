<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meri Pyari Jigglu — Dil Se Ek Vaada 🕯️🌹</title>
    <!-- Google Fonts: Great Vibes, Playfair Display & Poppins -->
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:ital,wght@0,500;0,600;0,700;1,500;1,600&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

    <style>
        /* ==============================================================
           1. CANDLELIT VELVET ROSE & WARM BLUSH SILK THEME
           ============================================================== */
        :root {
            --velvet-abyss: #14050b;
            --velvet-crimson: #2d0918;
            --velvet-wine: #4a0e26;
            --blush-silk: #ffe4ec;
            --rose-petal: #fb7185;
            --deep-rose: #e11d48;
            --champagne-gold: #f5d08a;
            --candle-amber: #fbbf24;
            --silk-card: rgba(34, 8, 20, 0.78);
            --silk-border: rgba(245, 208, 138, 0.34);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: radial-gradient(circle at 50% 18%, var(--velvet-wine) 0%, var(--velvet-crimson) 48%, var(--velvet-abyss) 100%);
            color: var(--blush-silk);
            min-height: 100vh;
            overflow-x: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 68px 14px 30px;
            position: relative;
        }

        /* Ambient Warm Candlelight Aura */
        .ambient-glow {
            position: fixed;
            inset: 0;
            pointer-events: none;
            background: radial-gradient(circle at 50% 45%, rgba(251, 191, 36, 0.08), transparent 65%);
            transition: opacity 0.8s ease;
            z-index: 0;
        }

        /* Drifting Rose Petals & Golden Embers Canvas */
        #romance-canvas {
            position: fixed;
            inset: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .font-script {
            font-family: 'Great Vibes', cursive;
        }

        .font-editorial {
            font-family: 'Playfair Display', serif;
        }

        /* Top Minimal Romantic HUD */
        .romance-hud {
            position: fixed;
            top: 14px;
            left: 16px;
            right: 16px;
            max-width: 460px;
            margin: 0 auto;
            display: flex;
            align-items: center;
            justify-content: space-between;
            z-index: 50;
            pointer-events: none;
        }

        .hud-chapter {
            pointer-events: auto;
            background: rgba(26, 6, 15, 0.82);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(245, 208, 138, 0.35);
            color: var(--champagne-gold);
            font-size: 0.72rem;
            font-weight: 500;
            padding: 7px 14px;
            border-radius: 999px;
            letter-spacing: 0.05em;
        }

        .piano-toggle {
            pointer-events: auto;
            display: inline-flex;
            align-items: center;
            gap: 7px;
            background: linear-gradient(135deg, rgba(225, 29, 72, 0.28), rgba(45, 9, 24, 0.9));
            backdrop-filter: blur(12px);
            border: 1px solid rgba(245, 208, 138, 0.48);
            color: var(--blush-silk);
            font-family: 'Poppins', sans-serif;
            font-size: 0.73rem;
            font-weight: 500;
            padding: 7px 14px;
            border-radius: 999px;
            cursor: pointer;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.45);
            transition: transform 0.2s ease;
        }

        .piano-toggle:hover {
            transform: scale(1.04);
        }

        .pulse-bars {
            display: inline-flex;
            align-items: flex-end;
            gap: 2px;
            height: 12px;
        }

        .pulse-bars span {
            width: 2.5px;
            height: 4px;
            background: var(--champagne-gold);
            border-radius: 2px;
        }

        .pulse-bars.playing span:nth-child(1) { animation: waveNote 0.65s infinite alternate; }
        .pulse-bars.playing span:nth-child(2) { animation: waveNote 0.48s infinite alternate 0.2s; }
        .pulse-bars.playing span:nth-child(3) { animation: waveNote 0.72s infinite alternate 0.35s; }

        @keyframes waveNote {
            from { height: 4px; }
            to { height: 12px; }
        }

        /* Main Glassmorphic Velvet Container */
        .sanctuary-wrap {
            width: 100%;
            max-width: 460px;
            z-index: 10;
            position: relative;
        }

        .velvet-sanctuary {
            background: var(--silk-card);
            backdrop-filter: blur(22px);
            -webkit-backdrop-filter: blur(22px);
            border: 1.5px solid var(--silk-border);
            border-radius: 30px;
            padding: 28px 22px;
            box-shadow: 0 28px 65px rgba(0, 0, 0, 0.68), 0 0 40px rgba(225, 29, 72, 0.16);
            text-align: center;
            animation: softAppear 0.7s cubic-bezier(0.16, 1, 0.3, 1) forwards;
        }

        @keyframes softAppear {
            from { opacity: 0; transform: translateY(20px) scale(0.98); }
            to { opacity: 1; transform: translateY(0) scale(1); }
        }

        .hidden {
            display: none !important;
        }

        .intimate-pill {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            padding: 5px 14px;
            border-radius: 999px;
            background: rgba(225, 29, 72, 0.18);
            border: 1px solid rgba(245, 208, 138, 0.4);
            color: var(--champagne-gold);
            font-size: 0.7rem;
            font-weight: 500;
            letter-spacing: 0.08em;
            text-transform: uppercase;
            margin-bottom: 12px;
        }

        .champagne-title {
            background: linear-gradient(135deg, #fff1f2 8%, #f5d08a 52%, #fb7185 95%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .btn-velvet-rose {
            width: 100%;
            padding: 15px 22px;
            border: 1px solid rgba(245, 208, 138, 0.55);
            border-radius: 18px;
            background: linear-gradient(135deg, #be123c 0%, #e11d48 52%, #9f1239 100%);
            color: #fff1f2;
            font-family: 'Poppins', sans-serif;
            font-size: 0.94rem;
            font-weight: 600;
            cursor: pointer;
            box-shadow: 0 12px 28px rgba(225, 29, 72, 0.42), inset 0 1px 0 rgba(255, 255, 255, 0.25);
            transition: transform 0.22s cubic-bezier(0.34, 1.56, 0.64, 1), box-shadow 0.22s ease;
        }

        .btn-velvet-rose:hover {
            transform: translateY(-2px);
            box-shadow: 0 16px 34px rgba(225, 29, 72, 0.58);
        }

        .btn-velvet-rose:active {
            transform: scale(0.97);
        }

        /* ==============================================================
           STAGE 1: CANDLELIGHT AWAKENING
           ============================================================== */
        .candles-altar {
            display: flex;
            justify-content: center;
            align-items: flex-end;
            gap: 32px;
            height: 155px;
            margin: 16px 0 14px;
            padding-bottom: 10px;
        }

        .romantic-candle {
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            position: relative;
            transition: transform 0.25s ease;
        }

        .romantic-candle:hover {
            transform: scale(1.06);
        }

        .candle-halo {
            position: absolute;
            top: -28px;
            width: 74px;
            height: 74px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(251, 191, 36, 0.55) 0%, rgba(251, 113, 133, 0.18) 55%, transparent 75%);
            opacity: 0;
            transform: scale(0.4);
            transition: all 0.6s ease;
            pointer-events: none;
        }

        .romantic-candle.lit .candle-halo {
            opacity: 1;
            transform: scale(1.25);
        }

        .flame-drop {
            width: 15px;
            height: 26px;
            border-radius: 50% 50% 38% 38%;
            background: radial-gradient(circle at 50% 72%, #ffffff 10%, #fde047 46%, #f97316 86%, transparent 100%);
            box-shadow: 0 0 16px #fbbf24, 0 0 32px #fb7185;
            opacity: 0;
            transform: scale(0.2);
            transition: opacity 0.45s ease, transform 0.45s ease;
            margin-bottom: 3px;
        }

        .romantic-candle.lit .flame-drop {
            opacity: 1;
            transform: scale(1);
            animation: flickerGentle 0.36s infinite alternate ease-in-out;
        }

        @keyframes flickerGentle {
            0% { transform: scale(1) rotate(-2.5deg); }
            100% { transform: scale(1.07, 0.94) rotate(2.5deg); }
        }

        .candle-wick {
            width: 2.5px;
            height: 7px;
            background: #29181e;
        }

        .wax-pillar {
            width: 34px;
            border-radius: 10px 10px 6px 6px;
            background: linear-gradient(180deg, #fff1f2 0%, #fecdd3 55%, #fda4af 100%);
            box-shadow: inset 0 4px 8px rgba(255, 255, 255, 0.85), 0 10px 20px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(245, 208, 138, 0.45);
        }

        .poetic-whisper-box {
            min-height: 68px;
            background: rgba(255, 228, 236, 0.06);
            border: 1px solid rgba(245, 208, 138, 0.3);
            border-radius: 18px;
            padding: 13px 15px;
            font-size: 0.85rem;
            line-height: 1.55;
            color: var(--champagne-gold);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 16px;
        }

        /* ==============================================================
           STAGE 2: FLOATING ROSE PETALS OF LOVE
           ============================================================== */
        .petal-meadow {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
            margin: 14px 0 16px;
        }

        .petal-card {
            min-height: 112px;
            border-radius: 22px;
            padding: 13px 11px;
            background: linear-gradient(145deg, rgba(225, 29, 72, 0.24), rgba(74, 14, 38, 0.55));
            border: 1.5px solid rgba(251, 113, 133, 0.42);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.32s cubic-bezier(0.34, 1.56, 0.64, 1);
            box-shadow: 0 10px 22px rgba(0, 0, 0, 0.35);
        }

        .petal-card:nth-child(5) {
            grid-column: span 2;
        }

        .petal-card:hover {
            transform: translateY(-3px) scale(1.02);
            border-color: var(--champagne-gold);
        }

        .petal-card.bloomed {
            background: linear-gradient(145deg, rgba(245, 208, 138, 0.14), rgba(225, 29, 72, 0.26));
            border-color: var(--champagne-gold);
            cursor: default;
        }

        .petal-confession-text {
            font-family: 'Playfair Display', serif;
            font-style: italic;
            font-size: 0.84rem;
            line-height: 1.48;
            color: #fff1f2;
            animation: softFade 0.45s ease;
        }

        @keyframes softFade {
            from { opacity: 0; transform: scale(0.92); }
            to { opacity: 1; transform: scale(1); }
        }

        /* ==============================================================
           STAGE 3: WHISPER IN THE FOG (TOUCH-TO-CLEAR MIST)
           ============================================================== */
        .mist-window-frame {
            position: relative;
            width: 100%;
            height: 205px;
            margin: 14px 0 16px;
            border-radius: 24px;
            overflow: hidden;
            border: 2px solid rgba(245, 208, 138, 0.5);
            box-shadow: 0 16px 36px rgba(0, 0, 0, 0.55);
            user-select: none;
            touch-action: none;
        }

        .mist-heart-underlay {
            position: absolute;
            inset: 0;
            background: radial-gradient(circle at center, #59112e 0%, #240613 100%);
            padding: 18px 16px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .beating-bg-heart {
            position: absolute;
            font-size: 5.5rem;
            opacity: 0.16;
            animation: slowHeartBeat 1.5s infinite ease-in-out;
            pointer-events: none;
        }

        @keyframes slowHeartBeat {
            0%, 100% { transform: scale(1); }
            30% { transform: scale(1.16); }
        }

        #mist-canvas {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            cursor: crosshair;
            transition: opacity 0.6s ease;
        }

        /* ==============================================================
           STAGE 4: TWO HEARTS, ONE RHYTHM (PRESS & HOLD SYNC)
           ============================================================== */
        .dual-hearts-arena {
            position: relative;
            width: 100%;
            height: 165px;
            margin: 14px 0 12px;
            border-radius: 24px;
            background: radial-gradient(circle, rgba(225, 29, 72, 0.16) 0%, rgba(20, 5, 11, 0.85) 100%);
            border: 1px solid rgba(245, 208, 138, 0.32);
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }

        .sync-wave-ring {
            position: absolute;
            width: 90px;
            height: 90px;
            border-radius: 50%;
            border: 2px solid rgba(251, 113, 133, 0.55);
            opacity: 0;
            pointer-events: none;
        }

        .dual-hearts-arena.holding .sync-wave-ring {
            animation: pulseWaveOut 1.2s infinite ease-out;
        }

        @keyframes pulseWaveOut {
            0% { transform: scale(0.7); opacity: 0.85; }
            100% { transform: scale(2.4); opacity: 0; }
        }

        .heart-orb-left, .heart-orb-right {
            position: absolute;
            font-size: 3.3rem;
            transition: transform 0.1s linear;
            filter: drop-shadow(0 0 16px rgba(251, 113, 133, 0.75));
            user-select: none;
        }

        .heart-name-tag {
            position: absolute;
            bottom: 12px;
            font-size: 0.72rem;
            font-weight: 600;
            color: var(--champagne-gold);
            letter-spacing: 0.04em;
        }

        .hold-sync-btn {
            width: 100%;
            padding: 16px 20px;
            border-radius: 18px;
            background: linear-gradient(135deg, rgba(245, 208, 138, 0.2), rgba(225, 29, 72, 0.35));
            border: 1.5px solid var(--champagne-gold);
            color: #fff1f2;
            font-family: 'Poppins', sans-serif;
            font-size: 0.92rem;
            font-weight: 600;
            cursor: pointer;
            user-select: none;
            touch-action: none;
            transition: transform 0.2s ease, background 0.2s ease;
        }

        .hold-sync-btn:active {
            transform: scale(0.97);
            background: linear-gradient(135deg, rgba(245, 208, 138, 0.35), rgba(225, 29, 72, 0.55));
        }

        /* ==============================================================
           STAGE 5: LOVE LETTERS IN SILK ENVELOPES
           ============================================================== */
        .silk-envelopes-stack {
            display: flex;
            flex-direction: column;
            gap: 11px;
            margin: 14px 0 16px;
            text-align: left;
        }

        .silk-envelope {
            background: linear-gradient(135deg, rgba(255, 228, 236, 0.1), rgba(225, 29, 72, 0.18));
            border: 1px solid rgba(245, 208, 138, 0.38);
            border-radius: 20px;
            padding: 14px 16px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .silk-envelope:hover {
            border-color: var(--champagne-gold);
            background: linear-gradient(135deg, rgba(255, 228, 236, 0.15), rgba(225, 29, 72, 0.25));
        }

        .silk-envelope.unfolded {
            background: rgba(255, 241, 242, 0.95);
            color: #3b071c;
            border-color: var(--champagne-gold);
            box-shadow: 0 12px 26px rgba(0, 0, 0, 0.45);
        }

        .envelope-top-row {
            display: flex;
            align-items: center;
            justify-content: space-between;
            font-weight: 600;
            font-size: 0.86rem;
        }

        .wax-heart-badge {
            width: 30px;
            height: 30px;
            border-radius: 50%;
            background: radial-gradient(circle at 30% 30%, #fb7185, #be123c);
            color: #fff1f2;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-size: 0.85rem;
            box-shadow: 0 4px 10px rgba(190, 18, 60, 0.5);
        }

        .envelope-letter-body {
            margin-top: 10px;
            padding-top: 10px;
            border-top: 1px dashed rgba(159, 18, 57, 0.3);
            font-family: 'Playfair Display', serif;
            font-size: 0.88rem;
            line-height: 1.55;
            color: #2d0918;
        }

        /* ==============================================================
           STAGE 6: STRING OF DESTINY (RED THREAD OF FATE)
           ============================================================== */
        .destiny-thread-box {
            position: relative;
            padding: 14px 10px;
            margin: 14px 0 14px;
            border-radius: 22px;
            background: rgba(20, 5, 11, 0.72);
            border: 1px solid rgba(245, 208, 138, 0.32);
        }

        .thread-endpoints {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 12px 10px;
            font-family: 'Great Vibes', cursive;
            font-size: 1.65rem;
            color: var(--champagne-gold);
        }

        .knots-timeline {
            position: relative;
            display: flex;
            flex-direction: column;
            gap: 10px;
            padding: 4px 8px;
        }

        /* Glowing Red Thread Line */
        .knots-timeline::before {
            content: "";
            position: absolute;
            left: 26px;
            top: 18px;
            bottom: 18px;
            width: 3px;
            background: linear-gradient(180deg, #fb7185, #e11d48, #f5d08a);
            box-shadow: 0 0 12px #e11d48;
            border-radius: 99px;
        }

        .destiny-knot-btn {
            position: relative;
            display: flex;
            align-items: center;
            gap: 12px;
            width: 100%;
            text-align: left;
            padding: 11px 13px;
            border-radius: 16px;
            background: rgba(255, 228, 236, 0.07);
            border: 1px solid rgba(251, 113, 133, 0.35);
            color: var(--blush-silk);
            font-family: 'Poppins', sans-serif;
            cursor: pointer;
            transition: all 0.25s ease;
            z-index: 2;
        }

        .destiny-knot-btn.tied {
            background: linear-gradient(135deg, rgba(225, 29, 72, 0.25), rgba(245, 208, 138, 0.16));
            border-color: var(--champagne-gold);
        }

        .knot-jewel {
            width: 28px;
            height: 28px;
            border-radius: 50%;
            background: #4a0e26;
            border: 2px solid #fb7185;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.85rem;
            shrink: 0;
            box-shadow: 0 0 12px rgba(225, 29, 72, 0.6);
        }

        .destiny-knot-btn.tied .knot-jewel {
            background: radial-gradient(circle, #fffbeb, #f5d08a);
            border-color: #ffffff;
            box-shadow: 0 0 16px #f5d08a;
        }

        /* ==============================================================
           STAGE 7: THE MIDNIGHT VELVET RING PROPOSAL
           ============================================================== */
        .velvet-ring-box {
            width: 195px;
            height: 175px;
            margin: 14px auto 16px;
            border-radius: 26px;
            background: radial-gradient(circle at 50% 30%, #881337 0%, #4c0519 75%, #27030d 100%);
            border: 3px solid var(--champagne-gold);
            box-shadow: 0 22px 45px rgba(0, 0, 0, 0.7), 0 0 30px rgba(225, 29, 72, 0.35);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 14px;
            cursor: pointer;
            position: relative;
            transition: transform 0.35s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .velvet-ring-box:hover {
            transform: scale(1.04);
        }

        .ring-sparkle-glow {
            font-size: 3.6rem;
            filter: drop-shadow(0 0 18px rgba(255, 255, 255, 0.85));
            animation: diamondShine 1.6s infinite alternate ease-in-out;
        }

        @keyframes diamondShine {
            from { transform: scale(1) rotate(-3deg); filter: drop-shadow(0 0 12px rgba(245, 208, 138, 0.7)); }
            to { transform: scale(1.12) rotate(3deg); filter: drop-shadow(0 0 24px rgba(255, 255, 255, 1)); }
        }

        .proposal-choice-area {
            display: flex;
            flex-direction: column;
            gap: 11px;
            margin-top: 14px;
            position: relative;
            min-height: 115px;
        }

        .btn-dodge-shy {
            width: 100%;
            padding: 12px 16px;
            border-radius: 16px;
            background: rgba(255, 228, 236, 0.08);
            border: 1px solid rgba(245, 208, 138, 0.35);
            color: #fda4af;
            font-family: 'Poppins', sans-serif;
            font-size: 0.83rem;
            font-weight: 500;
            cursor: pointer;
            transition: transform 0.22s cubic-bezier(0.34, 1.56, 0.64, 1);
            user-select: none;
        }

        /* ==============================================================
           STAGE 8: OUR FOREVER LOVE VOW & KEEPSAKE
           ============================================================== */
        .keepsake-silk-frame {
            background: linear-gradient(145deg, #fff1f2 0%, #ffe4ec 52%, #fef3c7 100%);
            color: #2d0918;
            border-radius: 24px;
            padding: 5px;
            box-shadow: 0 20px 48px rgba(0, 0, 0, 0.65), 0 0 32px rgba(245, 208, 138, 0.35);
            margin: 10px 0 16px;
        }

        .keepsake-inner-border {
            border: 2px solid #be123c;
            border-radius: 20px;
            padding: 20px 16px;
            background: rgba(255, 255, 255, 0.75);
            position: relative;
        }

        .keepsake-crest {
            display: inline-block;
            background: #881337;
            color: #fde68a;
            font-size: 0.66rem;
            font-weight: 600;
            letter-spacing: 0.1em;
            text-transform: uppercase;
            padding: 4px 13px;
            border-radius: 999px;
            margin-bottom: 8px;
        }

        .keepsake-vow-text {
            font-family: 'Playfair Display', serif;
            font-size: 0.86rem;
            line-height: 1.58;
            color: #3b071c;
            margin: 10px 0 12px;
        }

        .keepsake-signature-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-top: 1px dashed rgba(136, 19, 55, 0.35);
            padding-top: 10px;
            font-size: 0.72rem;
            font-weight: 600;
            color: #881337;
        }

        /* Floating Rose Petal & Heart Burst */
        .petal-burst-item {
            position: fixed;
            pointer-events: none;
            z-index: 100;
            font-size: 1.45rem;
            animation: petalFloatBurst 1.75s cubic-bezier(0.16, 1, 0.3, 1) forwards;
        }

        @keyframes petalFloatBurst {
            0% { transform: translate(0, 0) scale(0.4) rotate(0deg); opacity: 1; }
            100% { transform: translate(var(--px), var(--py)) scale(1.3) rotate(var(--prot)); opacity: 0; }
        }
    </style>
</head>
<body>

    <div id="ambient-glow" class="ambient-glow"></div>

    <!-- Drifting Rose Petals & Golden Embers Canvas -->
    <canvas id="romance-canvas"></canvas>

    <!-- Minimal Romantic HUD -->
    <header class="romance-hud">
        <span id="hud-chapter-pill" class="hud-chapter">1 / 8 • Candlelight 🕯️</span>
        <button class="piano-toggle" onclick="toggleRomanticPiano()">
            <span id="piano-label">Music: Off</span>
            <span id="pulse-bars" class="pulse-bars">
                <span></span><span></span><span></span>
            </span>
        </button>
    </header>

    <!-- Main 8-Stage Romantic Proposal Sanctuary -->
    <main class="sanctuary-wrap">

        <!-- ==========================================================
             STAGE 1: CANDLELIGHT AWAKENING
             ========================================================== -->
        <section id="stage-1" class="velvet-sanctuary">
            <div class="intimate-pill">
                🕯️ Stage 1 of 8 • Candlelight Awakening
            </div>

            <h1 class="font-script champagne-title" style="font-size: 2.65rem; line-height: 1.15; margin-bottom: 6px;">
                Meri Pyari Jigglu (Janu) 💖
            </h1>

            <p style="font-size: 0.83rem; color: #fecdd3; line-height: 1.55;">
                Is khamosh shaam mein, dil ki roshni jalane ke liye teeno mombattiyon par tap karein... ✨
            </p>

            <!-- 3 Interactive Candles -->
            <div class="candles-altar">
                <div class="romantic-candle" id="candle-0" onclick="igniteRomanticCandle(0, event)">
                    <div class="candle-halo"></div>
                    <div class="flame-drop"></div>
                    <div class="candle-wick"></div>
                    <div class="wax-pillar" style="height: 68px;"></div>
                </div>
                <div class="romantic-candle" id="candle-1" onclick="igniteRomanticCandle(1, event)">
                    <div class="candle-halo"></div>
                    <div class="flame-drop"></div>
                    <div class="candle-wick"></div>
                    <div class="wax-pillar" style="height: 88px;"></div>
                </div>
                <div class="romantic-candle" id="candle-2" onclick="igniteRomanticCandle(2, event)">
                    <div class="candle-halo"></div>
                    <div class="flame-drop"></div>
                    <div class="candle-wick"></div>
                    <div class="wax-pillar" style="height: 74px;"></div>
                </div>
            </div>

            <div id="candle-poetry-box" class="poetic-whisper-box font-editorial" style="font-style: italic;">
                "Har mombatti ke saath mere dil ka ek raaz roshan hoga..."
            </div>

            <button id="to-stage-2-btn" class="btn-velvet-rose hidden" onclick="moveStage(1, 2, '2 / 8 • Rose Petals 🌹'); initRosePetals();">
                Enter Our Rose Sanctuary 🌹✨
            </button>
        </section>

        <!-- ==========================================================
             STAGE 2: FLOATING ROSE PETALS OF LOVE
             ========================================================== -->
        <section id="stage-2" class="velvet-sanctuary hidden">
            <div class="intimate-pill">
                🌹 Stage 2 of 8 • Petals of Love
            </div>

            <h2 class="font-editorial champagne-title" style="font-size: 1.65rem; margin-bottom: 4px;">
                Gulab Ki Pankhudiyon Mein Chhupe Ehsaas 💖
            </h2>
            <p style="font-size: 0.8rem; color: #fecdd3;">
                Har chamakti pankhudi par tap karke padho ki tumne meri zindagi kaise badal di 👇
            </p>

            <div id="petal-meadow" class="petal-meadow"></div>

            <button id="to-stage-3-btn" class="btn-velvet-rose hidden" onclick="moveStage(2, 3, '3 / 8 • Whisper in Fog 🌫️'); initMistWindow();">
                Wipe The Frosted Glass 🌫️❤️
            </button>
        </section>

        <!-- ==========================================================
             STAGE 3: WHISPER IN THE FOG (TOUCH-TO-CLEAR MIST)
             ========================================================== -->
        <section id="stage-3" class="velvet-sanctuary hidden">
            <div class="intimate-pill">
                🌫️ Stage 3 of 8 • Whisper in the Fog
            </div>

            <h2 class="font-editorial champagne-title" style="font-size: 1.65rem; margin-bottom: 4px;">
                Dhundhle Sheeshe Ke Peechhe Ek Shayari ✨
            </h2>
            <p style="font-size: 0.8rem; color: #fecdd3;">
                Apni ungli se sheeshe ki dhundh (mist) saaf karo aur dekho andar kya likha hai 👇
            </p>

            <div class="mist-window-frame" id="mist-frame">
                <div class="mist-heart-underlay">
                    <div class="beating-bg-heart">❤️</div>
                    <span style="font-size: 1.3rem; margin-bottom: 4px;">🍬🍯💖</span>
                    <p class="font-editorial" style="font-size: 0.94rem; font-style: italic; color: #fde68a; line-height: 1.5; z-index: 2;">
                        "Meri Kaju Barfi aur Soan Papdi jaisi ho tum—<br>
                        Jiski ek muskaan meri poori duniya meethi kar deti hai.<br>
                        Mujhe ek hi janam mila hai, aur main bas tumhara banke rehna chahta hoon."
                    </p>
                </div>
                <canvas id="mist-canvas"></canvas>
            </div>

            <button class="btn-velvet-rose" onclick="moveStage(3, 4, '4 / 8 • Synced Hearts 💓'); initHeartSyncStage();">
                Sync Our Heartbeats 💓✨
            </button>
        </section>

        <!-- ==========================================================
             STAGE 4: TWO HEARTS, ONE RHYTHM (PRESS & HOLD SYNC)
             ========================================================== -->
        <section id="stage-4" class="velvet-sanctuary hidden">
            <div class="intimate-pill">
                💓 Stage 4 of 8 • Two Hearts, One Rhythm
            </div>

            <h2 class="font-editorial champagne-title" style="font-size: 1.62rem; margin-bottom: 4px;">
                Do Dil, Ek Dhadkan ❤️
            </h2>
            <p style="font-size: 0.8rem; color: #fecdd3;">
                Neeche diye gaye button ko <strong>press &amp; hold</strong> karke rakho jab tak Krishna aur Priya ke dil ek na ho jayein ✨
            </p>

            <div id="dual-hearts-arena" class="dual-hearts-arena">
                <div class="sync-wave-ring"></div>
                <div id="heart-krishna" class="heart-orb-left" style="transform: translateX(-78px);">💖</div>
                <div id="heart-priya" class="heart-orb-right" style="transform: translateX(78px);">💗</div>
                <div id="sync-status-tag" class="heart-name-tag">Krishna &amp; Priya • 0% Synced</div>
            </div>

            <button id="hold-sync-btn" class="hold-sync-btn"
                onpointerdown="startHeartMerge(event)"
                onpointerup="stopHeartMerge()"
                onpointerleave="stopHeartMerge()"
                onpointercancel="stopHeartMerge()">
                Press &amp; Hold To Unite Our Hearts 🤍
            </button>

            <button id="to-stage-5-btn" class="btn-velvet-rose hidden" style="margin-top: 12px;" onclick="moveStage(4, 5, '5 / 8 • Silk Letters 💌'); initSilkEnvelopes();">
                Open Silk Love Letters 💌
            </button>
        </section>

        <!-- ==========================================================
             STAGE 5: LOVE LETTERS IN SILK ENVELOPES
             ========================================================== -->
        <section id="stage-5" class="velvet-sanctuary hidden">
            <div class="intimate-pill">
                💌 Stage 5 of 8 • Silk Love Letters
            </div>

            <h2 class="font-editorial champagne-title" style="font-size: 1.62rem; margin-bottom: 4px;">
                Reshmi Lifafon Mein Chhupe Khat 🌹
            </h2>
            <p style="font-size: 0.8rem; color: #fecdd3;">
                Har wax-sealed lifafe par tap karke apne Bhondu ke dil ki baat padho 👇
            </p>

            <div id="silk-envelopes-stack" class="silk-envelopes-stack"></div>

            <button id="to-stage-6-btn" class="btn-velvet-rose hidden" onclick="moveStage(5, 6, '6 / 8 • Red Thread 🧵')">
                Tie Our Red Thread of Destiny 🧵❤️
            </button>
        </section>

        <!-- ==========================================================
             STAGE 6: STRING OF DESTINY (RED THREAD OF FATE)
             ========================================================== -->
        <section id="stage-6" class="velvet-sanctuary hidden">
            <div class="intimate-pill">
                🧵 Stage 6 of 8 • Red Thread of Fate
            </div>

            <h2 class="font-editorial champagne-title" style="font-size: 1.62rem; margin-bottom: 4px;">
                Kismat Ki Laal Dor ✨
            </h2>
            <p style="font-size: 0.8rem; color: #fecdd3;">
                Har milestone knot par tap karke humare rishte ki dor ko mazboot karo 👇
            </p>

            <div class="destiny-thread-box">
                <div class="thread-endpoints">
                    <span>Krishna</span>
                    <span style="font-size: 1.1rem; color: #fb7185;">━━ ❤️ ━━</span>
                    <span>Priya</span>
                </div>

                <div class="knots-timeline" id="knots-timeline">
                    <button class="destiny-knot-btn" onclick="tieDestinyKnot(0, this, event)">
                        <span class="knot-jewel">1</span>
                        <div>
                            <div style="font-size: 0.82rem; font-weight: 600; color: var(--champagne-gold);">Chupke Se Dosti</div>
                            <div style="font-size: 0.73rem; color: #fecdd3;">Jahan khamosh nazron aur choti baaton se pyaar shuru hua.</div>
                        </div>
                    </button>

                    <button class="destiny-knot-btn" onclick="tieDestinyKnot(1, this, event)">
                        <span class="knot-jewel">2</span>
                        <div>
                            <div style="font-size: 0.82rem; font-weight: 600; color: var(--champagne-gold);">Har Ladai Ke Baad Aur Pyaar</div>
                            <div style="font-size: 0.73rem; color: #fecdd3;">Gussa aur narazgi ke baad bhi ek-dusre ko kabhi na chhodne ka ehsaas.</div>
                        </div>
                    </button>

                    <button class="destiny-knot-btn" onclick="tieDestinyKnot(2, this, event)">
                        <span class="knot-jewel">3</span>
                        <div>
                            <div style="font-size: 0.82rem; font-weight: 600; color: var(--champagne-gold);">2027 Ka Vaada</div>
                            <div style="font-size: 0.73rem; color: #fecdd3;">Apne sapne aur career poore karke poore maan-samman se ek hone ka vaada.</div>
                        </div>
                    </button>

                    <button class="destiny-knot-btn" onclick="tieDestinyKnot(3, this, event)">
                        <span class="knot-jewel">4</span>
                        <div>
                            <div style="font-size: 0.82rem; font-weight: 600; color: var(--champagne-gold);">Hamesha Ka Saath</div>
                            <div style="font-size: 0.73rem; color: #fecdd3;">Is janam ke har pal mein sirf tumhara banke rehne ka faisla.</div>
                        </div>
                    </button>
                </div>
            </div>

            <button id="to-stage-7-btn" class="btn-velvet-rose hidden" onclick="moveStage(6, 7, '7 / 8 • The Ring 💍')">
                Open The Velvet Ring Box 💍✨
            </button>
        </section>

        <!-- ==========================================================
             STAGE 7: THE MIDNIGHT VELVET RING PROPOSAL
             ========================================================== -->
        <section id="stage-7" class="velvet-sanctuary hidden">
            <div class="intimate-pill">
                💍 Stage 7 of 8 • Dil Ka Sawaal
            </div>

            <h2 class="font-script champagne-title" style="font-size: 2.55rem; line-height: 1.15; margin-bottom: 4px;">
                Meri Pyari Jigglu... 💖
            </h2>
            <p id="ring-box-hint" style="font-size: 0.81rem; color: #fecdd3;">
                Is crimson velvet box par tap karke apne Bhondu ke dil ka tohfa kholo ✨
            </p>

            <!-- Crimson Velvet Jewelry Box -->
            <div class="velvet-ring-box" onclick="openVelvetRingBox(event)">
                <div id="box-closed-view">
                    <div style="font-size: 2.7rem; margin-bottom: 6px;">🎁❤️</div>
                    <div class="font-editorial" style="font-size: 1rem; color: var(--champagne-gold); font-weight: 600;">
                        Crimson Velvet Box
                    </div>
                    <div style="font-size: 0.7rem; color: #fecdd3; margin-top: 3px;">(Tap to Open Clasp)</div>
                </div>

                <div id="box-opened-view" class="hidden">
                    <div class="ring-sparkle-glow">💍</div>
                    <div class="font-editorial" style="font-size: 0.92rem; color: var(--champagne-gold); font-style: italic; margin-top: 6px;">
                        Sirf Tumhare Liye, Janu ✨
                    </div>
                </div>
            </div>

            <!-- Deeply Emotional Proposal Question -->
            <div id="proposal-moment-area" class="hidden">
                <p class="font-editorial" style="font-size: 1.12rem; line-height: 1.5; color: #fff1f2; margin-bottom: 6px;">
                    "Kya tum meri zindagi ki hamesha wali humsafar banogi, Priya?" ❤️
                </p>

                <div class="proposal-choice-area">
                    <button class="btn-velvet-rose" onclick="acceptProposalForever(event)">
                        Haan, Hamesha Ke Liye! ❤️💍
                    </button>
                    <button id="shy-dodge-btn" class="btn-dodge-shy" onmouseover="dodgeShyButton()" onclick="dodgeShyButton()">
                        Abhi Sochungi 🙈
                    </button>
                </div>
            </div>
        </section>

        <!-- ==========================================================
             STAGE 8: OUR FOREVER LOVE VOW & KEEPSAKE
             ========================================================== -->
        <section id="stage-8" class="velvet-sanctuary hidden">
            <div class="intimate-pill">
                👑 Stage 8 of 8 • Forever &amp; Always
            </div>

            <div class="keepsake-silk-frame">
                <div class="keepsake-inner-border">
                    <span class="keepsake-crest">✨ Official Forever Love Vow ✨</span>
                    <h2 class="font-script" style="font-size: 2.4rem; color: #881337; line-height: 1.1;">
                        Krishna ♥ Priya
                    </h2>
                    <div style="font-size: 0.74rem; font-weight: 600; color: #9f1239; letter-spacing: 0.04em;">
                        24 December 2026 • Sealed in Love &amp; Trust
                    </div>

                    <p class="keepsake-vow-text">
                        "Meri <strong>Pyari Jigglu, Janu, Kaju Barfi, Soan Papdi,</strong> aur <strong>Meri Protein</strong>—aaj is pal se mera har kal, meri har dua aur meri poori zindagi sirf tumhare naam hai. Main hamesha tumhari izzat, tumhari azaadi aur tumhari muskaan ki hifazat karunga."
                    </p>

                    <div class="keepsake-signature-row">
                        <span>Tumhara Apna: Krishna 💍</span>
                        <span>Forever &amp; Always ❤️</span>
                    </div>
                </div>
            </div>

            <button class="btn-velvet-rose" onclick="showerMorePetals(event)">
                Shower More Rose Petals &amp; Love 🌹✨
            </button>
        </section>

    </main>

    <script>
        /* ==============================================================
           1. WEB AUDIO API: SOFT ROMANTIC MUSIC BOX & WARM PIANO PAD
           ============================================================== */
        let audioCtx = null;
        let pianoPlaying = false;
        let pianoLoopTimer = null;
        let melodyIndex = 0;

        // Warm Romantic Piano & Music-Box Progression (F Major 7 -> C Major -> D Minor 7 -> Bb Major 7)
        const romanticNotes = [
            698.46, 880.00, 1046.50, 1318.51, // F5 A5 C6 E6
            1046.50, 880.00, 783.99, 659.25,  // C6 A5 G5 E5
            587.33, 698.46, 880.00, 1046.50,  // D5 F5 A5 C6
            932.33, 880.00, 698.46, 659.25    // Bb5 A5 F5 E5
        ];

        function ensureRomanticAudio() {
            if (!audioCtx) {
                const Ctx = window.AudioContext || window.webkitAudioContext;
                audioCtx = new Ctx();
            }
            if (audioCtx.state === 'suspended') {
                audioCtx.resume();
            }
        }

        function playWarmNote(freq, duration = 1.1, wave = 'sine', peakVol = 0.06, delay = 0) {
            if (!audioCtx) return;
            const start = audioCtx.currentTime + delay;
            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();
            osc.type = wave;
            osc.frequency.setValueAtTime(freq, start);

            gain.gain.setValueAtTime(0.0001, start);
            gain.gain.exponentialRampToValueAtTime(peakVol, start + 0.05);
            gain.gain.exponentialRampToValueAtTime(0.0001, start + duration);

            osc.connect(gain);
            gain.connect(audioCtx.destination);
            osc.start(start);
            osc.stop(start + duration + 0.06);
        }

        function startRomanticPiano() {
            ensureRomanticAudio();
            if (pianoPlaying) return;
            pianoPlaying = true;
            syncPianoHud();

            pianoLoopTimer = setInterval(() => {
                if (!pianoPlaying) return;
                const note = romanticNotes[melodyIndex % romanticNotes.length];
                playWarmNote(note, 1.5, 'sine', 0.052, 0);
                if (melodyIndex % 4 === 0) {
                    // Warm soft bass pad undertone
                    playWarmNote(note * 0.25, 2.2, 'triangle', 0.04, 0.02);
                }
                melodyIndex++;
            }, 680);
        }

        function stopRomanticPiano() {
            pianoPlaying = false;
            if (pianoLoopTimer) clearInterval(pianoLoopTimer);
            syncPianoHud();
        }

        function toggleRomanticPiano() {
            ensureRomanticAudio();
            if (pianoPlaying) {
                stopRomanticPiano();
            } else {
                startRomanticPiano();
                playRomanticChime();
            }
        }

        function syncPianoHud() {
            const lbl = document.getElementById('piano-label');
            const bars = document.getElementById('pulse-bars');
            if (pianoPlaying) {
                lbl.textContent = 'Music: On';
                bars.classList.add('playing');
            } else {
                lbl.textContent = 'Music: Off';
                bars.classList.remove('playing');
            }
        }

        function playRomanticChime() {
            ensureRomanticAudio();
            [523.25, 659.25, 783.99, 1046.50].forEach((f, i) => {
                playWarmNote(f, 0.85, 'sine', 0.06, i * 0.08);
            });
        }

        function playSoftHeartbeat(intensity = 1) {
            ensureRomanticAudio();
            playWarmNote(110 * intensity, 0.22, 'sine', 0.11, 0);
            playWarmNote(146.83 * intensity, 0.28, 'sine', 0.08, 0.14);
        }

        function playGrandProposalChord() {
            ensureRomanticAudio();
            [349.23, 523.25, 659.25, 880.00, 1046.50, 1318.51].forEach((f, idx) => {
                playWarmNote(f, 1.6, 'sine', 0.065, idx * 0.07);
            });
        }

        /* ==============================================================
           2. DRIFTING ROSE PETALS & GOLDEN CANDLE EMBERS CANVAS
           ============================================================== */
        const rCanvas = document.getElementById('romance-canvas');
        const rCtx = rCanvas.getContext('2d');
        let cw, ch;
        const driftingItems = [];

        function resizeRomanceCanvas() {
            cw = rCanvas.width = window.innerWidth;
            ch = rCanvas.height = window.innerHeight;
        }
        window.addEventListener('resize', resizeRomanceCanvas);
        resizeRomanceCanvas();

        const ambientSymbols = ['🌹', '🌸', '✨', '💖', '🥀'];
        for (let i = 0; i < 22; i++) {
            driftingItems.push({
                x: Math.random() * cw,
                y: Math.random() * ch,
                size: Math.random() * 13 + 11,
                vy: Math.random() * 0.55 + 0.22,
                vx: (Math.random() - 0.5) * 0.45,
                wobble: Math.random() * Math.PI * 2,
                sym: ambientSymbols[Math.floor(Math.random() * ambientSymbols.length)],
                alpha: Math.random() * 0.45 + 0.25
            });
        }

        function renderRomanceAtmosphere() {
            rCtx.clearRect(0, 0, cw, ch);
            driftingItems.forEach(p => {
                p.wobble += 0.02;
                p.y += p.vy;
                p.x += p.vx + Math.sin(p.wobble) * 0.3;

                if (p.y > ch + 25) {
                    p.y = -20;
                    p.x = Math.random() * cw;
                }
                if (p.x < -20) p.x = cw + 20;
                if (p.x > cw + 20) p.x = -20;

                rCtx.globalAlpha = p.alpha;
                rCtx.font = `${p.size}px sans-serif`;
                rCtx.fillText(p.sym, p.x, p.y);
            });
            rCtx.globalAlpha = 1;
            requestAnimationFrame(renderRomanceAtmosphere);
        }
        renderRomanceAtmosphere();

        /* ==============================================================
           3. CELEBRATORY PETAL BURST & STAGE TRANSITION
           ============================================================== */
        function burstRosePetals(x, y, count = 24) {
            const set = ['🌹', '💖', '✨', '🌸', '❤️', '💍', '🥂'];
            for (let i = 0; i < count; i++) {
                const el = document.createElement('div');
                el.className = 'petal-burst-item';
                el.textContent = set[Math.floor(Math.random() * set.length)];
                el.style.left = `${x}px`;
                el.style.top = `${y}px`;

                const ang = Math.random() * Math.PI * 2;
                const dist = 65 + Math.random() * 165;
                el.style.setProperty('--px', `${Math.cos(ang) * dist}px`);
                el.style.setProperty('--py', `${Math.sin(ang) * dist - 45}px`);
                el.style.setProperty('--prot', `${(Math.random() - 0.5) * 340}deg`);

                document.body.appendChild(el);
                setTimeout(() => el.remove(), 1750);
            }
        }

        function moveStage(fromNum, toNum, hudLabel) {
            document.getElementById(`stage-${fromNum}`).classList.add('hidden');
            document.getElementById(`stage-${toNum}`).classList.remove('hidden');
            document.getElementById('hud-chapter-pill').textContent = hudLabel;
        }

        /* ==============================================================
           4. STAGE 1: CANDLELIGHT AWAKENING
           ============================================================== */
        const litCandles = [false, false, false];
        const candleWhispers = [
            "\"Pehli roshni tumhari us masoom muskaan ke naam, jo meri har udaasi mita deti hai...\" 🕯️",
            "\"Doosri roshni hamare us bharose ke naam, jo har mushkil mein aur gehra hota gaya...\" ✨",
            "\"Teesri roshni hamare aane wale kal ke naam—jahan sirf tum aur main honge, meri Janu!\" ❤️"
        ];

        function igniteRomanticCandle(idx, ev) {
            startRomanticPiano();
            if (litCandles[idx]) return;
            litCandles[idx] = true;

            document.getElementById(`candle-${idx}`).classList.add('lit');
            playWarmNote(523.25 + idx * 130, 1.0, 'sine', 0.08, 0);

            const litTotal = litCandles.filter(Boolean).length;
            document.getElementById('candle-poetry-box').textContent = candleWhispers[litTotal - 1];
            document.getElementById('ambient-glow').style.background =
                `radial-gradient(circle at 50% 45%, rgba(251, 191, 36, ${0.08 + litTotal * 0.06}), transparent 68%)`;

            burstRosePetals(ev.clientX || window.innerWidth / 2, ev.clientY || window.innerHeight * 0.45, 14);

            if (litTotal === 3) {
                playRomanticChime();
                document.getElementById('to-stage-2-btn').classList.remove('hidden');
            }
        }

        /* ==============================================================
           5. STAGE 2: FLOATING ROSE PETALS OF LOVE
           ============================================================== */
        const lovePetalsData = [
            {
                title: "Pehli Nazar Se Aaj Tak 🌹",
                line: "\"Pehli nazar se lekar aaj tak, meri aankhon ne sirf tumhari hi khushi aur muskaan ki dua maangi hai.\""
            },
            {
                title: "Meri Pyari Jigglu & Janu 💖",
                line: "\"Meri Pyari Jigglu aur Janu—tumhare bina meri har subah aur har shaam adhoori si lagti hai.\""
            },
            {
                title: "Tumhari Har Muskurahat ✨",
                line: "\"Tumhari har muskurahat meri duniya hai, aur us muskaan ko bachaye rakhna mera sabse bada farz.\""
            },
            {
                title: "Meri Kaju Barfi & Soan Papdi 🍬",
                line: "\"Duniya ki saari mithas ek taraf, aur meri Kaju Barfi aur Soan Papdi ki pyari baatein ek taraf!\""
            },
            {
                title: "Meri Protein & Dil Ka Sukoon 💪❤️",
                line: "\"Tum meri daily Protein dose ho Janu—tumhari ek awaaz se mere dil ko poori duniya ki taqat mil jati hai.\""
            }
        ];

        let bloomedPetals = 0;

        function initRosePetals() {
            playRomanticChime();
            const meadow = document.getElementById('petal-meadow');
            meadow.innerHTML = '';
            bloomedPetals = 0;

            lovePetalsData.forEach((item, idx) => {
                const card = document.createElement('div');
                card.className = 'petal-card';
                card.innerHTML = `
                    <span style="font-size: 1.65rem; margin-bottom: 4px;">🌹</span>
                    <span style="font-size: 0.78rem; font-weight: 600; color: var(--champagne-gold);">${item.title}</span>
                    <span style="font-size: 0.66rem; color: #fecdd3; margin-top: 2px;">Tap Petal ✨</span>
                `;

                card.onclick = (ev) => {
                    if (card.classList.contains('bloomed')) return;
                    card.classList.add('bloomed');
                    card.innerHTML = `<p class="petal-confession-text">${item.line}</p>`;

                    playWarmNote(587.33 + idx * 75, 0.75, 'sine', 0.075, 0);
                    const rect = card.getBoundingClientRect();
                    burstRosePetals(ev.clientX || rect.left + rect.width / 2, ev.clientY || rect.top + rect.height / 2, 12);

                    bloomedPetals++;
                    if (bloomedPetals === lovePetalsData.length) {
                        playRomanticChime();
                        document.getElementById('to-stage-3-btn').classList.remove('hidden');
                    }
                };
                meadow.appendChild(card);
            });
        }

        /* ==============================================================
           6. STAGE 3: WHISPER IN THE FOG (TOUCH-TO-CLEAR MIST)
           ============================================================== */
        let mistCleared = false;

        function initMistWindow() {
            playRomanticChime();
            const frame = document.getElementById('mist-frame');
            const canvas = document.getElementById('mist-canvas');
            const ctx = canvas.getContext('2d');
            mistCleared = false;
            canvas.style.opacity = '1';
            canvas.style.pointerEvents = 'auto';

            const rect = frame.getBoundingClientRect();
            canvas.width = rect.width || 360;
            canvas.height = rect.height || 205;

            // Frosted Rose-Mist Overlay
            const mistGrad = ctx.createLinearGradient(0, 0, canvas.width, canvas.height);
            mistGrad.addColorStop(0, 'rgba(255, 228, 236, 0.92)');
            mistGrad.addColorStop(0.5, 'rgba(251, 207, 232, 0.94)');
            mistGrad.addColorStop(1, 'rgba(244, 114, 182, 0.88)');
            ctx.fillStyle = mistGrad;
            ctx.fillRect(0, 0, canvas.width, canvas.height);

            ctx.fillStyle = '#4a0e26';
            ctx.font = '600 15px Poppins, sans-serif';
            ctx.textAlign = 'center';
            ctx.textBaseline = 'middle';
            ctx.fillText('🌫️ Ungli Se Dhundh Saaf Karein (Wipe Mist) ✨', canvas.width / 2, canvas.height / 2);

            let rubbing = false;
            let wipeCount = 0;

            function wipeMistAt(cx, cy) {
                const bounds = canvas.getBoundingClientRect();
                const x = cx - bounds.left;
                const y = cy - bounds.top;

                ctx.globalCompositeOperation = 'destination-out';
                ctx.beginPath();
                ctx.arc(x, y, 28, 0, Math.PI * 2);
                ctx.fill();

                wipeCount++;
                if (wipeCount > 24 && !mistCleared) {
                    mistCleared = true;
                    canvas.style.opacity = '0';
                    canvas.style.pointerEvents = 'none';
                    playRomanticChime();
                    burstRosePetals(bounds.left + bounds.width / 2, bounds.top + bounds.height / 2, 24);
                }
            }

            canvas.onpointerdown = (e) => { rubbing = true; wipeMistAt(e.clientX, e.clientY); };
            canvas.onpointermove = (e) => { if (rubbing) wipeMistAt(e.clientX, e.clientY); };
            window.onpointerup = () => { rubbing = false; };
        }

        /* ==============================================================
           7. STAGE 4: TWO HEARTS, ONE RHYTHM (PRESS & HOLD SYNC)
           ============================================================== */
        let syncProgress = 0;
        let syncInterval = null;
        let heartsUnited = false;

        function initHeartSyncStage() {
            playRomanticChime();
            syncProgress = 0;
            heartsUnited = false;
            updateHeartPositions();
        }

        function startHeartMerge(ev) {
            if (ev) ev.preventDefault();
            if (heartsUnited) return;

            document.getElementById('dual-hearts-arena').classList.add('holding');
            playSoftHeartbeat(1);

            if (syncInterval) clearInterval(syncInterval);
            syncInterval = setInterval(() => {
                if (heartsUnited) return;
                syncProgress = Math.min(100, syncProgress + 4);
                updateHeartPositions();

                if (syncProgress % 24 === 0) {
                    playSoftHeartbeat(1 + syncProgress / 200);
                }

                if (syncProgress >= 100) {
                    heartsUnited = true;
                    clearInterval(syncInterval);
                    document.getElementById('dual-hearts-arena').classList.remove('holding');
                    document.getElementById('heart-krishna').textContent = '💞';
                    document.getElementById('heart-priya').classList.add('hidden');
                    document.getElementById('sync-status-tag').textContent = 'Krishna ♥ Priya • 100% Ek Dhadkan ✨';
                    document.getElementById('hold-sync-btn').textContent = 'Hamare Dil Ek Ho Gaye ❤️';
                    document.getElementById('to-stage-5-btn').classList.remove('hidden');

                    playGrandProposalChord();
                    burstRosePetals(window.innerWidth / 2, window.innerHeight * 0.45, 30);
                }
            }, 65);
        }

        function stopHeartMerge() {
            document.getElementById('dual-hearts-arena').classList.remove('holding');
            if (syncInterval) clearInterval(syncInterval);
        }

        function updateHeartPositions() {
            const offset = 78 * (1 - syncProgress / 100);
            document.getElementById('heart-krishna').style.transform = `translateX(${-offset}px) scale(${1 + syncProgress / 350})`;
            document.getElementById('heart-priya').style.transform = `translateX(${offset}px) scale(${1 + syncProgress / 350})`;
            if (!heartsUnited) {
                document.getElementById('sync-status-tag').textContent = `Krishna & Priya • ${syncProgress}% Synced`;
            }
        }

        /* ==============================================================
           8. STAGE 5: LOVE LETTERS IN SILK ENVELOPES
           ============================================================== */
        const silkLettersData = [
            {
                title: "1. Meri Protein & Taqat 💪❤️",
                body: "Jab bhi zindagi thakati hai ya mann udaas hota hai, tumhari ek muskaan aur tumhari baatein mere liye sabse zaroori 'Protein' ban jati hain. Tum meri har khushi ki wajah ho, Janu."
            },
            {
                title: "2. Tumhari Azaadi & Sapne 🕊️⚖️",
                body: "Main kabhi tumhare sapnon ya azaadi ke beech deewar nahi banunga. Jab meri Advocate Sahiba apni manzil par chamkengi, toh sabse zyada garv aur khushi tumhare is Bhondu ko hogi."
            },
            {
                title: "3. Har Galti Ki Maafi 🥺🌹",
                body: "Agar kabhi anjaane mein meri kisi baat se tumhara dil dukha ho, toh main dil se maafi maangta hoon. Main har roz khud ko behtar banaunga taaki tumhe sirf pyaar aur sukoon mile."
            },
            {
                title: "4. 2027 Aur Poori Zindagi 💍✨",
                body: "Abhi hum apne milestones aur sahi waqt ka intezar kar rahe hain, par 2027 aur uske baad ki har subah main poore maan-samman ke saath sirf tumhare saath jeena chahta hoon."
            }
        ];

        let openedEnvelopesCount = 0;

        function initSilkEnvelopes() {
            playRomanticChime();
            const stack = document.getElementById('silk-envelopes-stack');
            stack.innerHTML = '';
            openedEnvelopesCount = 0;

            silkLettersData.forEach((letter, idx) => {
                const env = document.createElement('div');
                env.className = 'silk-envelope';
                env.innerHTML = `
                    <div class="envelope-top-row">
                        <span>${letter.title}</span>
                        <span class="wax-heart-badge">♥</span>
                    </div>
                    <div class="envelope-letter-body hidden">${letter.body}</div>
                `;

                env.onclick = (ev) => {
                    const bodyEl = env.querySelector('.envelope-letter-body');
                    if (!bodyEl.classList.contains('hidden')) return;
                    bodyEl.classList.remove('hidden');
                    env.classList.add('unfolded');

                    playWarmNote(659.25 + idx * 80, 0.8, 'sine', 0.075, 0);
                    burstRosePetals(ev.clientX || window.innerWidth / 2, ev.clientY || window.innerHeight / 2, 12);

                    openedEnvelopesCount++;
                    if (openedEnvelopesCount === silkLettersData.length) {
                        playRomanticChime();
                        document.getElementById('to-stage-6-btn').classList.remove('hidden');
                    }
                };
                stack.appendChild(env);
            });
        }

        /* ==============================================================
           9. STAGE 6: STRING OF DESTINY (RED THREAD OF FATE)
           ============================================================== */
        let tiedKnotsCount = 0;

        function tieDestinyKnot(idx, btnEl, ev) {
            if (btnEl.classList.contains('tied')) return;
            btnEl.classList.add('tied');
            btnEl.querySelector('.knot-jewel').textContent = '🎀';

            playWarmNote(587.33 + idx * 95, 0.85, 'sine', 0.08, 0);
            burstRosePetals(ev.clientX || window.innerWidth / 2, ev.clientY || window.innerHeight / 2, 12);

            tiedKnotsCount++;
            if (tiedKnotsCount === 4) {
                playRomanticChime();
                document.getElementById('to-stage-7-btn').classList.remove('hidden');
            }
        }

        /* ==============================================================
           10. STAGE 7: THE MIDNIGHT VELVET RING PROPOSAL
           ============================================================== */
        let ringBoxOpened = false;

        function openVelvetRingBox(ev) {
            if (ringBoxOpened) return;
            ringBoxOpened = true;
            playGrandProposalChord();

            document.getElementById('box-closed-view').classList.add('hidden');
            document.getElementById('box-opened-view').classList.remove('hidden');
            document.getElementById('ring-box-hint').textContent = "Dil ki har dhadkan sirf tumhara jawaab sunna chahti hai... 💖";
            document.getElementById('proposal-moment-area').classList.remove('hidden');

            burstRosePetals(ev.clientX || window.innerWidth / 2, ev.clientY || window.innerHeight * 0.4, 28);
        }

        let shyAttempts = 0;
        const shyDodgeWhispers = [
            "Arey Janu, itna mat sharmao! Upar wala dabao ❤️",
            "Bhondu ka dil todogi kya? 'Haan' bol do na 🥺",
            "Kaju Barfi aur Soan Papdi pakki hai, maan jao 🍬💖",
            "Yeh button kaam nahi karega, sirf upar wala ❤️💍"
        ];

        function dodgeShyButton() {
            const btn = document.getElementById('shy-dodge-btn');
            btn.textContent = shyDodgeWhispers[shyAttempts % shyDodgeWhispers.length];
            shyAttempts++;

            const dx = Math.floor(Math.random() * 120) - 60;
            const dy = Math.floor(Math.random() * 60) - 30;
            btn.style.transform = `translate(${dx}px, ${dy}px)`;
        }

        function acceptProposalForever(ev) {
            playGrandProposalChord();
            const cx = ev.clientX || window.innerWidth / 2;
            const cy = ev.clientY || window.innerHeight / 2;
            burstRosePetals(cx, cy, 42);

            moveStage(7, 8, '8 / 8 • Forever Vow 👑');
            setTimeout(() => burstRosePetals(window.innerWidth * 0.25, window.innerHeight * 0.4, 26), 250);
            setTimeout(() => burstRosePetals(window.innerWidth * 0.75, window.innerHeight * 0.4, 26), 450);
        }

        function showerMorePetals(ev) {
            playGrandProposalChord();
            const cx = ev.clientX || window.innerWidth / 2;
            const cy = ev.clientY || window.innerHeight / 2;
            burstRosePetals(cx, cy, 45);
        }
    </script>
</body>
</html
