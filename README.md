<h2 align="center">🧑🏻‍💻About Me</h2>

<p align="center">
  Hello, I'm David. I possess a calm and inquisitive nature, always driven to uncover the underlying causes of issues and devise effective solutions. To me, work transcends being merely a job; it is a pathway for continuous growth and development. Currently, I serve as a frontend engineer at a startup, where my responsibilities encompass web development, collaborating with project managers to define requirements, coordinating with backend developers for seamless API integration, and ensuring product compatibility across diverse devices and browsers. My experience includes working on live streaming platforms and sporting event applications. Adhering to Clean Code principles, I strive to create components that exhibit low coupling and high scalability. Additionally,I am enthusiastic about functional programming and design pattern.
</p>

<h2 align="center">🔧 Languages and Tools</h2>

<p align="center">
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
    <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
    alt="html5"
    width="40"
    height="40"
    />
  </a>
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
    <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
    alt="css3"
    width="40"
    height="40"
    />
  </a>
  <a
    href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"
    target="_blank"
    rel="noreferrer"
  >
    <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
    alt="javascript"
    width="40"
    height="40"
    />
  </a>
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer">
    <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg"
    alt="typescript"
    width="40"
    height="40"
    />
  </a>  
  <a href="https://vuejs.org/" target="_blank" rel="noreferrer">
    <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg"
    alt="vuejs"
    width="40"
    height="40"
    />
  </a>
  <a href="https://nuxtjs.org/" target="_blank" rel="noreferrer">
    <img
    src="https://www.vectorlogo.zone/logos/nuxtjs/nuxtjs-icon.svg"
    alt="nuxtjs"
    width="40"
    height="40"
    />
  </a>
  <a href="https://vitejs.dev/" target="_blank" rel="noreferrer">
    <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vitejs/vitejs-original.svg"
    alt="vite"
    width="40"
    height="40"
    />
  </a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img
    src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg"
    alt="tailwindcss"
    width="40"
    height="40"
    />
  </a>
  <a href="https://pinia.vuejs.org/" target="_blank" rel="noreferrer">
    <img
    src="https://pinia.vuejs.org/logo.svg"
    alt="pinia"
    width="40"
    height="40"
    />
  </a>
<!--   <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
    <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg"
    alt="react"
    width="40"
    height="40"
    />
  </a>
  <a href="https://nextjs.org/" target="_blank" rel="noreferrer">
    <img
    src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg"
    alt="nextjs"
    width="40"
    height="40"
    />
  </a> -->
 
  <a href="https://github.com/" target="_blank" rel="noreferrer">
    <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"
    alt="github"
    width="40"
    height="40"
    />
  </a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer">
    <img
    src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg"
    alt="docker"
    width="40"
    height="40"
    />
  </a> 
  <a href="https://postman.com" target="_blank" rel="noreferrer">
    <img
    src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg"
    alt="postman"
    width="40"
    height="40"
    />
  </a>   
  <a href="https://www.google.com/chrome/" target="_blank" rel="noreferrer">
    <img
    src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chrome/chrome-original.svg"
    alt="chrome"
    width="40"
    height="40"
    />
  </a>
</p>

<h2 align="center">💼 Project Highlights</h2>

### LINE H5 Entertainment Platform

> **Stack**: Vue 3 · Vite 5 · TypeScript · Pinia · Tailwind CSS · Socket.io · LINE LIFF SDK · GSAP · ECharts · RxJS

A full-featured H5 web application for a LINE-based online entertainment platform, covering games, payments, guilds, referral commissions, real-time chat, and more.

**Advertising & Analytics Integration**
- Integrated **Google Tag Manager (GTM)**, **Google Analytics 4 (GA4)**, and **Meta Pixel** for ad event tracking and conversion measurement
- Implemented production-only conditional loading and async script injection to avoid impacting page performance

**Performance Optimization**
- Built a **Service Worker** with differentiated cache strategies: network-first for hashed JS/CSS assets (ensuring freshness), cache-first for static resources (enabling offline access), and forced cache-busting for `index.html`
- Added **PWA support** (`manifest.json`, standalone display mode) for Add-to-Home-Screen functionality
- Integrated **browser-side image compression** (`browser-image-compression`) and custom Vue directives for lazy loading and error fallback, reducing unnecessary bandwidth usage
- Configured **Terser** to strip all `console` and `debugger` statements in production builds
- Used `import.meta.glob()` for automatic component registration and code splitting

**SEO**
- Set up **Puppeteer-based pre-rendering** (`vite-plugin-seo-prerender`) for 8 key routes, improving search engine crawlability for a SPA
- Injected `noindex` meta tags automatically in non-production environments to prevent accidental indexing

**Architecture**
- Designed a modular **Workflow + Store** architecture with 14 business workflows and 14 Pinia stores, keeping UI components decoupled from business logic
- Implemented **real-time bidirectional chat** with Socket.io
- Integrated **LINE LIFF SDK** for native LINE login, in-app payments (LINE Pay), and social sharing
- Supported **multi-environment builds** (dev / stage / uat / production) with centralized API and feature configuration

<h2 align="center">📈 GitHub Stats</h2>

<picture>
<source 
  srcset="https://github-readme-stats.vercel.app/api?username=gloriousky&show_icons=true&theme=tokyonight"
  media="(prefers-color-scheme: dark)"
/>
<source
  srcset="https://github-readme-stats.vercel.app/api?username=gloriousky&show_icons=true"
  media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
/>
<img src="https://github-readme-stats.vercel.app/api?username=gloriousky&show_icons=true" />
</picture>
