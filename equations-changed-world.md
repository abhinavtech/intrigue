Below is a concise “guided tour” of Ian Stewart’s famous list. For each equation I give (i) the mathematical statement, (ii) what it *means* in plain language, and (iii) a quick note on how it reshaped science, technology, and everyday life.

---

| # | Equation | What it captures | Why it mattered |
|---|-----------|------------------|-----------------|
| **1. Pythagoras’ Theorem**  <br/>$$a^{2}+b^{2}=c^{2}$$ | Geometry of right-angled triangles | Corner-stone of surveying, architecture, computer graphics and distance calculations in every Cartesian coordinate system. |
| **2. Logarithms**  <br/>$$\log xy=\log x+\log y$$ | Converts multiplication into addition | Turned laborious arithmetic into slide-rule speed; enabled early astronomy tables, radio-signal calculations, and still underlies floating-point scaling and algorithmic complexity (the ubiquitous “log n”). |
| **3. Calculus (Derivative Definition)**  <br/>$$\displaystyle \frac{df}{dt}=\lim_{h\to0}\frac{f(t+h)-f(t)}{h}$$ | Instantaneous rate of change | Foundation of modern science and engineering: from orbital mechanics and control systems to gradient-descent optimizers in machine learning. |
| **4. Newton’s Law of Gravity**  <br/>$$F=G\frac{m_1m_2}{r^{2}}$$ | Attractive force between masses | Put the motion of planets and falling apples under a single law; the prototype of universal physical principles. |
| **5. The Square Root of −1**  <br/>$$i^{2}=-1$$ | Introduction of *imaginary* numbers | Unlocked complex analysis, AC circuit theory, quantum mechanics, signal processing (FFT uses $$e^{i\theta}$$). |
| **6. Euler’s Formula for Polyhedra**  <br/>$$V-E+F=2$$ | Topological invariant of convex polyhedra | First glimpse that shape has properties independent of geometric size; led to topology, crucial for computer graphics meshes and 3-D printing validation. |
| **7. Normal Distribution**  <br/>$$\displaystyle \Phi(x)=\frac{1}{\sqrt{2\pi}\,\sigma} e^{-(x-\mu)^{2}/2\sigma^{2}}$$ | “Bell curve” of random variation | Statistics, quality control, error bars, A/B testing, Kalman filters; anywhere “errors average out” you meet Gauss. |
| **8. Wave Equation**  <br/>$$\displaystyle \frac{\partial^{2}u}{\partial t^{2}}=c^{2}\frac{\partial^{2}u}{\partial x^{2}}$$ | Propagation of waves in a medium | Governs sound, light, vibration, fibre-optics, 5G antennas, even the strings in a game-engine’s audio synthesis. |
| **9. Fourier Transform**  <br/>$$f(\omega)=\int_{-\infty}^{\infty} f(x)e^{-2\pi i\omega x}\,dx$$ | Decomposes signals into frequencies | MP3, JPEG, MRI scanners, spectral analysis for fintech and seismology all rely on “frequency-domain thinking.” |
| **10. Navier–Stokes**  <br/>$$\rho\left(\frac{\partial \mathbf{v}}{\partial t}+\mathbf{v}\!\cdot\!\nabla\mathbf{v}\right)=-\nabla p+\mu\nabla^{2}\mathbf{v}+\mathbf{f}$$ | Motion of viscous fluids | Weather forecasting, airplane design, blood-flow simulation; still holds a Clay Millennium Prize for proof of smoothness. |
| **11. Maxwell’s Equations**  <br/>$$\nabla\!\cdot\!\mathbf{E}=\rho/\varepsilon_{0},\;\nabla\!\times\!\mathbf{E}=-\partial\mathbf{B}/\partial t,\;\dots$$ | Unifies electricity, magnetism & light | Birth of radio, wireless, optics, and ultimately today’s entire information infrastructure. |
| **12. Second Law of Thermodynamics**  <br/>$$dS\ge0$$ | Entropy never decreases in an isolated system | Explains irreversible processes, heat engines, why batteries run down, and sets limits for computation (Landauer’s principle). |
| **13. Relativity (Mass–Energy)**  <br/>$$E=mc^{2}$$ | Mass is frozen energy | Nuclear power and medicine, GPS time-dilation corrections, insights into stellar evolution. |
| **14. Schrödinger Equation**  <br/>$$i\hbar\frac{\partial\Psi}{\partial t}=H\Psi$$ | Wave-function dynamics of quantum systems | Quantum chemistry (LEDs, fertilizers), transistors, lasers, and the beginnings of quantum computing. |
| **15. Information Theory (Shannon Entropy)**  <br/>$$H=-\sum p(x)\log p(x)$$ | Quantifies uncertainty/information content | Sets channel capacity, compression limits, cryptography bases, and inspires modern machine-learning loss functions. |
| **16. Chaos Theory (Logistic Map)**  <br/>$$x_{t+1}=k x_t(1-x_t)$$ | Simple rule → unpredictable long-term behavior | From weather and ecological models to hash functions and random-number generators, it showed that determinism need not imply predictability. |
| **17. Black–Scholes Equation**  <br/>$$\tfrac12\sigma^{2}S^{2}\tfrac{\partial^{2}V}{\partial S^{2}}+rS\tfrac{\partial V}{\partial S}+\tfrac{\partial V}{\partial t}-rV=0$$ | Price evolution of financial derivatives | Standard tool of modern finance; connects probability, PDEs, and markets, enabling hedging and risk-neutral valuation. |

---

### Three cross-cutting take-aways

1. **Universality:** Many equations (Newton’s gravity, Maxwell, Schrödinger) describe disparate phenomena with a *single* mathematical language, revealing hidden unity in nature.  
2. **Abstraction pays off:** Imaginary numbers, entropy, and information looked esoteric at birth; today they underpin circuits, cryptography and data science.  
3. **From chalkboard to chipset:** Virtually every item has migrated from theory to technology—from Gauss curves in A/B tests to Fourier transforms running in your phone’s DSP—often centuries after its discovery.

Feel free to dive deeper into any of them (derivations, historical anecdotes, code snippets, or modern applications); just let me know which ones interest you most!