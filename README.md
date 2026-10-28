# 3D Website

An animated 3D portfolio-style website, plus a later experiment building a 3D scroll animation without React.

## Context

| | |
|---|---|
| **Type** | Personal learning project |
| **Built** | May – July 2024 |
| **Based on** | v1 follows a React Three Fiber 3D portfolio tutorial |

## Versions

| Tag | Date | What changed |
|---|---|---|
| `v1` | May 2024 | React + Vite + Tailwind site with Hero, About, Experience, Tech, Works, Feedbacks and Contact sections |
| `v2` | Jul 2024 | `experiments/3d-ball-no-react/`: plain HTML/CSS/JS animation driven by an image sequence rendered in Blender |

## Tech

React · Vite · Tailwind CSS · Three.js · Blender · vanilla JavaScript

## Run it

```bash
npm install
npm run dev
```

The v2 experiment runs by opening `experiments/3d-ball-no-react/index.html` in a browser.

## What I learned

3D on the web with React, and then how to fake a 3D effect without a framework by playing back pre-rendered Blender frames.
