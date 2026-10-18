<div align="center">

# 🌊 ripple-lake

**A quiet lake in a mountain valley, rendered live in your browser.**
Touch the water and watch the ripples travel all the way to the far shore.

![Three.js](https://img.shields.io/badge/three.js-r160-000000?logo=threedotjs&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-GLSL-990000?logo=webgl&logoColor=white)
![Web Audio](https://img.shields.io/badge/Web%20Audio-procedural-4B32C3)
![No build](https://img.shields.io/badge/build-none-2ea44f)

</div>

---

## ✨ What's in the scene

| | |
|---|---|
| 🌊 **Living water** | A wave simulation on a perspective grid, so ripples look right up close and far away. |
| ⛰️ **The valley** | Ray-marched hills, forest, terraced fields and a distant blue mountain range. |
| 💧 **A waterfall** | A stream drops off a sheer cliff on the right-hand ridge, with spray rising from the pool below. |
| ☁️ **Sky** | Cumulus clouds drift past, and the low sun lights the ridges and shades the gullies. |
| 🔊 **Sound** | Every splash and drip is made live in the browser from ringing air bubbles. No audio files. |

## 🖐️ How to play

| Action | What happens |
|---|---|
| **Click** the water | Start the scene (and the sound) |
| **Move** the pointer | Leave a trail of ripples |
| **Click** | Make a splash |
| **Hold** | Stir the water |

Use the 🔇 button to mute.

## 🚀 Run it

It's one HTML file and there's nothing to build or install.

```bash
git clone https://github.com/sandu584/ripple-lake.git
cd ripple-lake
python3 -m http.server 8000   # then open http://localhost:8000
```

> Needs a browser with WebGL. Three.js loads from a CDN, so you need to be online.

## 🗂️ Project layout

```
ripple-lake/
├── index.html   # the whole thing: scene, shaders, water sim, sound
└── README.md
```

---

<div align="center">
<sub>Made with WebGL shaders and a love of still water.</sub>
</div>
