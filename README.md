<div align="center">

  <h1>Little Ba (小八)</h1>

  <p>
    <strong>A narrative pixel-art album about a stray cat, a cold winter, and a warm goodbye.</strong>
  </p>

  <p>
    <a href="https://godotengine.org"><img src="https://img.shields.io/badge/Godot-4.4-478cbf?logo=godotengine&logoColor=white" alt="Godot 4.4"></a>
    <a href="#"><img src="https://img.shields.io/badge/Platform-Web%20(HTML5)-orange" alt="Web"></a>
    <a href="#"><img src="https://img.shields.io/badge/Style-Pixel%20Art-purple" alt="Pixel Art"></a>
  </p>

  <h3>
    <a href=https://little-ba-story.vercel.app/>Play in Browser (Vercel)</a>
    <span> | </span>
    <a href=https://yiyueqiao.itch.io/little-ba-story>Play on Itch.io</a>
  </h3>
  
  <p><em>📱 Optimized for Mobile (Landscape Mode) & Desktop</em></p>

</div>

---

## 📖 About The Project

Last winter, under the dim light of a streetlamp, I found a shivering stray cat. She had a peculiar marking on her forehead that looked exactly like the Chinese character **'八'** (Eight). So, I named her **Little Ba**.

This project is not just a game; it is a **digital interactive album**. I built it to preserve the memories of our brief time together—from the rescue and her first bath, to finding her a forever home.

> 去年冬天，我遇到了一只额头上有“八”字花纹的流浪猫。这个项目不仅仅是一个游戏，更是一本互动的数字相册，用来纪念那段温暖的时光。

## 🎮 Features

* **Interactive Storytelling:** 4 chapters of narrative gameplay (Encounter, Bath, Companionship, Farewell).
* **Cozy Aesthetics:** Hand-drawn 16-bit pixel art style (640x360 resolution).
* **Mobile-First Design:** Custom `DisplayServer` logic to detect device orientation and guide users to landscape mode.
* **Analytics:** Integrated **PostHog** for custom event tracking (e.g., scene completion, user engagement).

## 🛠️ Tech Stack

This project was built to explore the intersection of **Narrative Art** and **Web Engineering**.

* **Engine:** Godot 4.4 (Stable)
* **Language:** GDScript
* **Export:** WebAssembly (Wasm) / HTML5
* **Analytics:** PostHog Integration
* **Deployment:** Vercel / GitHub Pages / Itch.io
* **AI Co-pilot:** Developed with the assistance of **Google Gemini** for architecture planning and script optimization.

## 💻 Tech Stack details

This repository contains the **web export build** of the project.
The source code is written in GDScript using Godot 4.4.

* **Core Logic:** Custom state machine for scene transitions.
* **Mobile Support:** `DisplayServer` integration for orientation detection.
* **Rendering:** WebGL 2.0 (via Godot WebAssembly).

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
  <p>Made with ❤️ and ☕ by Yiyue Qiao</p>
  <p>
    <a href=www.linkedin.com/in/yiyue-joanna-qiao-2a6415184>LinkedIn</a> • 
    <a href=https://x.com/JoannaQYY>X (Twitter)</a>
  </p>
</div>
