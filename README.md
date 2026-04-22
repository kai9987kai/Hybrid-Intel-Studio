🌌 PROJECT 1X4G v6: Advanced Hybrid Intelligence Studio
A deterministic, multi-substrate simulation blending Quantum Density Evolution, Neuromorphic Active Inference, Hodgkin-Huxley Biology, and Astrocyte Glial Dynamics in a single, high-performance visual environment.
![alt text](https://img.shields.io/badge/version-v6.0.0-38bdf8?style=for-the-badge)

![alt text](https://img.shields.io/badge/tech-Vanilla_JS_|_HTML5_Canvas-4ade80?style=for-the-badge)

![alt text](https://img.shields.io/badge/license-MIT-c084fc?style=for-the-badge)
PROJECT 1X4G is an interactive, browser-based research sandbox. It simulates a synthetic neural topology where different computational substrates (Quantum, Biological, and Neuromorphic) interact, self-organize, and attempt to achieve homeostasis.
Version 6 introduces cutting-edge theoretical neuroscience concepts, wrapping them in a highly optimized "cyber-glassmorphism" UI.
🔬 Scientific Underpinnings
This engine simulates four distinct but interacting physical/theoretical layers:
Active Inference & Variational Free Energy (FEP)
Nodes utilize local precision-weighted predictive coding (based on Karl Friston's Free Energy Principle). Instead of traditional backpropagation, nodes continuously adjust their weights and spatial positions to minimize "surprisal" (prediction errors) from their neighbors.
Tripartite Synapses & Astrocyte Glial Waves
A background glial network tracks the global spike rate, accumulating intracellular Calcium (Ca²⁺). Upon crossing a critical threshold, astrocytes release a global wave of gliotransmitters, temporarily hyperpolarizing biological nodes and preventing chaotic runaway.
Quantum Zeno Effect & Density Matrix Evolution
Quantum nodes evolve according to a simplified Hamiltonian drive and thermal decoherence. Frequent measurements (neuromorphic spikes intersecting with quantum nodes) actively freeze or collapse the quantum state evolution, demonstrating observation-induced state locking (The Quantum Zeno Effect).
Hodgkin-Huxley Biological Substrate
Biological nodes are governed by continuous non-linear differential equations representing Sodium (
m
m
, 
h
h
) and Potassium (
n
n
) ion channel gating variables, complete with realistic membrane potentials (
V
m
e
m
V 
mem
​
 
) and refractory periods.
🚀 Features
Zero-Dependency Architecture: Entirely built in Vanilla JavaScript, HTML5, and CSS3. No Webpack, no NPM, no server required.
Real-time Telemetry: Live readout of Variational Free Energy (VFE), Zeno measurement rates, Astrocyte Calcium thresholds, and a cryptographic deterministic hash digest of the system state.
Multi-Objective Graph Layout: Nodes physically drift and organize based on a gradient descent of their Free Energy, visually mapping the "surprisal" landscape in real-time.
Screen-Space Compositing: Hardware-accelerated canvas rendering with screen blend modes, dynamic glow mapping, and responsive scaling.
🛠️ Installation & Usage
Because the project is entirely self-contained, installation is instantaneous:
Clone or Download this repository (or copy the HTML code).
Save the file as index.html.
Double-click index.html to open it in any modern web browser (Chrome, Edge, Safari, Firefox).
Note: For the best visual experience, run on a display with accurate sRGB/P3 color profiles, as the engine makes heavy use of deep space gradients and subtle neon compositing.
🎛️ UI & Controls Guide
Telemetry Readouts
Quantum Density ρ₁₁ / Purity: Tracks the probability amplitude of the quantum substrate being in the excited state, alongside the density matrix purity (decoherence tracker).
Free Energy (VFE): The current precision-weighted prediction error of the network. Lower is better (homeostasis).
Astrocyte Ca²⁺: When this hits 100%, a pink glial suppression wave will wash over the visualizer, resetting hyperactive nodes.
Hash Digest: A deterministic, cryptographic footprint of the current frame, ensuring replayability.
Orchestration Panel
Presets:
Default: Balanced FEP and standard homeostasis.
Criticality: High noise, low sparsity. Pushes the network to the "edge of chaos."
Astrocyte Dominant: Forces frequent, slow glial waves.
Zeno Lock: High quantum coupling forces the network to frequently measure and freeze quantum states.
Active Inference Rate: Adjusts how aggressively nodes update their weights to minimize surprise.
Thermal Noise (T): Introduces Brownian motion and spontaneous stochastic firing.
🧬 Architecture Overview
The simulation runs on a decoupled loop architecture:
rebuild(): Generates the tripartite topology (Neuro, Bio, Quant) and initializes matrices.
step(dt): The deterministic physics and physics loop. Integrates Hodgkin-Huxley equations, computes FEP gradients, and manages Astrocyte timers.
draw(): The decoupled rendering pass. Translates internal variables into glow intensities, edge weights into opacities, and FEP error into particle radii.
updateDOM(): Throttled UI updater (runs every 3rd frame) to prevent DOM-thrashing while maintaining 60+ FPS on the canvas.
📝 License
This project is open-source and released under the MIT License. Feel free to fork, modify, and integrate these simulations into your own theoretical neuroscience or generative art projects.
