<div align="center">

<!-- Monochrome Wave Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:09090b,50:18181b,100:27272a&height=150&section=header&animation=fadeIn" width="100%" />

# Saurabh Thapliyal
**Creative Frontend Developer** &nbsp;·&nbsp; `saurow`

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=400&size=13&duration=3200&pause=1200&color=A1A1AA&center=true&vCenter=true&width=600&lines=WebGPU+%C2%B7+Three.js+%C2%B7+TSL+Node+Materials+%C2%B7+GSAP;Design+engineering%2C+real-time+3D+%26+choreographed+motion." alt="Typing SVG" />
</a>

<br/>

<p align="center">
  <a href="https://saurow.vercel.app"><kbd>&nbsp;↗ Portfolio&nbsp;</kbd></a>&nbsp;&nbsp;
  <a href="https://blog-saurow.vercel.app"><kbd>&nbsp;↗ Technical Blog&nbsp;</kbd></a>&nbsp;&nbsp;
  <a href="https://linkedin.com/in/saurabh-thapliyal-76a0a6306"><kbd>&nbsp;↗ LinkedIn&nbsp;</kbd></a>&nbsp;&nbsp;
  <a href="https://x.com/"><kbd>&nbsp;↗ X / Twitter&nbsp;</kbd></a>
</p>

</div>

<br/>

---

## `01` &nbsp;Overview

<table width="100%">
  <tr>
    <td width="54%" valign="top">
      <p>I build interactive web experiences focused on motion architecture, custom shaders, and real-time 3D in the browser.</p>
      <p>Most of my current work revolves around <b>Three.js Shading Language (TSL)</b>, <b>WebGPU</b> node materials, and tight scroll choreography using <b>GSAP</b> and <b>Lenis</b>.</p>
      <p>When I'm not pushing vertices or fine-tuning easing curves, I'm usually writing technical breakdowns on my blog, recording guitar in Ableton, or queuing CS2.</p>
    </td>
    <td width="46%" valign="middle">
<pre lang="ts">
// shader.tsl.ts
import { Fn, uv, time, sin, vec3, mix } from 'three/tsl';

export const waveDisplacement = Fn(([position]) => {
  const st = uv();
  const wave = sin(st.x.mul(6.0).add(time.mul(1.5))).mul(0.15);

  return vec3(
    position.x,
    position.y.add(wave),
    position.z.add(wave.mul(0.5))
  );
});
</pre>
    </td>
  </tr>
</table>

<br/>

---

## `02` &nbsp;Stack & Tools

<div align="center">

<br/>

<img src="https://skillicons.dev/icons?i=nextjs,react,threejs,ts,js,scss,cpp,python,git,github,figma,linux&perline=6&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/Three.js_TSL-121212?style=for-the-badge&logo=threedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/WebGPU-121212?style=for-the-badge&logo=w3c&logoColor=005A9C" />
<img src="https://img.shields.io/badge/React_Three_Fiber-121212?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/WebGL-121212?style=for-the-badge&logo=webgl&logoColor=990000" />
<br/>
<img src="https://img.shields.io/badge/GSAP-121212?style=for-the-badge&logo=greensock&logoColor=88CE02" />
<img src="https://img.shields.io/badge/Lenis-121212?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Framer_Motion-121212?style=for-the-badge&logo=framer&logoColor=0055FF" />

<br/>

</div>

---

## `03` &nbsp;Selected Works

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://blog-saurow.vercel.app">Reel Flux</a> &nbsp;<sub><code>WebGPU</code> <code>TSL</code> <code>R3F</code></sub></h4>
      <p><sub>Open-source 3D wavy film reel slider built with Three.js WebGPU and TSL node materials, paired with a full technical write-up.</sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="#">Orbita</a> &nbsp;<sub><code>Next.js</code> <code>GSAP Flip</code> <code>Lenis</code></sub></h4>
      <p><sub>Editorial product showcase featuring choreographed preloader sequences, ScrollTrigger reveals, and tactile layout transitions.</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="#">STRIDE</a> &nbsp;<sub><code>Next.js</code> <code>TypeScript</code> <code>Lenis</code></sub></h4>
      <p><sub>Editorial footwear platform built around custom smooth-scroll architecture, fluid grids, and sharp typography.</sub></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="#">Raya — Essesi Studio</a> &nbsp;<sub><code>Next.js</code> <code>GSAP</code> <code>SCSS</code></sub></h4>
      <p><sub>Art-directed furniture showcase driven by custom GSAP timelines and seamless section transitions.</sub></p>
    </td>
  </tr>
</table>

> **Lab Notes & Breakdowns:** Deep dives into TSL shaders, WebGPU, and motion engineering at **[blog-saurow.vercel.app](https://blog-saurow.vercel.app)**

<br/>

---

## `04` &nbsp;Current Focus

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>Craft</h4>
      <ul>
        <li><b>TSL & Node Materials</b> — Procedural shaders in Three.js</li>
        <li><b>Motion Architecture</b> — GSAP ScrollTrigger & Flip pipelines</li>
        <li><b>WebGL / WebGPU Scenes</b> — Post-processing & custom meshes</li>
        <li><b>Editorial Frontends</b> — High-frame-rate Next.js builds</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>R&D</h4>
      <ul>
        <li><b>WebGPU Compute</b> — Particle systems & GPGPU workflows</li>
        <li><b>Raymarching & SDFs</b> — Volumetric rendering in TSL</li>
        <li><b>Procedural Math</b> — Simplex/curl noise & vertex deformation</li>
        <li><b>Low-Level Graphics</b> — Rendering pipelines & Blender workflows</li>
      </ul>
    </td>
  </tr>
</table>

<br/>

---

## `05` &nbsp;Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Saur0w&bg_color=09090b&color=71717a&line=e4e4e7&point=ffffff&area=true&area_color=27272a&hide_border=true&custom_title=Contribution%20Pipeline" width="100%" alt="Activity Graph" />

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:09090b,50:18181b,100:27272a&height=90&section=footer&animation=fadeIn" width="100%" />
</div>
