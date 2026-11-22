<div align="center">

# Angelo Fusco

**B.Sc. Computer Science Student @ University of Salerno (UNISA)**  
*Vehicle Dynamics Simulation · F1 Telemetry · Software Engineering*

<p>
  <a href="mailto:fusco.angelo@proton.me"><img src="https://img.shields.io/badge/Email-fusco.angelo%40proton.me-6D4AFF?style=flat-square&logo=protonmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/angelo-fusco-19baab287/"><img src="https://img.shields.io/badge/LinkedIn-Angelo_Fusco-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Italy_(Open_to_Relocation)-2ea44f?style=flat-square" />
</p>

</div>

---

Final-year Computer Science undergraduate building software for **vehicle dynamics simulation**, **motorsport telemetry** and **data-driven performance analysis**, in Python, C# and Java.

---

## 🏁 Motorsport, Telemetry & Simulation Projects

### [DynaLoad Telemetry](https://github.com/af21-code/DynaLoad-Telemetry) ![CI](https://github.com/af21-code/DynaLoad-Telemetry/actions/workflows/tests.yml/badge.svg)
**100 Hz Suspension Telemetry Pipeline & Damper Fault Detection**

* **C# / .NET 8 streamer** broadcasting 7-channel damper, pushrod-load and gas-reservoir telemetry over UDP at 100 Hz, with F1 lap profiles for nominal, overload and fault scenarios.
* **Python engine** for damper velocity, bump/rebound regime classification, structural load checks and a physics-informed Isolation Forest.
* **Validated sensitivity:** no false alarms on healthy laps; gas pre-charge loss detected from about 15%. Synthetic data, limits documented in the README.

`C#` · `.NET 8` · `Python` · `Scikit-Learn` · `Pytest` · `GitHub Actions` · `Streamlit`

---

### [ADDS — Adaptive Drivetrain Decoupling System](https://github.com/af21-code/ADDS) ![ADDS CI Tests](https://github.com/af21-code/ADDS/actions/workflows/tests.yml/badge.svg)
**Longitudinal Vehicle Dynamics Simulator & Drivetrain State Machine**

Physics-based simulator comparing a conventional drivetrain with an adaptive decoupling system under identical driving profiles.
* **Physics:** engine torque, gear ratios, clutch slip, aerodynamic drag, rolling resistance, road grade and tyre-force limits.
* **Control:** 6-state FSM (`CONNECTED`, `DECOUPLING`, `DECOUPLED`, `REV_MATCHING`, `REENGAGING`, `FAULT_SAFE`) with rule-based, offline-optimised and behavioural-cloning controllers.
* **Evaluation:** robustness sweeps on mass, drag, grip and grade; track-lap and endurance-strategy analysis; 77 automated tests in CI; Streamlit dashboard.

`Python` · `Pytest` · `Streamlit` · `Plotly` · `Pandas`

---

### [F1 Overtake Prediction](https://github.com/af21-code/f1-overtake-prediction)
**Machine Learning on Official F1 Timing Data (team of 2)**

* Pairwise attacker/defender features from FastF1 lap data (Monza 2022–2024): pace delta, tyre age, compound advantage, position.
* Logistic Regression, Random Forest and XGBoost evaluated **leave-one-season-out** against a trivial baseline: PR-AUC 0.45 vs 0.17.
* Label audit showed 124 of 403 "overtakes" were pit-stop effects; added a cleaner on-track-pass target (ROC-AUC 0.81–0.83).
* Streamlit "pit wall" app to simulate attack and defence scenarios.

`Python` · `FastF1` · `Pandas` · `Scikit-Learn` · `XGBoost` · `Streamlit`

---

### [Red Bull Spielberg Experience](https://github.com/af21-code/redbull-spielberg-experience)
**Java Web Platform for Track-Day Bookings (team of 2, unofficial university project)**

E-commerce and booking platform for driving experiences at the Red Bull Ring: time-slot availability, packages, orders and an admin panel.
* **Architecture:** MVC with DAO layer on Jakarta Servlets/JSP, MySQL and Tomcat.
* **Security:** PBKDF2 password hashing, CSRF tokens and session management.

`Java` · `Jakarta EE` · `MySQL` · `JavaScript` · `HTML5/CSS3`

---

## 🏗️ Software Engineering & Data Science Projects

### [SINTONIA — Full-Stack Microservices Platform](https://github.com/gianfrancobarba/SINTONIA)
**Decoupled Web Architecture developed with Agile (Scrum) Methodologies**
* **Architecture:** **React + TypeScript** frontend communicating with a **NestJS** RESTful backend and **PostgreSQL** database.
* **Engineering Practices:** JWT authentication, role-based access control, full UML specification (requirements, class, sequence, and deployment diagrams), and iterative Scrum sprints.

`TypeScript` · `React` · `NestJS` · `PostgreSQL` · `Docker`

---

### [Biological Data Regression](https://github.com/af21-code/biological-data-regression) ![Tests](https://github.com/af21-code/biological-data-regression/actions/workflows/tests.yml/badge.svg)
**Regression from First Principles on Real Gene-Expression Data**
* Simple and multiple linear regression implemented from scratch with NumPy (normal equations, optional Ridge), on NCBI GEO dataset GSE38417 (Duchenne muscular dystrophy).
* Descriptive statistics, train/test validation, interpolation vs extrapolation and interactive outlier analysis; 30 unit tests.

`Python` · `NumPy` · `Pandas` · `Matplotlib` · `SciPy`

---

### [The Knowledge Haven](https://github.com/af21-code/The-Knowledge-Haven)
**Relational Database Design (team of 3)**
* Conceptual EER model, redundancy analysis, 3NF relational schema and MySQL implementation (DDL, sample data, queries) for a scientific library with event streaming, documented in the project report.

`SQL` · `MySQL` · `Database Modeling`

---

## 🛠️ Technical Stack

| Area | Technologies |
| :--- | :--- |
| **Languages** | Python, C#, Java, TypeScript, JavaScript, SQL, C/C++ |
| **Simulation & Data** | NumPy, Pandas, Scikit-Learn, XGBoost, FastF1, Matplotlib, Plotly, Streamlit |
| **Backend & Web** | .NET 8, NestJS, Node.js, React, Jakarta EE, REST APIs |
| **Databases, Testing & DevOps** | PostgreSQL, MySQL, Pytest, GitHub Actions, Docker, Git, Linux |
