# High Power Rocketry Airframe Integration: Optimizing Static Stability
**By Wildania Baez Polanco**

### 1. Project Objective
To safely upgrade a custom 70 cm launch vehicle from mid-power to high-power propulsion systems. Heavy motors shift the Center of Gravity (CG) rearward, causing dangerous stability degradation.

### 2. The Problem & The Solution
* **The Hazard:** Larger G and H-class motors significantly increase rear-end mass, shifting the Center of Gravity (CG) backwards and dropping the static stability margin as low as a catastrophic 0.089 cal (Safety threshold is 1.0–2.0 cal).
* **The Engineering Solution:** Designed a custom, concentric internal ballast compartment inside the nose cone using Fusion 360. 
* **The Modular Advantage:** This compartment is engineered to be completely modular. It allows flight crew to easily add, remove, or swap out variable counterweights on the field (such as 50g for G-motors or 80g for H-motors) to match the exact stability requirements of different motor profiles.

### 3. Final Simulated Flight Performance

| Motor Configuration | Peak Acceleration | Maximum Velocity | Apogee | Flight Safety Status |
| :--- | :--- | :--- | :--- | :--- |
| **H-130W (Unballasted)** | 516 m/s² | 245 m/s | 658 m | Severe Danger (Unstable) |
| **H-130W (With 80g Ballast)** | 432 m/s² | 228 m/s | 687 m | Safe / Stable |
| **G-Motor (With 50g Ballast)** | 297 m/s² | 155 m/s | 491 m | Safe / Stable |
