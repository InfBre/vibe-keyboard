# 工位 DAW · Cubicle DAW

浏览器里的迷你数字音乐工作站。一个 HTML 文件，零依赖、零安装。

> 上班是 KPI，下班是 BPM 🎧

## 这是什么

- 🎹 **键盘即钢琴** — A–L 弹白键，W/E/T/Y/U/O/P 弹黑键，Z/X 调八度
- 🥁 **MPC 鼓垫** — Space / Z / X / C / V / B 触发 Kick / Snare / Hi-Hat / Hat / Crash / Clap
- 🎛️ **16 种流派伴奏** — Bossa Nova / Chillwave / Drum & Bass / Funk / Chiptune / Lush Strings / Sparkling Arp / Punchy Kick / Dubstep / K Pop / Neo Soul / Trip Hop ... 点击开关，拖动调音量
- 🎚️ **16 步 Sequencer** — BPM 60–200，自动和声进行（Cmaj7 → Am7 → Fmaj7 → G7）
- 🌊 **Master FX** — Delay + Reverb 总线
- 📊 **示波器** — 实时波形可视化

## 怎么开

打开 `index.html` 就行。或者用任意静态服务器：

```bash
python3 -m http.server 3458
# 然后访问 http://localhost:3458
```

## 部署到 GitHub Pages

1. Settings → Pages
2. Source 选 `main` 分支 `/` 根目录
3. 等 30 秒拿到 `https://infbre.github.io/<repo-name>/` 链接

## 技术栈

纯原生：HTML + CSS + Web Audio API + Canvas。**0 个 npm 包**。

整个项目就一个 `index.html`，~1700 行。

## 致谢

灵感来自 [InfBre/Music-Keyboard-MIDI-Controller](https://github.com/InfBre/Music-Keyboard-MIDI-Controller) — TS/React 版本。本仓库是单文件原生版本。
