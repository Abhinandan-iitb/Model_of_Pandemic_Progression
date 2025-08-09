# Pandemic Progression Modeling using System Dynamics

##  Overview

This project presents a **system dynamics-based pandemic model** designed to simulate the spread of an infectious disease (e.g., COVID-19) and evaluate various intervention strategies.
It models **population dynamics, healthcare constraints, vaccination campaigns, testing efforts, and mortality** — capturing the complex interplay between public health policies and disease progression.

The model is particularly suited for **resource-limited settings like India** and incorporates:

* Feedback loops
* Delays in testing & reporting
* Hospital capacity limitations
* Virus mutation impacts

---

##  Objectives

1. **Capture endogenous feedbacks** — interactions between infection rates, public awareness, and policy measures.
2. **Model interventions** — social distancing, mask usage, quarantine, testing, and vaccination.
3. **Reflect healthcare capacity constraints** — ICU/hospital load effects on mortality and recovery.
4. **Account for delays** — incubation, testing turnaround, and contact tracing bottlenecks.
5. **Enable scenario analysis** — compare “what-if” outcomes under varying compliance or policy timings.

---

##  Methodology

The model uses **six core stocks**:

* Healthy Non-Vaccinated People
* Healthy Vaccinated People
* Infected
* Identified Infected
* Recovered
* Death

Key flows include:

* Infection & breakthrough infection
* Vaccination
* Recovery
* Mortality
* Testing

**Simulation parameters** such as virus mutation rate, vaccination rate, and healthcare capacity are tunable to test multiple scenarios.

---

## 📊 Key Findings

* **Timely vaccination** reduces infection peaks and stabilizes healthy population counts.
* **Expanded testing** improves early detection, lowering spread rates.
* **Healthcare capacity** significantly impacts mortality outcomes.
* **Virus mutations** (e.g., 0.4 vs. 0.8 mutation rate) greatly affect infection curves and vaccination effectiveness.

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/pandemic-model.git
   cd pandemic-model
   ```
2. Install dependencies (if applicable):

   ```bash
   pip install -r requirements.txt
   ```
3. Run the simulation:

   ```bash
   python src/main.py
   ```

## 📚 References

* Singh, R., Adhikari, R. (2020). *Age-structured impact of social distancing on COVID-19 in India.*
* Venkateswaran, J., Damani, O. (2020). *Effectiveness of Testing, Tracing, Social Distancing and Hygiene in Tackling COVID-19 in India: A System Dynamics Model.*
* [Aarogya Setu App – COVID-19 Tracker](https://secure.mygov.in/task/aarogya-setu-app-covid-19-tracker-launched-alert-you-and-keep-you-safe-download-now)

---

## 👨‍💻 Authors

* **Abhinandan Kumar**
* **Aman Sharma**
* **Vishal Kumar Singh**
* **Guided by Prof. Om P. Damani, IIT Bombay**

