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

I am an M.Sc. candidate in **Theoretical Physics at Shanghai University**, jointly trained at the **Shanghai Institute of Applied Physics, Chinese Academy of Sciences (SINAP, CAS)**.

My research lies at the intersection of **reactor physics, numerical methods, and scientific machine learning**. I am particularly interested in developing AI methods that can work together with established numerical solvers, rather than simply replacing them.

My current research focuses on **physics-informed machine learning**, **neural operators**, and **AI-assisted numerical methods for neutron diffusion eigenvalue problems**. Looking forward, I am interested in extending these ideas toward **Monte Carlo neutron transport and high-performance scientific computing**.

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

### 02 · Neural operators as a warm start for conventional solvers

My more recent work shifts from **AI replacing numerical solvers** toward **AI assisting reliable numerical solvers**.

I developed a physics-informed neural-operator approach to predict an improved initial fission-source distribution for multi-group neutron diffusion eigenvalue calculations.

Instead of directly producing the final solution, the neural operator provides a **warm start**, after which the conventional finite-element source-iteration solver continues to convergence under the same numerical stopping criterion.

This design allows the traditional solver to retain control of the final accuracy while the learned model helps reduce unnecessary iterations.

**Keywords:**  
`Neural Operators` · `Warm Start` · `Finite Elements` · `Source Iteration`

---

### 03 · Toward AI-assisted Monte Carlo transport

My long-term research interest is to explore how machine learning can be integrated into **Monte Carlo neutron transport** without compromising the reliability and physical consistency of conventional simulation methods.

Possible directions that I am currently interested in include:

- learned initialization of fission-source distributions;
- data-driven acceleration of source convergence;
- AI-assisted importance functions and variance reduction;
- uncertainty-aware and physics-constrained surrogate models;
- hybrid workflows combining machine learning with high-performance Monte Carlo simulation.

Rather than treating AI as a standalone replacement, I am interested in **hybrid computational frameworks in which AI improves efficiency while trusted physics-based solvers guarantee the final solution quality**.

---
<span class="anchor" id="publications"></span>
## 📚 Selected Research Work

### Physics-Informed Neural Networks with Multi-Band Fourier Feature Enhancement for Two-Group Heterogeneous Neutron Diffusion Eigenvalue Problems

**Yao-Zhong Kang**, et al.

*Nuclear Science and Techniques*

**Status:** Major Revision

This work investigates PINN-based solutions of heterogeneous two-group neutron diffusion eigenvalue problems and introduces multi-band Fourier features to improve the representation of spatially complex neutron-flux distributions.

<!-- Add links when available:
[Manuscript] [Code] [Project]
-->

---

### Physics-informed neural-operator fission-source warm-start method for multi-group neutron diffusion eigenvalue problems

**Yao-Zhong Kang**, Jian Guo, Rui Yan, Yang Zou

*Annals of Nuclear Energy*

**Status:** Under Review

This work develops a physics-informed neural operator for predicting improved initial fission-source distributions. The predicted source is coupled with a conventional finite-element solver to accelerate subsequent source iterations while maintaining the original convergence criterion.

<!-- Add links when available:
[Manuscript] [Code] [Project]
-->

---
<span class="anchor" id="perspective"></span>
## 🧭 My Research Perspective

One important change in my research has been the way I think about the role of AI in scientific computing.

My initial question was:

> *Can a neural network solve the governing equations directly?*

My current question is increasingly:

> *Can machine learning provide useful information to a trusted numerical solver, while the solver remains responsible for final accuracy and reliability?*

This shift motivates my current interest in **hybrid AI–physics computation**, particularly for reactor-physics and neutron-transport applications.

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

**Email:** Add your preferred email here  
**GitHub:** [jr1128](https://github.com/jr1128)

<!--
Future links:
CV | Google Scholar | ORCID | LinkedIn
-->
