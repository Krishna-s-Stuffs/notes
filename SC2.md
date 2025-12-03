Based on the provided PDF slides from the "Parishram 2026" Physics lecture by Rakshak Sir, here are the detailed lecture notes on **Semiconductor Electronics (Lecture 02).**

---

### **1. Numerical Problem (Law of Mass Action)**
**Question:** A pure Silicon (Si) crystal has $5 \times 10^{28}$ atoms/m³. It is doped by 1 ppm concentration of pentavalent Arsenic (As). Calculate the number of electrons ($n_e$) and holes ($n_h$).
*   **Given:** Intrinsic carrier concentration ($n_i$) = $1.5 \times 10^{16}$ m⁻³.
*   **Solution:**
    1.  **Calculate Electron Density ($n_e$):**
        *   Doping is 1 ppm (1 part per million), meaning 1 impurity atom per $10^6$ Si atoms.
        *   $n_e \approx N_D$ (Donor density).
        *   $N_D = \frac{5 \times 10^{28}}{10^6} = 5 \times 10^{22} \text{ m}^{-3}$.
    2.  **Calculate Hole Density ($n_h$):**
        *   Using the Law of Mass Action: $n_e \times n_h = n_i^2$
        *   $n_h = \frac{(1.5 \times 10^{16})^2}{5 \times 10^{22}}$
        *   $n_h = \frac{2.25 \times 10^{32}}{5 \times 10^{22}} = 0.45 \times 10^{10} = 4.5 \times 10^9 \text{ m}^{-3}$.

---

### **2. Classification of Semiconductors**

#### **Intrinsic vs. Extrinsic Semiconductors**
| Feature | Intrinsic Semiconductor | Extrinsic Semiconductor |
| :--- | :--- | :--- |
| **Purity** | Pure semiconducting tetravalent crystals (e.g., Pure Si, Ge). | Doped with impurity atoms of Group III or Group V. |
| **Conductivity** | Low electrical conductivity. | High electrical conductivity. |
| **Energy States** | No permitted energy state between valence and conduction bands. | Permitted energy states exist (Donor/Acceptor levels) in the band gap. |
| **Charge Carriers** | $n_e = n_h$ (Electrons = Holes). | Majority and Minority carriers exist ($n_e \neq n_h$). |
| **Dependency** | Conductivity depends on temperature. | Conductivity depends on temperature and dopant concentration. |

#### **n-type vs. p-type Semiconductors**
| Feature | n-type Semiconductor | p-type Semiconductor |
| :--- | :--- | :--- |
| **Doping** | Doped with Group V (Pentavalent) impurities. | Doped with Group III (Trivalent) impurities. |
| **Role** | Impurities provide free electrons (Donors). | Impurities create vacancies/holes (Acceptors). |
| **Impurity Level** | Donor level lies just **below** the conduction band. | Acceptor level lies just **above** the valence band. |
| **Carriers** | Majority: Electrons ($n_e$); Minority: Holes ($n_h$). | Majority: Holes ($n_h$); Minority: Electrons ($n_e$). |
| **Relation** | $n_e \gg n_h$ | $n_h \gg n_e$ |

---

### **3. The p-n Junction**

#### **Definition**
A single crystal of Ge or Si doped such that one half acts as a p-type semiconductor and the other half as an n-type semiconductor.

#### **Formation Process**
1.  **Diffusion Current:**
    *   Majority charge carriers move from higher concentration to lower concentration.
    *   Holes move $p \to n$.
    *   Electrons move $n \to p$.
2.  **Drift Current:**
    *   Due to the electric field developed across the junction, minority carriers move.
    *   Electrons move $p \to n$.
    *   Holes move $n \to p$.

#### **Key Regions**
*   **Depletion Region:** A small region near the junction depleted of free charge carriers, containing only immobile ions.
*   **Barrier Potential ($V_B$):** The accumulation of negative charges in the p-region and positive charges in the n-region creates a potential difference that opposes further diffusion.
    *   **Factors affecting $V_B$:** Nature of semiconductor, Temperature, Amount of doping.
    *   **Standard Values (at 300K):**
        *   Germanium (Ge): ~0.3 V
        *   Silicon (Si): ~0.7 V

---

### **4. Biasing of p-n Junction**

#### **Forward Bias**
*   **Connection:** Positive terminal of battery to **p-side**; Negative terminal to **n-side**.
*   **Effects:**
    1.  Barrier potential decreases ($V_0 - V$).
    2.  Width of depletion layer **decreases**.
    3.  Effective resistance decreases.
    4.  Current flows (measured in **mA**) due to majority carrier diffusion.

#### **Reverse Bias**
*   **Connection:** Positive terminal of battery to **n-side**; Negative terminal to **p-side**.
*   **Effects:**
    1.  Barrier potential increases ($V_0 + V$).
    2.  Width of depletion layer **increases**.
    3.  Resistance becomes very large.
    4.  No majority current; very small current (Reverse Saturation Current) flows due to minority drift (measured in **$\mu$A**).

---

### **5. V-I Characteristics**

#### **Forward Bias Graph**
*   **Non-Ohmic:** Does not obey Ohm's law (not a straight line).
*   **Cut-in/Knee Voltage:** Current increases very slowly until this voltage is reached (0.3V for Ge, 0.7V for Si).
*   **Exponential Rise:** After the cut-in voltage, current increases rapidly.

#### **Reverse Bias Graph**
*   **Reverse Saturation Current:** A small, constant current ($\mu$A) exists due to minority carriers.
*   **Breakdown Voltage (Zener Breakdown):** At a high reverse voltage, the current suddenly increases sharply.

#### **Dynamic Resistance ($r_d$)**
defined for non-ohmic devices like diodes.
$$r_d = \frac{\Delta V}{\Delta I}$$
It is the reciprocal of the slope of the V-I characteristic curve.

---

### **6. Junction Diode as a Rectifier**

**Rectifier:** A device used to convert Alternating Current (AC) into Direct Current (DC).
**Principle:** A diode offers low resistance in forward bias (conducts) and high resistance in reverse bias (blocks).

#### **A. Half-Wave Rectifier**
*   **Circuit:** Uses **one** diode.
*   **Operation:** Conducts only during the positive half-cycle of AC input. Blocks the negative half-cycle.
*   **Output:** Pulsating DC.
*   **Frequency:** Output frequency = Input frequency.

#### **B. Full-Wave Rectifier**
*   **Circuit:** Uses **two** diodes ($D_1$ and $D_2$) with a center-tap transformer.
*   **Operation:**
    *   Positive cycle: $D_1$ conducts, $D_2$ is reverse biased.
    *   Negative cycle: $D_2$ conducts, $D_1$ is reverse biased.
    *   Current flows through the load in the same direction during both cycles.
*   **Frequency:** Output frequency = $2 \times$ Input frequency.

#### **C. Capacitor Filter**
*   Rectifiers produce "pulsating DC". To smooth this, a **capacitor** is connected in parallel across the load.
*   **Function:** The capacitor blocks DC and passes AC components (bypassing the ripple), resulting in a smoother DC output.
