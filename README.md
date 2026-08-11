<svg width="100%" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f172a">
        <animate attributeName="stop-color" values="#0f172a;#1e1b4b;#0f172a" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#312e81">
        <animate attributeName="stop-color" values="#312e81;#4c1d95;#312e81" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#0f172a">
        <animate attributeName="stop-color" values="#0f172a;#1e1b4b;#0f172a" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#818cf8"/>
      <stop offset="50%" stop-color="#c084fc"/>
      <stop offset="100%" stop-color="#818cf8">
        <animate attributeName="offset" values="1;1.5;1" dur="3s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="1200" height="320" fill="url(#bgGrad)"/>

  <circle cx="100" cy="60" r="3" fill="#818cf8" opacity="0.7">
    <animate attributeName="cy" values="60;40;60" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1080" cy="90" r="4" fill="#c084fc" opacity="0.6">
    <animate attributeName="cy" values="90;120;90" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.15;0.6" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="250" r="2.5" fill="#38bdf8" opacity="0.5">
    <animate attributeName="cy" values="250;220;250" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="950" cy="240" r="3.5" fill="#818cf8" opacity="0.6">
    <animate attributeName="cy" values="240;270;240" dur="4.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="30" r="2" fill="#c084fc" opacity="0.5">
    <animate attributeName="cx" values="600;650;600" dur="6s" repeatCount="indefinite"/>
  </circle>

  <g transform="translate(1050,160)">
    <circle r="45" fill="none" stroke="#818cf8" stroke-width="1" opacity="0.35"/>
    <circle r="65" fill="none" stroke="#c084fc" stroke-width="1" opacity="0.2"/>
    <circle cx="45" cy="0" r="4" fill="#c084fc">
      <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-65" cy="0" r="3" fill="#818cf8">
      <animateTransform attributeName="transform" type="rotate" from="360 0 0" to="0 0 0" dur="11s" repeatCount="indefinite"/>
    </circle>
  </g>

  <text x="600" y="145" font-family="'Segoe UI', Arial, sans-serif" font-size="58" font-weight="700" fill="url(#textGrad)" text-anchor="middle" filter="url(#glow)">
    Challa Manohar
    <animate attributeName="opacity" values="0;1" dur="1.2s" fill="freeze"/>
  </text>

  <text x="600" y="190" font-family="'Segoe UI', Arial, sans-serif" font-size="22" fill="#c7d2fe" text-anchor="middle" opacity="0">
    AI &#8226; Full Stack Developer
    <animate attributeName="opacity" values="0;0;1" dur="2.4s" fill="freeze"/>
  </text>

  <rect x="500" y="205" width="0" height="3" rx="1.5" fill="url(#textGrad)">
    <animate attributeName="width" values="0;200" dur="1.4s" begin="1.8s" fill="freeze"/>
    <animate attributeName="x" values="600;500" dur="1.4s" begin="1.8s" fill="freeze"/>
  </rect>

  <text x="600" y="245" font-family="'Segoe UI', Arial, sans-serif" font-size="16" fill="#94a3b8" text-anchor="middle" opacity="0">
    Building scalable web apps with React, Node.js &amp; AI
    <animate attributeName="opacity" values="0;0;1" dur="3.2s" fill="freeze"/>
  </text>
</svg>
<svg width="600" height="260" viewBox="0 0 600 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="barGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#6366f1"/>
      <stop offset="100%" stop-color="#c084fc"/>
    </linearGradient>
  </defs>

  <text x="0" y="20" font-size="15" fill="#e2e8f0">React.js</text>
  <rect x="0" y="28" width="600" height="10" rx="5" fill="#1e293b"/>
  <rect x="0" y="28" height="10" rx="5" fill="url(#barGrad)">
    <animate attributeName="width" from="0" to="540" dur="1.6s" fill="freeze"/>
  </rect>

  <text x="0" y="70" font-size="15" fill="#e2e8f0">Node.js</text>
  <rect x="0" y="78" width="600" height="10" rx="5" fill="#1e293b"/>
  <rect x="0" y="78" height="10" rx="5" fill="url(#barGrad)">
    <animate attributeName="width" from="0" to="528" dur="1.6s" begin="0.15s" fill="freeze"/>
  </rect>

  <text x="0" y="120" font-size="15" fill="#e2e8f0">JavaScript (ES6+)</text>
  <rect x="0" y="128" width="600" height="10" rx="5" fill="#1e293b"/>
  <rect x="0" y="128" height="10" rx="5" fill="url(#barGrad)">
    <animate attributeName="width" from="0" to="552" dur="1.6s" begin="0.3s" fill="freeze"/>
  </rect>

  <text x="0" y="170" font-size="15" fill="#e2e8f0">Firebase &amp; REST APIs</text>
  <rect x="0" y="178" width="600" height="10" rx="5" fill="#1e293b"/>
  <rect x="0" y="178" height="10" rx="5" fill="url(#barGrad)">
    <animate attributeName="width" from="0" to="510" dur="1.6s" begin="0.45s" fill="freeze"/>
  </rect>

  <text x="0" y="220" font-size="15" fill="#e2e8f0">AI APIs &amp; Integration</text>
  <rect x="0" y="228" width="600" height="10" rx="5" fill="#1e293b"/>
  <rect x="0" y="228" height="10" rx="5" fill="url(#barGrad)">
    <animate attributeName="width" from="0" to="480" dur="1.6s" begin="0.6s" fill="freeze"/>
  </rect>
</svg>
<svg width="100%" height="60" viewBox="0 0 1200 60" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#6366f1"/>
      <stop offset="50%" stop-color="#c084fc"/>
      <stop offset="100%" stop-color="#38bdf8"/>
    </linearGradient>
  </defs>
  <path fill="url(#waveGrad)" opacity="0.85">
    <animate attributeName="d" dur="6s" repeatCount="indefinite"
      values="
      M0,30 C300,60 900,0 1200,30 L1200,60 L0,60 Z;
      M0,30 C300,0 900,60 1200,30 L1200,60 L0,60 Z;
      M0,30 C300,60 900,0 1200,30 L1200,60 L0,60 Z"/>
  </path>
</svg>
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch: {}
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake animation
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push snake svg to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
