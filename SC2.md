Based on the provided PDF screenshots from the "Parishram 2026" Physics lecture by Rakshak Sir, here are the detailed lecture notes for **Semiconductor Electronics (Lecture 01)**.

---

# **Semiconductor Electronics – Lecture 01 Notes**

## **1. Evolution of Electronic Devices**

### **A. Vacuum Tubes (Historical Context)**
Before semiconductors, electronics relied on vacuum tubes (Vacuum diodes, triodes, pentodes).
*   **Mechanism:** Electrons are emitted from a heated cathode and flow to the anode through a vacuum. Voltage controls the flow.
*   **Drawbacks:**
    *   **Bulky:** Large size.
    *   **High Power:** Consumes high power and operates at high voltages (~100V).
    *   **Short Life:** Low reliability and limited lifespan.
    *   **Heating Required:** Needs cathode heating to produce electrons (thermionic emission).
    *   **Vacuum Essential:** Requires a vacuum to prevent electron collision with air molecules.

### **B. Solid-State Devices (Semiconductors)**
*   **History:** realized in the 1930s; Transistor discovered in **1948**.
*   **Mechanism:** Charge carriers flow *inside* the solid semiconductor material.
*   **Advantages:**
    *   **Small Size:** Enables miniaturization (ICs).
    *   **Low Power:** Operates at low voltages and consumes less power.
    *   **Reliable:** Long life and high reliability.
    *   **Instant On:** No cathode heating required; starts immediately.
    *   **Impact:** Replaced CRTs with LCD/LEDs; enabled modern computers and integrated circuits (ICs).

---

## **2. Classification of Solids**

Solids are classified based on their electrical conductivity ($\sigma$) and resistivity ($\rho = 1/\sigma$).

### **A. Metals**
*   **Conductivity:** Very High ($\sigma \approx 10^2 - 10^8 \, \text{Sm}^{-1}$)
*   **Resistivity:** Very Low ($\rho \approx 10^{-2} - 10^{-8} \, \Omega\text{m}$)

### **B. Insulators**
*   **Conductivity:** Very Low ($\sigma \approx 10^{-11} - 10^{-19} \, \text{Sm}^{-1}$)
*   **Resistivity:** Very High ($\rho \approx 10^{11} - 10^{19} \, \Omega\text{m}$)

### **C. Semiconductors**
*   **Conductivity:** Intermediate ($\sigma \approx 10^5 - 10^{-6} \, \text{Sm}^{-1}$)
*   **Resistivity:** Intermediate ($\rho \approx 10^{-5} - 10^{6} \, \Omega\text{m}$)
*   **Key Properties:**
    1.  Resistivity is higher than metals.
    2.  **Negative Temperature Coefficient of Resistivity ($\alpha$):** Unlike metals, the resistivity of semiconductors **decreases** as temperature increases.
    3.  Lower number density ($n$) of charge carriers compared to metals.

---

## **3. Types of Semiconductors**

### **A. Based on Chemical Composition**
1.  **Elemental:** Silicon (Si) and Germanium (Ge).
2.  **Compound:**
    *   **Inorganic:** CdS, GaAs, CdSe, InP.
    *   **Organic:** Polypyrrole, polythiophene, anthracene.

### **B. Based on Source of Charge Carriers**
1.  **Intrinsic:** Pure semiconductors (Impurity < 1 part in $10^{10}$).
2.  **Extrinsic:** Doped semiconductors (Impurities added to modify conductivity).

---

## **4. Band Theory of Solids**

In isolated atoms, electrons occupy discrete orbitals. In solids, atoms are close, causing outer orbits to overlap and split into continuous energy bands.

### **Terminology**
*   **Valence Band (VB):** The lower energy band occupied by valence electrons. It is never empty. Electrons here do not contribute to current unless excited.
*   **Conduction Band (CB):** The upper energy band. Empty at 0K. Electrons here can move freely and conduct current.
*   **Energy Band Gap ($E_g$):** The forbidden energy region between the top of the VB and the bottom of the CB. No electrons can exist here.
    *   Formula: $E_g = E_C - E_V$

### **Differences based on Band Theory**

| Material | Band Structure Description | Energy Gap ($E_g$) | Behavior |
| :--- | :--- | :--- | :--- |
| **Metals** | VB and CB overlap OR CB is partially filled. | $E_g \approx 0$ | Electrons move easily; high conductivity. |
| **Insulators** | Large gap between VB and CB. | $E_g > 3 \text{ eV}$ (e.g., Diamond $\approx 6 \text{ eV}$) | Electrons cannot jump to CB thermally. No conduction. |
| **Semiconductors** | Small finite gap. | $E_g < 3 \text{ eV}$ | At **0K**: Insulator (CB empty). <br> At **Room Temp**: Electrons gain thermal energy to jump to CB. |

**Important Values:**
*   **Germanium (Ge):** $E_g \approx 0.72 \text{ eV}$
*   **Silicon (Si):** $E_g \approx 1.1 \text{ eV}$

---

## **5. Intrinsic Semiconductors (Pure)**

*   **Examples:** Pure Si or Ge (Tetravalent - Valency 4).
*   **Bonding:** Atoms form covalent bonds sharing 4 electrons with neighbors.
*   **At 0K:** All bonds are intact. No free carriers. Behaves as an **insulator**.
*   **At T > 0K (Thermal Excitation):**
    *   Thermal energy breaks some covalent bonds.
    *   Electrons escape to the Conduction Band (creating **Free Electrons**).
    *   The vacancy left behind in the bond is called a **Hole**.

### **Concept of a Hole**
*   A vacancy created by the removal of an electron.
*   Behaves as an apparent free particle with **positive charge ($+e$)**.
*   Moves towards negative potential (effective movement of bound electrons filling vacancies).
*   **Current:** Total current ($I$) is the sum of electron current ($I_e$) and hole current ($I_h$).
    $$I_{\text{total}} = I_e + I_h$$

### **Carrier Concentration**
*   In intrinsic semiconductors, the number of free electrons ($n_e$) equals the number of holes ($n_h$).
    $$n_e = n_h = n_i$$
    *(where $n_i$ is intrinsic carrier concentration)*
*   **Temperature Dependence:**
    $$n_i = C e^{-E_g / 2kT}$$
    *(Conductivity increases with Temperature)*

### **Limitations of Intrinsic Semiconductors**
1.  Low conductivity (small number of carriers).
2.  Conductivity depends only on temperature (cannot be controlled easily).
3.  $n_e = n_h$, preventing specific device applications that need majority carriers.

---

## **6. Extrinsic Semiconductors (Doped)**

To improve conductivity, impurities are added to pure semiconductors. This process is called **Doping**.
*   **Dopant:** The impurity atom added (ppm level).
*   **Condition:** Dopant size must be similar to the host atom to prevent lattice distortion.

### **A. n-type Semiconductor**
*   **Dopant:** **Pentavalent** (Group 15 elements: **P, As, Sb**).
*   **Mechanism:**
    *   Replaces a Si atom.
    *   4 electrons form bonds with Si.
    *   The **5th electron** is loosely bound and becomes free with very little energy ($0.01 - 0.05 \text{ eV}$).
*   **Carriers:**
    *   **Majority:** Electrons ($n_e$).
    *   **Minority:** Holes ($n_h$).
    *   Relation: **$n_e \approx N_d \gg n_h$** (where $N_d$ is donor density).
*   **Band Diagram:** Creates a **Donor Level ($E_D$)** just **below** the Conduction Band.
*   **Name:** "n-type" because negative charge carriers (electrons) dominate.

### **B. p-type Semiconductor**
*   **Dopant:** **Trivalent** (Group 13 elements: **Al, B, In**).
*   **Mechanism:**
    *   Replaces a Si atom.
    *   3 electrons form bonds.
    *   The **4th bond has a vacancy (hole)**.
    *   This hole can easily accept an electron from a neighbor.
*   **Carriers:**
    *   **Majority:** Holes ($n_h$).
    *   **Minority:** Electrons ($n_e$).
    *   Relation: **$n_h \approx N_a \gg n_e$** (where $N_a$ is acceptor density).
*   **Band Diagram:** Creates an **Acceptor Level ($E_A$)** just **above** the Valence Band.
*   **Name:** "p-type" because positive charge carriers (holes) dominate.

---

## **7. Important Relations & Facts**

### **Mass Action Law**
At thermal equilibrium, for both intrinsic and extrinsic semiconductors:
$$n_e \times n_h = n_i^2$$

### **Electrical Neutrality**
*   **Crucial Point:** Both n-type and p-type semiconductors are **electrically neutral** as a whole. The total negative charge (electrons + ionized acceptor atoms) equals the total positive charge (holes + ionized donor atoms).

---

## **8. Comparison Tables**

### **Intrinsic vs. Extrinsic**
| Feature | Intrinsic | Extrinsic |
| :--- | :--- | :--- |
| **Purity** | Pure | Doped with Impurities |
| **Conductivity** | Low | High |
| **Carriers** | $n_e = n_h$ | $n_e \neq n_h$ (Majority/Minority) |
| **Control** | Depends on Temp only | Depends on Temp and Dopant amount |

### **n-type vs. p-type**
| Feature | n-type | p-type |
| :--- | :--- | :--- |
| **Impurity** | Pentavalent (Group 15) | Trivalent (Group 13) |
| **Role** | Donor (Donates electrons) | Acceptor (Accepts electrons/Creates holes) |
| **Majority** | Electrons ($n_e \gg n_h$) | Holes ($n_h \gg n_e$) |
| **Energy Level** | Donor level near Conduction Band | Acceptor level near Valence Band |

---

## **9. Homework Question (from Slide 53)**

**Problem:**
Suppose a pure Si crystal has $5 \times 10^{28}$ atoms $\text{m}^{-3}$. It is doped by 1 ppm concentration of pentavalent As. Calculate the number of electrons and holes. Given that $n_i = 1.5 \times 10^{16} \text{ m}^{-3}$.

**Hint for Solution:**
1.  Calculate Donor density ($N_d$) using 1 ppm of total atoms.
    *   $N_d = \frac{1}{10^6} \times 5 \times 10^{28}$
2.  Assume $n_e \approx N_d$.
3.  Use Mass Action Law ($n_e n_h = n_i^2$) to find $n_h$.
   

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
