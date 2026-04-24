# 🧪 SemiLattice — Interactive Semiconductor Simulator

An interactive, concept-first semiconductor visualization platform that enables real-time exploration of lattice structures, covalent bonding, doping, and charge-carrier dynamics.

---

## 🚀 Live Demo

🔗 https://semilattice.onrender.com/

---

## 🎯 Problem Statement

Traditional semiconductor teaching relies heavily on static diagrams, making it difficult to intuitively understand:

* Electron-hole pair generation
* Doping effects (P-type / N-type)
* Covalent bonding in lattices
* Charge carrier movement

SemiLattice bridges this gap using **real-time interactive simulation**.

---

## 💡 Key Features

### 🧩 Lattice Construction

* Drag-and-drop atoms (Si, Ge, B, P, etc.)
* Grid-based crystal structure formation

### 🔗 Covalent Bond Visualization

* Automatic bond formation between neighboring atoms
* Visual bond overlap using dynamic SVG rendering

### ⚡ Electron Excitation

* Click to excite valence electrons
* Generates free electrons + holes dynamically

### 🕳️ Hole Dynamics

* Visual hole creation in P-type doping
* Recombination via drag-and-drop electrons

### 🔄 Doping Simulation

* P-type (Boron, Gallium)
* N-type (Phosphorus, Arsenic)
* Real-time behavior changes based on valency

### 🧠 Concept-First Learning

* No equations — pure visualization
* Designed for teaching intuition, not memorization

---

## 🏗️ System Architecture

| Layer            | Description                             |
| ---------------- | --------------------------------------- |
| Rendering        | DOM + SVG (for bonds)                   |
| State Management | In-memory JavaScript state object       |
| Interaction      | Event-driven (drag, click, drop)        |
| Simulation Logic | Rule-based valency + neighbor detection |

---

## ⚙️ Tech Stack

* HTML5
* CSS3 (Custom UI system)
* Vanilla JavaScript (No frameworks)
* SVG for bond rendering

---

## 🧪 How It Works

1. Drag elements into workspace
2. Enable **“Make Bonds”**
3. Observe lattice formation
4. Excite electrons → generate free carriers
5. Drag electrons to recombine with holes

---

## 📦 Installation (Local Setup)

```bash
git clone https://github.com/your-username/semilattice-simulator.git
cd semilattice-simulator
open index.html
```

---

## 🌍 Deployment

This is a static frontend project and can be deployed using:

* GitHub Pages
* Vercel
* Netlify
* Render

---

## 👩‍💻 Author

Built by Nayani
Computer Science Student 

---

## 📄 License

MIT License
