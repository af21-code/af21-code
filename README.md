<div align="center">

# Angelo Fusco

**B.Sc. Computer Science Student @ University of Salerno (UNISA)**  
*Software Engineering · Vehicle Dynamics Simulation · Applied Machine Learning*

<p>
  <a href="mailto:fusco.angelo@proton.me"><img src="https://img.shields.io/badge/Email-fusco.angelo%40proton.me-6D4AFF?style=flat-square&logo=protonmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/TUO-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-Angelo_Fusco-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Italy_(Open_to_Relocation)-2ea44f?style=flat-square" />
</p>

</div>

---

Final-year Computer Science undergraduate specializing in **Software Architecture**, **Distributed Systems**, and **Applied Machine Learning**, with a strong focus on **Motorsport Engineering**, **Vehicle Dynamics Simulation**, and **Formula 1 Telemetry Analysis**.

---

## 🏁 Motorsport, Telemetry & Simulation Projects

### [ADDS — Adaptive Drivetrain Decoupling System](https://github.com/af21-code/ADDS) ![ADDS CI Tests](https://github.com/af21-code/ADDS/actions/workflows/tests.yml/badge.svg)
**Longitudinal Vehicle Dynamics Simulator & Finite State Machine Control Architecture**

Physics-based simulation framework comparing a conventional baseline drivetrain against an adaptive decoupling system (ADDS) under identical driving profiles.
* **Deterministic Physics Engine:** Models ICE torque maps, transmission ratios, clutch slip dynamics, aerodynamic drag, rolling resistance, and road grade.
* **Explicit 6-State FSM:** Governs transitions across `CONNECTED`, `DECOUPLING`, `DECOUPLED`, `REV_MATCHING`, `REENGAGING`, and a deterministic `FAULT_SAFE` fallback state.
* **Validation & ML Pipeline:** Built following a *"Physics before optimization, Baselines before AI"* methodology across 7 stages, combining rule-based baselines, **Behavioral Cloning**, automated **Pytest** suites, robustness sweeps, and a **Streamlit** analysis dashboard.

`Python` · `NumPy` · `Scikit-Learn` · `Pytest` · `Streamlit`

---

### [F1 Overtake Prediction](https://github.com/af21-code/f1-overtake-prediction)
**Machine Learning Pipeline on Real Formula 1 Telemetry & Strategy Data**

End-to-end predictive modeling pipeline designed to estimate overtaking probability in Formula 1 using historical race and telemetry data.
* **Feature Engineering:** Extracts domain-specific indicators including pace deltas, track position, tire compound degradation curves, and pit-stop strategy windows.
* **Model Benchmarking:** Implements data cleaning, feature scaling, cross-validation, and comparative evaluation of classification algorithms.

`Python` · `Scikit-Learn` · `Pandas` · `NumPy` · `Matplotlib`

---

### [Red Bull Spielberg Experience](https://github.com/af21-code/redbull-spielberg-experience)
**MVC Web Platform for Track Driving Sessions**

Full-stack web application built on the **Model-View-Controller (MVC)** architecture in Java for managing track driving experiences, telemetry package customization, and booking workflows at the Red Bull Ring.

`Java` · `JavaScript` · `HTML5` · `CSS3` · `MVC Architecture`

---

## 🏗️ Software Engineering & Data Science Projects

### [SINTONIA — Full-Stack Microservices Platform](https://github.com/gianfrancobarba/SINTONIA)
**Decoupled Web Architecture developed with Agile (Scrum) Methodologies**
* **Architecture:** **React + TypeScript** frontend communicating with a **NestJS** RESTful backend and **PostgreSQL** database.
* **Engineering Practices:** JWT authentication, role-based access control, full UML specification (requirements, class, sequence, and deployment diagrams), and iterative Scrum sprints.

`TypeScript` · `React` · `NestJS` · `PostgreSQL` · `Docker`

---

### [Biological Data Regression](https://github.com/af21-code/biological-data-regression)
**Regularized Regression & Statistical Modeling**
* Comparative evaluation of Linear, Polynomial, Ridge ($L_2$), and Lasso ($L_1$) regression models on continuous biological datasets with residual diagnostics and cross-validation.

`Python` · `Scikit-Learn` · `Pandas` · `Jupyter`

---

### [The Knowledge Haven](https://github.com/af21-code/The-Knowledge-Haven)
**Relational Database Design & SQL Implementation**
* Complete database lifecycle from E-R conceptual modeling and logical normalization to MySQL implementation for a hybrid library and live-streaming platform.

`SQL` · `MySQL` · `Database Modeling`

---

## 🛠️ Technical Stack

| Area | Technologies |
| :--- | :--- |
| **Core Languages** | Python, C, C++, Java, TypeScript, JavaScript, SQL |
| **Software Engineering & Web** | React, NestJS, Node.js, HTML5/CSS3, REST APIs, Microservices |
| **Simulation & Data Science** | NumPy, Pandas, Scikit-Learn, Streamlit, Matplotlib, Jupyter |
| **Databases, Testing & DevOps** | PostgreSQL, MySQL, Pytest, Docker, Git, Linux |
