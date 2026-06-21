# Modular Propulsion Integration & Static Stability Optimization
**By Wildania Baez Polanco** |

## Project Vision & Professional Focus
This project represents my core interest in **propulsion systems integration, rocket motor flight dynamics, and structural launch configurations**. When scaling a launch vehicle to higher-impulse motors, the primary engineering challenge is managing severe shift changes in flight stability margins caused by increased propellant mass. 

Instead of treating stability as a static problem requiring a total vehicle redesign for every single launch, this project introduces a **modular airframe integration system** designed to adapt dynamically to varying motor thrust profiles.

## The Propulsion Challenge & The "Zero-Redesign" Solution

* **The Problem (Propulsion-Driven Instability):** Upgrading from mid-power to high-power solid rocket motors (specifically moving across G and H-impulse classes) significantly increases rear-end mass. This shifts the vehicle's Center of Gravity (CG) dangerously rearward, crushing the static stability margin down to well below the safe 1.0–2.0 cal threshold.
* **The Traditional Inefficiency:** Usually, switching to a more powerful motor forces a complete, costly structural redesign of the airframe, altering fin geometry or body tube lengths to compensate for the weight distribution.
* **The Engineering Solution:** I designed a custom, concentric internal weight compartment integrated into the nose cone using Fusion 360. 
* **The Design Philosophy (Modular Adaptability):** It is **not just a piece of metal**. It is a dynamic flight-tuning system. The compartment allows the flight crew to field adjust the ballast on demand. Depending on the exact impulse class and mass of the chosen motor, weight can be mechanically added or removed in seconds **completely eliminating the need to redesign the physical rocket.** 

---

## 🔬 Experimental Case Study: G vs. H-Class Motors

To validate this modular propulsion integration system, simulations were conducted across two distinct motor profiles using OpenRocket, proving that stability can be recovered strictly through modular ballast adjustments.

| Propulsion Configuration | Ballast Mass | Peak Acceleration | Maximum Velocity | Apogee | Flight Safety Status |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **G-Motor [G76G-6] (Unballasted)** | 0g | 310 m/s² | 162 m/s | 468 m | Marginal / Unstable |
| **G-Motor [G76G-6] (Optimized)** | **60g** | **310 m/s²** | **159 m/s** | **492 m** | **Safe & Stable (1.22 cal)** |
| **H-130W Motor (Unballasted)** | 0g | 516 m/s² | 245 m/s | 658 m | Catastrophic Instability (0.089 cal) |
| **H-130W Motor [H130W-7] (Optimized)** | **80g** | **433 m/s²** | **228 m/s** | **687 m** | **Safe & Stable (1.12 cal)** |

---

## 📂 Repository Contents & Engineering Deliverables
* **CAD:** Contains the `.step`file of the modular internal weight compartment as well as the rest of the components modeled in Fusion 360.
* **Simulations:** Raw .ork` (OpenRocket) file containing the complete vehicle configuration and environmental flight profiles for both G and H motors.
* **Report_Airframe_Integration.docx:** The final engineering brief outlining structural materials selection (plywood internal components, cardboard body tubes) and mass-over-time flight graphs.
