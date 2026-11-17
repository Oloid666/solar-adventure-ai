# Solar Adventure AI — 宇宙漫遊 V0.3

兒童互動式太陽系網頁原型。使用 iPhone Safari 或 Mac 瀏覽器開啟，選擇行星後按「飛往這裡」，主鏡頭先移到天體，太空船隨後追上。

## 使用方式

1. 選擇太陽、水星、金星、地球、月球、火星、木星、土星、天王星、海王星或冥王星。
2. 按「飛往這裡」；抵達後可閱讀各天體的特色與介紹。
3. 在地球實驗室切換自轉、公轉、四季、時差。
4. 支援 WebGL 的瀏覽器顯示 3D，否則以 Canvas 備援。

## GitHub Pages 部署

Repository → Settings → Pages → Build and deployment → Source 選 **Deploy from a branch**；Branch 選 **main**、資料夾選 **/(root)**，按 Save。稍後開啟 https://oloid666.github.io/solar-adventure-ai/ 。

## 目前限制

- V0.3 原型，星球和鏡頭可互動，但未完成正式 iPhone 13 遙控 Mac 的多人連線。
- 需要網路下載行星貼圖；未建立離線快取。
- 中文語音依賴裝置系統 TTS。
- 行星表面百科觀察點是示意文字，不是依經緯度精確落在 3D 地圖上的地標。

## 材質來源

太陽及多數行星的貼圖：Solar System Scope，透過 [Sanghel/solar-system-3d](https://github.com/Sanghel/solar-system-3d) 取得，依其說明採 **CC BY 4.0**，作者／來源為 [Solar System Scope](https://www.solarsystemscope.com/textures/)。

冥王星貼圖：New Horizons NASA / Johns Hopkins APL / Southwest Research Institute 圖資，透過 [RTF22/Orrery](https://github.com/RTF22/Orrery) 的 Pluto 地圖取得。注意：未探測區域可能缺少實際測繪資料。

這是學習與家庭探索原型，不應視為嚴格科學比例模擬。