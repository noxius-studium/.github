<!--
  noxius-studium · Organization profile README
  HOW THE "VIDEO / DYNAMIC" STYLING WORKS:
  GitHub does NOT render <video>, <iframe>, <script>, or <canvas> in markdown.
  The moving banner below is an animated SVG using SMIL (<animate>) — those ARE
  allowed and play automatically when the README renders. If you ever host this
  on a real site (not GitHub), you can swap the inline <svg> for a real video:
  <video autoplay loop muted playsinline src="assets/banner.mp4" width="100%"></video>
  Also, every shields.io badge below is LIVE — it updates itself (stars, last
  commit, license) without you touching this file again.
-->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 260" width="100%" preserveAspectRatio="xMidYMid slice" role="img" aria-label="noxius-studium banner">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f0c29"/>
      <stop offset="50%" stop-color="#302b63"/>
      <stop offset="100%" stop-color="#24243e"/>
      <animateTransform attributeName="gradientTransform" type="rotate" from="0 0.5 0.5" to="360 0.5 0.5" dur="24s" repeatCount="indefinite"/>
    </linearGradient>
    <linearGradient id="shimmer" x1="0%" y1="0%" x2="200%" y2="0%">
      <stop offset="0%" stop-color="#ff6ec4"/>
      <stop offset="50%" stop-color="#7873f5"/>
      <stop offset="100%" stop-color="#ff6ec4"/>
      <animate attributeName="x1" values="0%;-100%" dur="3.5s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="100%;0%" dur="3.5s" repeatCount="indefinite"/>
    </linearGradient>
  </defs>

  <rect width="1000" height="260" fill="url(#bg)"/>

  <circle cx="140" cy="50" r="5" fill="#ffffff" opacity="0.5">
    <animate attributeName="cy" values="50;210;50" dur="9s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.15;0.7;0.15" dur="9s" repeatCount="indefinite"/>
  </circle>
  <circle cx="320" cy="200" r="7" fill="#ff6ec4" opacity="0.5">
    <animate attributeName="cy" values="200;40;200" dur="11s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="11s" repeatCount="indefinite"/>
  </circle>
  <circle cx="680" cy="70" r="6" fill="#7873f5" opacity="0.5">
    <animate attributeName="cy" values="70;220;70" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.2;0.65;0.2" dur="10s" repeatCount="indefinite"/>
  </circle>
  <circle cx="860" cy="190" r="5" fill="#ffffff" opacity="0.5">
    <animate attributeName="cy" values="190;60;190" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.15;0.7;0.15" dur="8s" repeatCount="indefinite"/>
  </circle>

  <text x="500" y="118" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="62" font-weight="800" fill="url(#shimmer)" letter-spacing="1">noxius-studium</text>
  <text x="500" y="162" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="22" fill="#e6e6ff" opacity="0.9">learn by building — cross-language open-source tooling</text>
  <text x="500" y="196" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="15" fill="#b9b9e6" opacity="0.8">identity · events · api patterns</text>
</svg>

> _Open-source libraries and hands-on examples — because you learn best by building the thing, not just reading about it._

---

## 🌟 About Us

- 🎯 **Focus:** developer tooling, South African identity standards, and API interoperability
- 🌍 **Languages we ship in:** C++, C#, Go, Java, JavaScript/Node, PHP, Python, Rust
- 📚 **Philosophy:** _study by building_ — every repo is a worked example, not a black box
- 🔭 **Into right now:** multi-language ID-number parity, event-driven systems, and comparing API styles side-by-side

---

## 🚀 Featured Projects

### 🪪 South African ID Validator
A cross-language toolkit for **validating, decoding, generating, and extracting** data from South African ID numbers — with identical behavior across eight languages.

**What it does**
- ✅ Checksum validation
- 🎂 Date-of-birth & gender extraction
- 📅 Age calculation (years, months, days)
- 🎲 ID-number generation (random or parameterized)
- 🧩 Decoding of ID numbers into structured models

| Language | Repository |
|----------|------------|
| C++ | [SouthAfricanIDV-cpp](https://github.com/noxius-studium/SouthAfricanIDV-cpp) |
| C# | [SouthAfricanIDV-csharp](https://github.com/noxius-studium/SouthAfricanIDV-csharp) |
| Go | [SouthAfricanIDV-go](https://github.com/noxius-studium/SouthAfricanIDV-go) |
| Java | [SouthAfricanIDV-java](https://github.com/noxius-studium/SouthAfricanIDV-java) |
| Node | [SouthAfricanIDV-node](https://github.com/noxius-studium/SouthAfricanIDV-node) |
| PHP | [SouthAfricanIDV-php](https://github.com/noxius-studium/SouthAfricanIDV-php) |
| Python | [SouthAfricanIDV-py](https://github.com/noxius-studium/SouthAfricanIDV-py) |
| Rust | [SouthAfricanIDV-rust](https://github.com/noxius-studium/SouthAfricanIDV-rust) |

![languages](https://img.shields.io/badge/implementations-8%20languages-ff6ec4?style=for-the-badge)

### ⚡ [eventflowsys](https://github.com/noxius-studium/eventflowsys)
A modern, extensible **Python** package for building robust event-driven systems — threaded **and** async event buses, group-based subscriptions, priority/TTL messaging, broadcast, event hooks, delivery metrics, and `loguru`-based logger injection. Built around SOLID principles; `pip install eventflowsys`.

[![Stars](https://img.shields.io/github/stars/noxius-studium/eventflowsys?style=for-the-badge)](https://github.com/noxius-studium/eventflowsys/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/noxius-studium/eventflowsys?style=for-the-badge)](https://github.com/noxius-studium/eventflowsys/commits)
[![License](https://img.shields.io/github/license/noxius-studium/eventflowsys?style=for-the-badge)](https://github.com/noxius-studium/eventflowsys/blob/main/LICENSE)
[![Python](https://img.shields.io/badge/language-Python-3776AB?style=for-the-badge)](https://github.com/noxius-studium/eventflowsys)

### 🔌 [soap-json-graphql-example](https://github.com/noxius-studium/soap-json-graphql-example)
A **Python** reference that exposes the *same* user CRUD operations over three protocols at once — **REST (JSON)**, **GraphQL**, and **SOAP (zeep)** — so you can compare the calling code side-by-side in one place.

[![Stars](https://img.shields.io/github/stars/noxius-studium/soap-json-graphql-example?style=for-the-badge)](https://github.com/noxius-studium/soap-json-graphql-example/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/noxius-studium/soap-json-graphql-example?style=for-the-badge)](https://github.com/noxius-studium/soap-json-graphql-example/commits)
[![Python](https://img.shields.io/badge/language-Python-3776AB?style=for-the-badge)](https://github.com/noxius-studium/soap-json-graphql-example)

### 🧱 [BaseProjects](https://github.com/noxius-studium/BaseProjects)
Shared **base templates and starter scaffolding** used across the org's Python repositories.
> _Note for you, darling: this repo has no README on GitHub, so I inferred the description from its name. Fix this line if it's actually something else._

[![Stars](https://img.shields.io/github/stars/noxius-studium/BaseProjects?style=for-the-badge)](https://github.com/noxius-studium/BaseProjects/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/noxius-studium/BaseProjects?style=for-the-badge)](https://github.com/noxius-studium/BaseProjects/commits)
[![Python](https://img.shields.io/badge/language-Python-3776AB?style=for-the-badge)](https://github.com/noxius-studium/BaseProjects)

---

## 🤝 Contributing

Issues and PRs are welcome. `eventflowsys` in particular is happy to take bug fixes, new features, and docs improvements — each repo carries its own contributing notes where they exist.


---

<p align="center"><i>"Empowering innovation, one repo at a time."</i></p>
