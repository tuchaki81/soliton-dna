Aqui está um README.md completo, profissional e bem estruturado para o seu repositório no GitHub. Ele está em inglês (como o post no X que você pediu anteriormente), mas inclui uma seção em português para o público brasileiro, se desejar manter bilíngue.

```markdown
# TGU Interactive Simulator  
**Microtubule Coherence → Topological Soliton Formation**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Here-brightgreen?style=for-the-badge&logo=netlify)](https://dashing-mochi-a07f37.netlify.app/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![Twitter/X](https://img.shields.io/badge/@MatuchakiSilva-Follow-blue?style=flat&logo=twitter)](https://x.com/MatuchakiSilva)

Interactive real-time visualization of the **Unified Informational Spin Theory (TGU)** — showing how quantum coherence in microtubules can lead to the formation of topologically protected solitons, with implications for consciousness persistence and informational immortality.

## What You See

A single microtubule segment with 60 tubulin dimers evolves through five distinct phases:

1. **Incoherent Oscillators** — random phases, Φ ≈ 0  
2. **Kuramoto Synchronization** — coupling increases, phases begin to align  
3. **Supracritical Coherence** — order parameter Φ > Φ_c ≈ 0.6, MT↔DNA loop becomes coherent  
4. **Soliton Formation** — γ > λ, self-sustained pulse emerges (analytic Bernoulli solution)  
5. **Topologically Protected Soliton** — winding number Q ∈ ℤ accumulates, soliton becomes indestructible by continuous deformations

The simulation displays:
- Real-time Kuramoto order parameter Φ(t)  
- Topological charge Q = (1/2π) ∮ ∇θ · dl (accumulated symbolically)  
- Exact soliton profile ℐ(ξ) with equation  
- Live phase indicators and persistence conditions (γ > λ, Ψ₀ > Ψ_c, Q ≠ 0)

## Live Demo

→ https://dashing-mochi-a07f37.netlify.app/

(Hosted on Netlify — no installation required)

## Features

- Pure vanilla JavaScript + HTML5 Canvas (no frameworks)  
- Faithful implementation of Kuramoto model with distance-decaying coupling  
- Analytic soliton profile (logistic approximation of the Bernoulli solution)  
- Phase-scheduled transitions matching the TGU paper timeline  
- Visual feedback for coherence glow, phase arrows, soliton pulse propagation  
- Topological charge winding animation  
- Pause / Restart controls  
- Responsive layout (works on desktop & mobile)

## Theory Background

This simulator illustrates key results from:

**Part II: Impressão Informacional e Persistência Topológica**  
(H. Matuchaki, Teoria Unificada do Spin Informacional — TGU, 2025–2026)

Core predictions visualized:
- Persistence Theorem: under γ > λ, Ψ₀ > Ψ_c and Q ≠ 0, the informational imprint survives indefinitely as a topological soliton  
- Q proportional to number of coherent MT↔DNA cycles  
- High-coherence lives produce stronger, longer-lived solitons

Full paper forthcoming on Zenodo (March 2026 expected release).

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/MatuchakiSilva/tgu-simulator.git
   cd tgu-simulator
   ```

2. Open the file directly in your browser:
   ```bash
   open index.html    # macOS
   # or
   start index.html   # Windows
   # or just drag index.html into your browser
   ```

No build step, no dependencies.

## Folder Structure

```
.
├── index.html          # Main simulation page
├── README.md           # This file
└── (future) assets/    # For screenshots, paper PDF, etc.
```

## Planned Improvements

- Adjustable parameters (coupling strength, noise, Φ_c, γ/λ ratio) via UI sliders  
- Export animation as video/GIF  
- 3D microtubule rendering (Three.js)  
- Numerical integration of full field equation (instead of scheduled phases)  
- Sound feedback for phase transitions and Q accumulation  
- Mobile touch controls

## Related Work

- Orch-OR (Penrose & Hameroff) — microtubule quantum computation  
- Kuramoto model — synchronization phenomena  
- Topological solitons (skyrmions, magnetic monopoles, vortices)  
- Informational conservation in black holes (Susskind, Hawking)

## Citation / Attribution

If you use this simulator in research, teaching or presentations, please cite:

```
Matuchaki, H. (2026). TGU Interactive Simulator: Microtubule Coherence to Topological Soliton. 
GitHub: https://github.com/MatuchakiSilva/tgu-simulator
```

Português / Brazilian Portuguese version available in the [README-pt.md](README-pt.md) file (coming soon).

## Contact

Henry Matuchaki  
[@MatuchakiSilva](https://x.com/MatuchakiSilva) on X  
Open for collaboration: quantum biology, topology in consciousness, numerical field simulations.

Made with curiosity & caffeine — TGU 2026
```

### Versão curta (se preferir algo mais minimalista)

Se quiser uma versão mais enxuta para o GitHub:

```markdown
# TGU Simulator

Real-time visualization of microtubule coherence evolving into a topologically protected soliton — core mechanism of the Unified Informational Spin Theory (TGU).

**Live:** https://dashing-mochi-a07f37.netlify.app/

Phases: Incoherent → Kuramoto sync → Supracritical → Soliton → Topological protection (Q ≠ 0)

Pure JS + Canvas. No dependencies.

See the theory: forthcoming Zenodo paper (Part II — Informational Imprint & Topological Persistence)

Questions / collabs → @MatuchakiSilva on X
```

Escolha a versão que mais combina com o tom do seu repositório. Se quiser ajustes (mais técnico, mais filosófico, adicionar badges extras, screenshots, etc.), é só falar!
