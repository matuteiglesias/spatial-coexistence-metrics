
# 📘 The Overlooked Insights from Correlation Structures in Economic Geography

_A computational exploration and open codebase supporting the findings of [Matias Nehuen Iglesias](http://econ.geo.uu.nl/peeg/peeg2105.pdf), Utrecht University._

**Keywords**: spatial economics, co-location, cosine similarity, MAUP, economic geography, industry clustering, employment density, continuous space modeling, spatial analysis, kernel density, economic complexity, GIS.

---

## 🧠 What This Project Is

This repository contains the source code, computational experiments, and data structures supporting the research paper:

> 📄 **“The Overlooked Insights from Correlation Structures in Economic Geography”**  
> _Papers in Evolutionary Economic Geography, Working Paper #21.05_  
> [Download PDF](http://econ.geo.uu.nl/peeg/peeg2105.pdf)

This project studies the mathematical and empirical conditions under which **continuous spatial models** (e.g., radial influence around establishments) and **discrete areal data models** (e.g., county-level employment statistics) yield comparable measures of industrial co-location.

---

## 🔍 Motivation

Traditional spatial analyses rely on administrative units that may distort the real patterns of economic co-location due to the [Modifiable Areal Unit Problem (MAUP)](https://en.wikipedia.org/wiki/Modifiable_areal_unit_problem). This repository:

- Formalizes **coexistence measures** in continuous space.
- Compares them with **cosine similarity metrics** computed on discrete areal data.
- Offers code to replicate **analytical derivations** and **computational simulations**.
- Helps identify when discrete spatial indicators are reliable proxies for true spatial proximity.

---

## 🧪 Contents

```

/notebooks/           # Exploratory and replication notebooks
/models/              # Density function models and simulation engines
/data/                # Sample geospatial datasets (synthetic and real)
/experiments/         # Setup for controlled spatial displacement simulations
/utils/               # Math helpers, kernel generators, area integrators

```

---

## 🧰 Methods Implemented

- Kernel density estimation (Gaussian & Laplace)
- Cosine similarity over employment vectors
- Numerical integration of joint density functions
- Systematic decomposition of co-location pairs (A/B/C/D types)
- Simulation of influence decay and spatial shifting
- Comparative experiments across area sizes (e.g., 10km², 100km²)

---

## 💬 Citation

If you use this codebase or ideas in your work, please cite:

```

@techreport{iglesias2021correlation,
title={The Overlooked Insights from Correlation Structures in Economic Geography},
author={Matias Nehuen Iglesias},
year={2021},
institution={Utrecht University},
series={Papers in Evolutionary Economic Geography},
number={21.05}
}

```

---

## 🌐 Discover More

- 📄 [Official paper link (PDF)](http://econ.geo.uu.nl/peeg/peeg2105.pdf)
- 📚 [EconGeo Working Papers Series](https://ideas.repec.org/p/egu/wpaper/2105.html)
- 🌍 [Research Gate: Matias Nehuen Iglesias](https://www.researchgate.net/profile/Matias-Iglesias-9)

---

## 👨‍🔬 Author

**Matias Nehuen Iglesias**  
PhD in Economics – SSSUP Univ di Pisa  
Researcher in economic geography, spatial modeling, and applied AI.  


