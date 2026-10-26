<div align="center">

# 👋 Hi, I'm Angelo Fusco!

### 🏎️ Software Engineering & Simulation Student · 🎯 Full-Stack, Vehicle Dynamics & Applied ML

<p>
  <a href="mailto:fusco.angelo@proton.me"><img src="https://img.shields.io/badge/Email-fusco.angelo%40proton.me-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white" /></a>
  <a href="https://github.com/af21-code"><img src="https://img.shields.io/badge/GitHub-af21--code-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&random=false&width=650&lines=Motorsport+%26+Telemetry+Software+Engineering;Vehicle+Dynamics+Simulation+%26+Applied+ML;Full-Stack+%26+Distributed+Systems+Developer;Physics+before+optimization%2C+Baselines+before+AI+%F0%9F%8F%81" alt="Typing SVG" />

</div>

---

<br/>

> 💡 3rd-year **Computer Science Student (B.Sc.)** at the **University of Salerno (UNISA)** and Full-Stack / Simulation Software Developer. Focused on **Software Engineering**, **Distributed Systems**, **Vehicle Dynamics Simulation**, and **Machine Learning**, bridging rigorous engineering baselines with high-performance software architectures for **Motorsport & Formula 1**.

<br/>

## 🏆 Featured Projects

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!-- 🏁  MOTORSPORT, TELEMETRY & SIMULATION                  -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">
  <img src="https://img.shields.io/badge/🏁_MOTORSPORT,_TELEMETRY_&_SIMULATION-E10600?style=for-the-badge" />
</div>

<br/>

### ⚙️ ADDS — *Adaptive Drivetrain Decoupling System*

> **Physics-based longitudinal vehicle dynamics simulator and AI-assisted control architecture for adaptive drivetrain decoupling.**

ADDS simulates and benchmarks longitudinal vehicle dynamics under identical driving profiles, comparing a conventional baseline vehicle against an ADDS-equipped vehicle capable of adaptively decoupling, speed-matching, and re-engaging the engine and transmission.

The system implements a **complete deterministic physics engine** (ICE torque curves, transmission ratios, clutch slip dynamics, aerodynamic drag, rolling resistance, road grade) governed by an **explicit 6-state Finite State Machine (FSM)**:

| State | Operational Description |
| :--- | :--- |
| `CONNECTED` | Drive torque and engine braking transmitted directly through the drivetrain |
| `DECOUPLING` | Controlled clutch disengagement ramp to minimize torque transients |
| `DECOUPLED` | Free-rolling coasting phase while engine dynamics evolve independently |
| `REV_MATCHING` | Active engine speed synchronization to target transmission input shaft RPM |
| `REENGAGING` | Closed-loop clutch re-engagement with bounded slip and jerk constraints |
| `FAULT_SAFE` | Conservative deterministic fallback state for unsafe or out-of-bounds conditions |

**Engineering Methodology:** *Physics before optimization, Baselines before AI, Constraints before rewards.* Built across 7 structured development stages: deterministic rule-based controllers first, followed by Machine Learning pipelines (**Behavioral Cloning**), automated unit/integration testing (**Pytest**), robustness parameter sweeps, and an interactive **Streamlit** telemetry & comparison dashboard.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
</p>

[![Repo](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/af21-code/ADDS)

---

### 🏎️ F1 Overtake Prediction — *Machine Learning & Race Telemetry*

> **End-to-end Machine Learning pipeline to predict on-track overtaking maneuvers in Formula 1 using real telemetry and race strategy data.**

Advanced analysis of Formula 1 telemetry datasets featuring a full ML workflow: data ingestion, noise filtering, domain-specific feature engineering (pace deltas, track position, tire compound/age degradation, and pit strategy), predictive model training, and performance evaluation.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white" />
</p>

[![Repo](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/af21-code/f1-overtake-prediction)

---

### 🚀 Red Bull Spielberg Experience — *MVC Web Platform*

> **Full-stack web application for booking track driving experiences at the Red Bull Ring in Spielberg.**

Complete web platform built with the **MVC architectural pattern** in Java. Features driving session scheduling, customizable telemetry & track packages, secure payment workflows, and user profile management with a high-engagement UI.

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
</p>

[![Repo](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/af21-code/redbull-spielberg-experience)

---

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!-- 🔬  SOFTWARE ENGINEERING, DISTRIBUTED SYSTEMS & DATA    -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">
  <img src="https://img.shields.io/badge/🔬_SOFTWARE_ENGINEERING_&_DATA_SCIENCE-6C63FF?style=for-the-badge" />
</div>

<br/>

### 🧠 SINTONIA — *Microservices Full-Stack Platform*

> **End-to-end digital healthcare platform engineered using Agile (Scrum) methodologies and a decoupled full-stack architecture.**

Built with a **React + TypeScript** frontend and a **NestJS** RESTful backend backed by **PostgreSQL**. Implements JWT-based authentication, role-based access control, session scheduling, and complete **UML** architectural documentation (requirements, class, sequence, and deployment diagrams).

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
</p>

[![Repo](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gianfrancobarba/SINTONIA)

---

### 🧬 Biological Data Regression — *Data Science & Predictive Modeling*

> **Comparative regression modeling and regularization analysis on complex continuous biological datasets.**

Implementation and benchmarking of multiple regression pipelines (Linear, Polynomial, Ridge $L_2$, and Lasso $L_1$ regularization) with cross-validation, feature scaling, residual diagnostics, and statistical visualization.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
</p>

[![Repo](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/af21-code/biological-data-regression)

---

### 📚 The Knowledge Haven — *Relational Database Architecture*

> **Relational database design and SQL implementation for an integrated scientific library and live-streaming event platform.**

Full database lifecycle engineering: requirements analysis, Entity-Relationship (E-R) conceptual modeling, relational logical schema normalization, and SQL implementation with triggers, views, and optimized queries.

<p>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=amazon-dynamodb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
</p>

[![Repo](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/af21-code/The-Knowledge-Haven)

---

<br/>

## 🔭 Current Focus

<table>
  <tr>
    <td>🏎️ <strong>Motorsport R&D</strong></td>
    <td>Real-Time F1 Telemetry Pipelines, Vehicle Dynamics Simulation & Race Strategy Tooling</td>
  </tr>
  <tr>
    <td>🏗️ <strong>Software Engineering</strong></td>
    <td>Microservices, Distributed Systems & High-Reliability Software Architectures</td>
  </tr>
  <tr>
    <td>🤖 <strong>Applied AI & ML</strong></td>
    <td>Physics-Informed ML, Behavioral Cloning & Predictive Telemetry Analytics</td>
  </tr>
</table>

<br/>

## 🛠️ Tech Stack

<div align="center">

**Core Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
</p>

**Full-Stack & Web Engineering**
<p>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

**Simulation, Data Science & ML**
<p>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
</p>

**Databases & DevOps**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

</div>

---

<div align="center">

## 📊 GitHub Stats

<p>
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=af21-code&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=af21-code&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=af21-code&theme=tokyonight&hide_border=true" />

---

<img src="https://komarev.com/ghpvc/?username=af21-code&color=6C63FF&style=for-the-badge&label=PROFILE+VIEWS" />

<br/><br/>

*"af21-ccode"*

</div>
