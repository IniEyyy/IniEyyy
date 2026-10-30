<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" alt="IniEy" width="100%">
  </picture>
</p>

I'm a computer science student who likes owning a project end to end: the interface, the data layer, and the part that has to keep working when the network doesn't. Most of my work is TypeScript and Node, with C, Python, Java and Lua for everything else.

<img src="assets/divider.svg" width="100%" alt="">

## Things I've built

**[Canvas App](https://github.com/IniEyyy/canvas-app)**
A local-first whiteboard workspace for the desktop: named boards with tags, automatic version history, cross-board links, Markdown export, 18 templates, and a one-click mind-map layout. Everything autosaves to files on your machine — no account and no connection needed. MIT licensed.
<sub>`Tauri v2` · `React 19` · `Excalidraw`</sub>

<p align="center">
  <a href="https://github.com/IniEyyy/canvas-app/blob/main/docs/canvas-trailer.mp4">
    <img src="assets/canvas-trailer-poster.png" alt="Canvas trailer: template gallery with live previews" width="100%">
  </a>
</p>
<p align="center">
  <sub>45-second walkthrough · <a href="https://github.com/IniEyyy/canvas-app/blob/main/docs/canvas-trailer.mp4">full-quality MP4</a> · <a href="https://github.com/IniEyyy/canvas-app">view code</a></sub>
</p>

<details>
<summary>How it saves your work</summary>

<p align="center">
  <img src="assets/canvas-save-flow.png" alt="Canvas save flow: Excalidraw onChange is debounced 800 ms, then saveBoard writes boards.json plus one folder per board containing board.json, assets, and snapshots." width="420">
</p>

One queued save path behind the debounce, so a slow disk cannot race the
next write. On desktop everything stays in the app-data folder: `boards.json`
indexes the library, each board keeps its own scene and snapshots, and images
are written to `assets/` instead of base64 inside the scene. In browser dev,
the same index, scenes, and snapshots go to `localStorage`.

</details>

**[Seatudy](https://github.com/IniEyyy/seatudy)**
An online learning platform with role-based access, JWT auth and real-time features.
<sub>`React` · `Vite` · `Node.js` · `Express` · `PostgreSQL` · `Socket.IO`</sub>

<p align="center">
  <a href="https://github.com/IniEyyy/seatudy">
    <img src="assets/seatudy-preview.gif" alt="Seatudy preview: student dashboard, course assignments, instructor submissions, and the admin course manager" width="100%">
  </a>
</p>
<p align="center">
  <sub>Dark-mode walkthrough · <a href="https://github.com/IniEyyy/seatudy/blob/main/docs/preview.mp4">full-quality MP4 (22s)</a></sub>
</p>

**[Jomoro Koffee](https://github.com/IniEyyy/SA)**
A system architecture project built as NestJS microservices.
<sub>`NestJS` · `Microservices`</sub>

**[Growlauncher Documentation](https://github.com/IniEyyy/Growlauncher-Documentation)** &nbsp; ![stars](https://img.shields.io/github/stars/IniEyyy/Growlauncher-Documentation?style=flat-square&color=1F6FEB&labelColor=0A1020)
API documentation for a Lua scripting tool, put together by testing each function by hand.
<sub>`Lua`</sub>

**[ML Energy Experiment](https://github.com/IniEyyy/ML-Energy-Experiment)**
An academic research experiment.

<img src="assets/divider.svg" width="100%" alt="">

## Right now

- Extending Canvas App: PDF export, media overlays, performance
- Finishing my portfolio site

<img src="assets/divider.svg" width="100%" alt="">

## Stack

<p>
  <img src="https://img.shields.io/badge/C-0A1020?style=flat-square&logo=c&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Python-0A1020?style=flat-square&logo=python&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/JavaScript-0A1020?style=flat-square&logo=javascript&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/TypeScript-0A1020?style=flat-square&logo=typescript&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Java-0A1020?style=flat-square&logo=openjdk&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Lua-0A1020?style=flat-square&logo=lua&logoColor=58A6FF">
</p>
<p>
  <img src="https://img.shields.io/badge/React-0A1020?style=flat-square&logo=react&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Astro-0A1020?style=flat-square&logo=astro&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Tailwind_CSS-0A1020?style=flat-square&logo=tailwindcss&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Flutter-0A1020?style=flat-square&logo=flutter&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Tauri-0A1020?style=flat-square&logo=tauri&logoColor=58A6FF">
</p>
<p>
  <img src="https://img.shields.io/badge/Node.js-0A1020?style=flat-square&logo=nodedotjs&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Express-0A1020?style=flat-square&logo=express&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/NestJS-0A1020?style=flat-square&logo=nestjs&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/PostgreSQL-0A1020?style=flat-square&logo=postgresql&logoColor=58A6FF">
  <img src="https://img.shields.io/badge/Socket.IO-0A1020?style=flat-square&logo=socketdotio&logoColor=58A6FF">
</p>

<img src="assets/divider.svg" width="100%" alt="">

## How I work

I use AI coding agents for implementation. The architecture, the trade-offs and the review are still mine.

Issues and discussions are open on every repo above.
