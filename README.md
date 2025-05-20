# 🛰️ 2024 YR4 - Asteroid Trajectory Analysis & Mission Design

## 📌 SUBJECT

- **The asteroid named _2024 YR4_ will pass close to Earth in December 2032.**
- **There is a potential risk of collision with the Moon.**

---

## 🎯 GOALS

### Phase 1: Close Approach Analysis

Timeframe: **October 1, 2032 – March 1, 2033**

1. Analyze 2024 YR4’s motion during this period.
2. Plot distance of the asteroid from:
   - The **Sun**
   - The **Moon**
   - The **Earth**
3. Plot the **Earth–YR4–Sun angle** over time.
4. Visualize the **ground-track** of the asteroid over:
   - The **Earth’s surface** (±6 hours around Time of Closest Approach - TCA)
   - The **Moon’s surface** (±6 hours around TCA)

---

### Phase 2: Interplanetary Mission Design

This phase focuses on designing a trajectory from Earth to asteroid 2024 YR4:

- Solve **Lambert’s problem** to compute interplanetary transfer orbits.
- Calculate **delta-v requirements** from **Low Earth Orbit (LEO)** to the asteroid.
- Generate **porkchop plots** to visualize feasible **departure/arrival windows**.
- Highlight **close approach dates** of the asteroid for mission planning.

---

## 🧰 LIBRARIES USED

| Library | Purpose |
|--------|---------|
| `numpy` | Numerical computations |
| `matplotlib.pyplot` | Plotting graphs |
| `matplotlib.colors`, `matplotlib.dates` | Custom plot formatting |
| `date2num`, `DateFormatter` | Time axis formatting |
| `datetime`, `timedelta`, `calendar` | Time and date handling |
| `spiceypy` | Access SPICE ephemeris data |
| `scipy.optimize.root_scalar` | Solving Lambert transfer equations |
| `scipy.ndimage.gaussian_filter` | Data smoothing for visualization |
| `os` | File system operations |

---

## 📈 OUTPUTS & VISUALS

- **Distance Plots** of 2024 YR4 from Earth, Moon, and Sun.
- **Angle Plots**: Earth–YR4–Sun angular variation over time.
- **Ground-tracks**: 2D projections of YR4’s motion on Earth and Moon around TCA.
- **Porkchop Plots**:
  - Color-coded maps of delta-v values vs. departure and arrival dates.
  - Used to identify optimal launch windows from Earth to the asteroid.

---

## 📁 REQUIREMENTS

- **SPICE Kernels** (planetary ephemerides, asteroid data) must be available and correctly loaded.
- **Python ≥ 3.8**
- All listed libraries must be installed via `pip` or `conda`.

---

## 🚀 MISSION APPLICATION

This project can be used as the basis for:

- **Asteroid flyby or rendezvous mission planning**
- **Trajectory optimization and delta-v budgeting**
- **Visual validation of SPICE-based space mission tools**

---


