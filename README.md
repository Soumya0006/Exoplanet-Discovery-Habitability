# 🪐 Exoplanet Discovery & Habitability Dashboard

An interactive Tableau dashboard exploring 51 confirmed exoplanets — their discovery methods, physical characteristics, host stars, and habitability potential.

![Dashboard Preview](Images/dashboard-main-view.png)

---

## 📌 Overview

This project analyzes a curated dataset of confirmed exoplanets to uncover patterns in how — and where — we're finding worlds beyond our solar system. The dashboard covers planet type distribution, mass vs. radius relationships, discovery methods and trends, habitability analysis, star temperature distribution, and distance from Earth by planet type.

**Key highlights:**
- 🌍 **51** confirmed exoplanets analyzed (discoveries from 1995–2023)
- 🟢 **24** planets (47%) fall within their host star's habitable zone
- 🔭 **Transit** is the leading discovery method (54.9%), followed by Radial Velocity (33.3%)
- 🪨 **Super-Earths** are the most common planet type (39.2%)
- 🛰️ **Kepler** is the top contributing NASA mission, with **JWST** increasingly prominent in recent years

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `Exoplanet_Discovery_Habitability_Dashboard.twbx` | Packaged Tableau workbook — full dashboard, worksheets, and embedded data source |
| `images/dashboard-main-view.png` | Screenshot of the main analytics dashboard (KPIs + 7 charts + filters) |
| `images/dashboard-insights-panel.png` | Screenshot of the key insights & observations panel |
| `Exoplanet_Discovery_Habitability_Report.docx` | Full written report with data-backed analysis and takeaways |
| `README.md` | Project documentation (this file) |

---

## 📊 Dashboard Views

### Main Analytics View
KPI summary cards, planet type distribution, mass vs. radius scatter, discovery method breakdown, discovery trend over time, habitability analysis, star temperature distribution, and distance-from-Earth by planet type — with filters for discovery year, planet type, discovery method, habitability zone, atmosphere, NASA mission, and constellation.

![Main Dashboard](Images/dashboard-main-view.png)

### Key Insights Panel
A narrative summary of the standout findings across discovery trends, habitability, star & planet characteristics, observation methods, distance & location, and missions & future scope.

![Insights Panel](Images/dashboard-insights-panel.png)

---

## 🗂️ Dataset

The dashboard is built on a 51-row, 35-column dataset of confirmed exoplanets, including:

| Category | Fields |
|---|---|
| **Identification** | Planet Name, Host Star, Constellation, Right Ascension, Declination |
| **Discovery** | Discovery Year, Discovery Method, NASA Mission, Confirmed |
| **Orbit** | Orbital Period, Semi-Major Axis, Eccentricity, Hill Sphere |
| **Planet Physics** | Mass (Jupiter/Earth units), Radius (Jupiter/Earth units), Density, Surface Gravity, Escape Velocity, Planet Type |
| **Star Properties** | Star Type, Star Mass, Star Radius, Star Temperature, Star Age, Stellar Luminosity |
| **Habitability** | Habitability Zone, Atmosphere Detected, Equilibrium Temperature, Insolation Flux |
| **Observation** | Distance from Earth (light-years), Transit Depth |

---

## 🛠️ Tools Used

- **Tableau** — dashboard design and visualization
- **Excel** — data cleaning and preparation
- **Generative AI** — supporting analysis and content generation

---

## 🚀 How to View

1. **Interactive dashboard:** Download `Exoplanet_Discovery_Habitability_Dashboard.twbx` and open it in [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/) (free).
2. **Quick look:** View the screenshots in the `images/` folder or scroll up to the previews above.
3. **Full write-up:** Open `Exoplanet_Discovery_Habitability_Report.docx` for the complete analysis, methodology, and key takeaways.

---

## 🔍 Key Insights

- Habitable-zone status is concentrated almost entirely among **Super-Earths** and **Terrestrial** planets — none of the Gas Giants, Hot Jupiters, Neptune-like, or Saturn-like planets in the sample qualify.
- Only **1 of 24** habitable-zone planets has a confirmed atmosphere — highlighting the gap between *detection* and *characterization*.
- Discovery activity peaked in **2008** and **2017**, aligned with major Kepler data-release cycles.
- Average distance from Earth varies sharply by planet type (73.5 ly for Neptune-like vs. 568.1 ly for Super-Earths), largely reflecting detection-method bias rather than physical clustering.

---

## 👤 Credit

**Dashboard designed & created by:** Soumya Ranjan Das
*Aspiring Data Analyst*

---

## 📄 License

This project is shared for portfolio and educational purposes. Feel free to explore, fork, and reference with attribution.
