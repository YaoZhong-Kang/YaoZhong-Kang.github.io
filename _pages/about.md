---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='home'></span>

## Hi, I'm Yao-Zhong Kang.

I am an M.Sc. candidate in **Theoretical Physics at Shanghai University**, conducting my research jointly with the **Shanghai Institute of Applied Physics, Chinese Academy of Sciences (SINAP, CAS)**, under the supervision of **Research Professor Yang Zou** and **Research Professor Jian Guo**.

My research focuses on **computational reactor physics** and **scientific machine learning**, particularly on how learned models can be incorporated into established numerical methods for neutron diffusion problems.

I have worked on **physics-informed neural networks** for heterogeneous neutron diffusion eigenvalue problems and, more recently, on **neural operators** for accelerating fission-source iteration through improved initialization. I am also interested in extending these ideas to **Monte Carlo neutron transport and high-performance computing**.

> **Research theme:**  
> Physics-informed learning → AI-assisted trusted solvers → AI-assisted Monte Carlo transport

---
<span class="anchor" id="research"></span>
## 🔬 What I Work On

### 01 · Physics-informed learning for neutron diffusion

My early work explored whether neural networks can directly solve reactor-physics PDEs under physical constraints.

I studied **physics-informed neural networks (PINNs)** for two-group heterogeneous neutron diffusion eigenvalue problems, with particular attention to material discontinuities, interface behavior, and spectral representation.

To improve the representation of heterogeneous flux distributions, I introduced a **multi-band Fourier feature enhancement strategy** and investigated its effects on convergence and solution accuracy.

**Keywords:**  
`PINNs` · `Fourier Features` · `Neutron Diffusion` · `Eigenvalue Problems`

---

### 02 · Neural operators for fission-source initialization

My recent work investigates whether a neural operator can provide a better initial fission-source distribution for multi-group neutron diffusion eigenvalue calculations.

The predicted source is used only as the **initial condition** for a conventional **finite-element** source-iteration solver, which then proceeds to convergence using the original stopping criterion. I use this setup to study how learned initialization affects **source convergence** and the number of subsequent iterations.

**Keywords:**  
`Neural Operators` · `Warm Start` · `Finite Elements` · `Source Iteration`

---

### 03 · Toward Monte Carlo neutron transport

I am interested in extending learned-initialization and source-acceleration ideas from deterministic neutron diffusion to ** Monte Carlo transport** .

In particular, I would like to investigate machine-learning methods for fission-source initialization, source convergence, and variance reduction while keeping the underlying Monte Carlo transport process and statistical convergence criteria explicit.

---
<span class="anchor" id="publications"></span>
## 📚 Selected Research Work

### Physics-Informed Neural Networks with Multi-Band Fourier Feature Enhancement for Two-Group Heterogeneous Neutron Diffusion Eigenvalue Problems

**Yao-Zhong Kang**, Jian Guo, Rui Yan, Yang Zou

*Nuclear Science and Techniques*

**Status:** Major Revision

This work investigates PINN-based solutions of heterogeneous two-group neutron diffusion eigenvalue problems and introduces multi-band Fourier features to improve the representation of spatially complex neutron-flux distributions.

<div class="research-figures research-figures-stacked">

  <figure class="figure-wide">
    <a href="{{ '/images/research/pinn-framework.png' | relative_url }}"
       target="_blank" rel="noopener">
      <img
        src="{{ '/images/research/pinn-framework.png' | relative_url }}"
        alt="PINN framework with multi-band Fourier features"
        loading="lazy">
    </a>
  </figure>

  <figure class="figure-medium">
    <a href="{{ '/images/research/pinn-1.jpg' | relative_url }}"
       target="_blank" rel="noopener">
      <img
        src="{{ '/images/research/pinn-1.jpg' | relative_url }}"
        alt="PINN neutron-flux prediction and error"
        loading="lazy">
    </a>
  </figure>

</div>

<!-- Add links when available:
[Manuscript] [Code] [Project]
-->

---

### Physics-informed neural-operator fission-source warm-start method for multi-group neutron diffusion eigenvalue problems

**Yao-Zhong Kang**, Jian Guo, Rui Yan, Yang Zou

*Annals of Nuclear Energy*

**Status:** Under Review

This work develops a physics-informed neural operator for predicting improved initial fission-source distributions. The predicted source is coupled with a conventional finite-element solver to reduce the number of subsequent source iterations while maintaining the original convergence criterion.

<div class="research-figures research-figures-asymmetric">

  <figure>
    <a href="{{ '/images/research/neural-operator-framework.png' | relative_url }}"
       target="_blank" rel="noopener">
      <img
        src="{{ '/images/research/neural-operator-framework.png' | relative_url }}"
        alt="Physics-informed neural-operator framework"
        loading="lazy">
    </a>
  </figure>

  <figure>
    <a href="{{ '/images/research/neural-operator-1.png' | relative_url }}"
       target="_blank" rel="noopener">
      <img
        src="{{ '/images/research/neural-operator-1.png' | relative_url }}"
        alt="Comparison between neural-operator prediction and FEM refinement"
        loading="lazy">
    </a>
  </figure>

</div>


<!-- Add links when available:
[Manuscript] [Code] [Project]
-->

---
<span class="anchor" id="highlights"></span>
## 📌 Recent Highlights

- **2026** — Abstract *Neural-Operator Warm Start for Neutron Diffusion Eigenvalue Problems* accepted for presentation at the **2026 American Nuclear Society Winter Conference & Expo**.
- **2026** — Submitted the neural-operator fission-source warm-start work to *Annals of Nuclear Energy*.
- **2026** — Received a major-revision decision for the PINN neutron-diffusion work from *Nuclear Science and Techniques*.

---
<span class="anchor" id="conferences"></span>
## 🎤 Conferences & Presentations

### 2026 American Nuclear Society Winter Conference & Expo
**Neural-Operator Warm Start for Neutron Diffusion Eigenvalue Problems**  
Phoenix, Arizona, USA · November 2026  
*Accepted for presentation*

### 21st Conference on Reactor Numerical Calculation and Particle Transport & 2026 Reactor Physics Conference
Wuhan, China · May 2026  
*Oral Presentation*

### 2026 “核理安邦” Joint Academic Forum & 837th Tsinghua University Doctoral Academic Forum
Tsinghua University, Beijing, China · May 2026  
*Oral Presentation & Poster Presentation*

---
<span class="anchor" id="awards"></span>
## 🏅 Honors & Awards

- **2026** · **Grand Prize for Outstanding Oral Presentation**, “Nuclear Science for National Security (核理安邦)” Joint Academic Forum, Tsinghua University
- **2026** · **Second Prize for Outstanding Poster**, “Nuclear Science for National Security (核理安邦)” Joint Academic Forum, Tsinghua University
- **2025** · **First-Class Graduate Academic Scholarship**, Shanghai University *(Top 20%)*
- **2024** · **National Third Prize**, Huawei Cup China Postgraduate Mathematical Contest in Modeling


---
<span class="anchor" id="experience"></span>
## 🎓 Academic Journey

### Shanghai University × SINAP, CAS
**M.Sc. in Theoretical Physics** · 2024 – 2027 (expected)

Jointly trained at the Shanghai Institute of Applied Physics, Chinese Academy of Sciences.

Research focus: **AI-assisted numerical methods for reactor physics**

---

### Soochow University
**B.Sc. in Physics** · 2020 – 2024

---

## 🧑‍🏫 Teaching

**Teaching Assistant — University Physics**  
Shanghai University · March – July 2026

Assisted undergraduate students with problem-solving sessions, homework assessment, and course tutorials.

---

## 🧰 Research Toolkit

**Scientific Computing**  
`Python` · `PyTorch` · `COMSOL` · `OpenMC` · `Finite Element Methods`

**Scientific Machine Learning**  
`Physics-Informed Neural Networks` · `Neural Operators` · `Physics-Constrained Learning`

**Reactor Physics**  
`Neutron Diffusion` · `Multi-group Methods` · `Fission Source Iteration`

**Research Workflow**  
`LaTeX` · `Zotero` · `Matplotlib` · `Origin` · `Draw.io`

**Currently Expanding**  
`Monte Carlo Neutron Transport` · `C++` · `High-Performance Computing`

---
<span class="anchor" id="beyond"></span>
## 🌿 Beyond Research

Outside the lab, I enjoy **badminton, cycling, long-distance running, and Chinese chess**.

- 🏃 **16th / 353** in the 2022 Soochow University Campus Marathon
- ♟️ **Champion**, Chinese Chess, 11th Shanghai University Mind Sports Games
- ♟️ **Runner-up**, Chinese Chess, 4th Suzhou Intercollegiate Chess League

---

## 📫 Contact

I am always happy to discuss research related to scientific machine learning, numerical reactor physics, and AI-assisted scientific computing.

**Email:** kangyaozhong@sinap.ac.cn 
**GitHub:** [YaoZhong-Kang](https://github.com/YaoZhong-Kang)

<!--
Future links:
CV | Google Scholar | ORCID | LinkedIn
-->
