# ChemSim Studio 🧪⚡

An open, browser-native suite for chemical process simulation, equipment sizing, and laboratory safety analysis. **ChemSim Studio** runs entirely client-side with zero dependencies to install, offering instant calculations, interactive dynamic charts, and downloadable engineering summary reports.

---

## 🌟 Modules & Features

### 1. McCabe-Thiele Distillation Column Solver
- **Equilibrium Stepping:** Dynamically solves and renders theoretical equilibrium stages, pinch points, and optimal feed stage location.
- **Operating Lines:** Calculates the Rectifying Operating Line (ROL), Stripping Operating Line (SOL), and $q$-line across varying feed thermal qualities.
- **Critical Parameters:** Real-time calculation of minimum reflux ratio ($R_{\text{min}}$) and minimum theoretical stages ($N_{\text{min}}$).
- **Industrial Presets:** Quick-select benchmarks for binary mixtures (Benzene/Toluene, Acetone/Water, n-Heptane/Octane).

### 2. Shell & Tube Heat Exchanger Designer
- **Thermal Sizing:** Evaluates heat duty ($Q$), Log Mean Temperature Difference ($\text{LMTD}$), Bowman $F$-correction factors, and required surface area ($A$).
- **Flow Configurations:** Toggle between counter-current and co-current modes with automatic temperature-cross warnings.
- **Dynamic Temperature Profiles:** Live SVG rendering showing fluid temperature gradients along the exchanger length.

### 3. GHS Chemical Safety & Reactivity Matrix
- **NFPA 704 Visualization:** Dynamic fire diamond showing Health, Flammability, Instability, and Special hazard codes.
- **Incompatibility Engine:** Matrix-based binary cross-checking to warn against violent acid-base reactions, toxic gas evolution, and runaway oxidizer pairings.
- **Pre-loaded Reagents:** 16 standard chemical engineering reagents included out of the box.

### 4. Engineering Reports
- Clean print- and PDF-ready engineering summary reports generated on demand.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, Modern Vanilla JavaScript (ES6+)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- **Visualization:** [Chart.js](https://www.chartjs.org/) for McCabe-Thiele $x\text{-}y$ diagrams, Custom SVG for heat exchanger profiles
- **Icons:** [Lucide Icons](https://lucide.dev/)

---