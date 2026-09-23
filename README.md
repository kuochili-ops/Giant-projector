# 𓃥 白六巨大投影機 (Giant Projector)

![Three.js](https://img.shields.io/badge/Three.js-r160-black?style=flat&logo=three.js)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

一個基於 WebGL 與 Three.js 開發的 3D 建築物光雕投影模擬器。將高亮度的動態文字與隨機主題特效（飄雪、玫瑰花海、金魚游動、Matrix 數位雨、連環煙火、Pac-Man 吃豆人等）擬真投影於 3D 建築物牆面上。

👉 **線上展示 (Demo)**：[https://kuochili-ops.github.io/Giant-projector/](https://kuochili-ops.github.io/Giant-projector/)

---

## ✨ 核心特色

- **🏢 3D 建築物光雕對齊**：精準將 Canvas 動態貼圖縫合於 14 節點的 3D 外牆，呈現擬真折角與立體投影效果。
- **🎆 隨機串場主題特效**：訊息切換時自動帶入豐富的過場動畫：
  - ❄️ **飄雪景象 (Snow)**
  - 🌹 **多層次玫瑰花海 (Roses)**
  - 🐠 **繽紛金魚游動與氣泡 (Goldfish)**
  - 🟢 **大字版 Matrix 數位雨 (Matrix)**
  - 🎆 **連環夜空煙火 (Fireworks)**
  - 🟡 **經典 Pac-Man 巨型吃豆人逆轉秀 (Pac-Man)**
- **🔗 專屬設定與訊息分享**：一鍵複製打包當前「輪播訊息」、「霓虹發光色」、「布條底色」與「播放速度」為 URL，隨時分享專屬光雕秀。
- **🎥 自動高畫質錄影與下載**：內建 Screen Capture 錄影功能，點擊後自動進行正面鏡頭錄影，完整輪播播完一輪後自動停止並下載 `.webm` 影片。

---

## 🛠️ 技術棧

- **3D 渲染引擎**：[Three.js](https://threejs.org/) (r160)
- **控制器**：OrbitControls
- **模型載入器**：GLTFLoader (`.glb` 格式)
- **前端繪圖**：HTML5 Canvas 2D / WebGL
- **錄影技術**：Web API (`MediaRecorder` & `captureStream`)

---

## 🏛️ 3D 模型來源聲明 (Model Attribution)

本專案採用的建築物 3D 模型來源資訊如下：

- **模型名稱**：`quill-_dawson_college_50_years.glb`
- **建築原型**：[Dawson College](https://www.dawsoncollege.qc.ca/) (50 Years Anniversary Model)
- **感謝**：感謝原創作者繪製並提供 3D 建築物模型供社群開發與視覺創作使用。

---

## 🚀 本地開發與運行

本專案採用純前端模組化架構（ES Modules），無須複雜建置流程：

1. **複製專案**：
   ```bash
   git clone [https://github.com/kuochili-ops/Giant-projector.git](https://github.com/kuochili-ops/Giant-projector.git)
   cd Giant-projector
