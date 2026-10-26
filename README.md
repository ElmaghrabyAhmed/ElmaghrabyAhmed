## Hi, I'm Ahmed

### GNSS Algorithms Engineer & PhD Researcher (Dissertation successfully defended) | Precise Time and Frequency Transfer Specialist 

I am a GNSS Expert with research background in **GNSS-based frequency trasnfer** and **error modeling** for high-precision PNT (Positioning, Navigation and Timing) algorithms. My work focused on characterizing the impact of errors on GNSS-based links that are utilized for frequency transfer and time synchrnoization. 

---

### 🛰️ Core Expertise & Domain Knowledge


### 🛠️ Technical Stack
Languages/Tools: Matlab, Python, C++, Java
Domain Keywords: Frequency transfer, Allan variance, time synchronization, GNSS metrology networks.
Scientific programming in Matlab and Python
Precising timing and positioning algorithms implementation
Frequency stability and accuracy evaluation


---

### 📂 Featured GNSS Repositories

[GNSS Planner](https://github.com/ElmaghrabyAhmed/gnss-planner)
 
A Python/Tkinter tool that combines GNSS mission planning with data analysis:
 
- **Planning:** satellite visibility, DOP and common-view windows for up to six stations (GPS, GLONASS, Galileo, BeiDou, QZSS)
- **RINEX analysis:** automatic download of daily observation files; tracking, C/N0 and geometry-free phase plots with cycle-slip indicators


- Unit-tested parsers, continuous integration on GitHub Actions, documented methods and data sources

---
 e.g. the ground tracks at PTBB:
![GNSS Planner](https://github.com/ElmaghrabyAhmed/gnss-planner/blob/main/docs/img/gnss_planner_observations.png)

--- 
e.g. the satellite visibility at PTBB:
![GNSS Planner](https://github.com/ElmaghrabyAhmed/gnss-planner/blob/main/docs/img/satellite_visibility_ptbb.png)


`Python` `NumPy` `Matplotlib` `scikit-learn` `Tkinter` `pytest` `GitHub Actions`

---
[GNSS Positioning Engine](https://github.com/ElmaghrabyAhmed/gnss_repository)

A high-performance C++ tool implemented to compute the receiver position from raw GNSS data. The application processes standard RINEX observation and navigation files, applying advanced atmospheric corrections to deliver precise coordinate estimations via two distinct positioning algorithms.

## Key Features

* **Dual Positioning Algorithms:**
  * **SPP (Single Point Positioning):** Snapshot-based least-squares estimation for absolute positioning.
  * **EKF (Extended Kalman Filter):** Time-sequential filtering that incorporates process noise and dynamics for smoothed trajectory estimation.
* **Atmospheric Error Mitigation:**
  * **Ionospheric Correction:** Implements the Klobuchar model utilizing broadcast coefficients from the navigation message.
  * **Tropospheric Correction:** Implements the Saastamoinen model to calculate dry and wet delay components.
* **Standard File Format Support:** Fully parses RINEX Observation (`.o`) and Navigation (`.n` / `.p`) files.

## Prerequisites

Ensure you have the following installed on your system:
* A C++ compiler supporting **C++17** or higher (GCC, Clang, or MSVC)
* **CMake** (version 3.10 or higher)

## Input Data Requirements
* **Observation File:** Multi-epoch RINEX file containing pseudorange observables (e.g., C1C, C1W).
* **Navigation File:** Broadcast ephemeris file providing satellite orbit parameters and Klobuchar ionospheric coefficients.


---

- 🔭 I’m currently working on advancing a python-based tool for planning and assessing GNSS observations. Additionally, I implement an algorithm in C++ to exploit GNSS observations for precise positioing.
- 🌱 I’m currently learning the Gaussian process and its application in machine learning, and I am doing this by implementing a tool that uses the historic data from Ionosphere to predict the anomalies of GNSS observations.
- 👯 I’m looking to collaborate on improving the atmospheric models for GNSS high-precision applications.
- 💬 Ask me about GNSS-based frequency transfer and the stochastic modeling of GNSS errors. How to assess the stability of frequency links?
- ⚡ Fun fact: I bake my own bread using home-grown sour dough:=) 
---

### 📈 Find Me Outside of GitHub
* 💼 Connect with me on [LinkedIn]([https://linkedin.com](https://www.linkedin.com/in/elmaghrabyahmed/))
* 📧 Reach out via Email: `elmaghraby.ahmed@gmx.de`



-->
