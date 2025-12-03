PARISHRAM 2026, Physics Lecture 01

Semiconductor Electronics
BY - RAKSHAK SIR

Topics to be covered
1. Band Theory
2. p - n Junction Diode

Syllabus: Unit IX: Electronic Devices, Chapter-14: Semiconductor Electronics: Materials, Devices and Simple Circuits
* Energy bands in conductors, semiconductors and insulators (qualitative ideas only)
* Intrinsic and extrinsic semiconductors - p and n type p-n junction
* Semiconductor diode - I-V characteristics in forward and reverse bias, application of junction diode - diode as a rectifier.

---

Types of Electronic Devices

The electronic devices are of two types:
1. Vacuum tubes: These include vacuum diodes, triode and pentode.
2. Solid-state electronic devices: In such devices, the charge carriers flow through solid-state semiconductors.

Comparison of Vacuum Tubes and Solid-State Electronic Devices

| Vacuum Tubes | Solid-State Electronic Devices |
| :--- | :--- |
| **Important features:** | **Important features:** |
| Electrons are obtained from a **heated cathode**. | Charge carriers flow through **solid-state semiconductors**. |
| A **vacuum** is necessary. | **Examples:** Junction diode (2-electrode), transistor (3-electrode, discovered in 1948), Integrated Circuits (ICs). |
| They are **bulky**. | They are of **small size**. |
| They consume **high power**. | They consume **low power**. |
| They operate at **high voltages** ($\approx 100\text{V}$). | They operate at **low voltages**. |
| They have **limited life** and **low reliability**. | They have **long life** and **high reliability**. |

The invention of solid-state electronic devices led to the miniaturization of electronic gadgets and the replacement of CRTs (based on vacuum tubes) with LCDs.

---

Classification of Solids (on the basis of Conductivity)

Solids are classified based on the relative values of electrical **conductivity ($\sigma$)** or **resistivity ($\rho$)** ($\rho = 1/\sigma$):

| Class | Resistivity ($\rho$) ($\Omega\ m$) | Conductivity ($\sigma$) ($S\ m^{-1}$) |
| :--- | :--- | :--- |
| **1. Metals (Conductors)** | $10^{-2}-10^{-8}$ | $10^2-10^8$ |
| **2. Insulators** | $10^{11}-10^{19}$ | $10^{-11}-10^{-19}$ |
| **3. Semiconductors** | $10^{-5}-10^{6}$ | $10^5-10^{-6}$ |

**Note:**
1. Semiconductors have a much **higher resistivity** than metals.
2. The resistivity of semiconductors **decreases rapidly with temperature** (they have a negative temperature coefficient, $\alpha$). The resistivity of metals increases with temperature.
3. Semiconductors have a considerably lower number density n of charge carriers (charge carriers per unit volume) than metals.

---

Energy Bands in Solids (Band Theory)

When atoms are brought together to form a solid, the discrete energy levels of isolated atoms broaden into **energy bands** with continuous energy variation.

* **Valence Band ($E_v$):** The band corresponding to the energy of the valence electrons. It is the **highest occupied** energy band. Electrons in this band **do not** contribute to electric current.
* **Conduction Band ($E_c$):** The band corresponding to the energy of free electrons (which conduct electricity). It is the **lowest unoccupied** energy band.
* **Energy Band Gap ($E_g$):** The energy separation between the top of the valence band ($E_v$) and the bottom of the conduction band ($E_c$). $E_g = E_c - E_v$. This is the minimum energy required to shift an electron from the valence band to the conduction band.

| Material | Energy Band Gap ($E_g$) | Conduction Band/Valence Band |
| :--- | :--- | :--- |
| **Metals** | $\mathbf{E_g = 0}$ or very small (bands overlap). | The valence band is partially filled, or the valence band overlaps with the conduction band. Conduction is easy. |
| **Insulators** | $\mathbf{E_g > 3\ \text{eV}}$ (Large). | The conduction band is empty. $E_g$ is too large for thermal energy to excite electrons to $E_c$. (e.g., Diamond, $E_g \approx 6\ \text{eV}$) |
| **Semiconductors** | $\mathbf{E_g < 3\ \text{eV}}$ (Small). | At room temperature, some electrons gain enough energy to jump across the small $E_g$ to the conduction band. (e.g., Ge $E_g = 0.72\ \text{eV}$, Si $E_g = 1.1\ \text{eV}$). Therefore, the semiconductor at zero kelvin behaves as insulator. |

---

Classification of Semiconductors

#### A. By Chemical Composition
1. Elemental semiconductors: Si (Silicon) and Ge (Germanium).
2. Compound semiconductors:
    * (i) Inorganic: CdS, GaAs, CdSe, InP, etc.
    * (ii) Organic: Polypyrrole, polythiophene, etc.

#### B. By Nature of Charge Carriers

| Type | Definition | Charge Carriers | Carrier Concentration |
| :--- | :--- | :--- | :--- |
| **1. Intrinsic (Pure)** | A pure semiconductor crystal (impurity less than 1 part in $10^{10}$). | **Electrons** and **holes**. | **Equal:** $n_e = n_h = n_i$. |
| **2. Extrinsic (Impure/Doped)** | A pure semiconductor to which small amounts of impurity atoms (dopants) are added. | Electrons and holes. | **Unequal:** $n_e \neq n_h$. |

**Intrinsic Semiconductors (Details):**
* **Current:** Total current $I_{\text{total}} = I_e + I_h$.
* **Holes:** A **vacancy** or absence of an electron in a covalent bond. It behaves as an apparent free particle with effective **positive charge** $(+e)$.
* An intrinsic semiconductor is **electrically neutral** as a whole.
* At **$T = 0\ \text{K}$**, it behaves like an **insulator**.
* **Mass-Action Law:** $n_e \times n_h = n_i^2$.

---

Extrinsic Semiconductors (Doping)

**Doping** is the deliberate addition of a small amount of impurity to a pure semiconductor to increase its conductivity.

#### A. n-type Semiconductor
* **Dopant:** **Pentavalent** (Group V) impurities (e.g., Arsenic (As), Antimony (Sb), Phosphorous (P)). They are called **Donors**.
* **Mechanism:** The impurity atom **donates** an extra "free" electron. This creates a **donor energy level ($E_D$)** just **below the conduction band ($E_c$)**.
* **Charge Carriers:** **Electrons** are the **majority** carriers; holes are minority carriers. $\mathbf{n_e \gg n_h}$.
* **Fermi Level ($E_F$):** Lies in the forbidden energy gap near the **conduction band**.

#### B. p-type Semiconductor
* **Dopant:** **Trivalent** (Group III) impurities (e.g., Indium (In), Boron (B), Aluminium (Al)). They are called **Acceptors**.
* **Mechanism:** The impurity atom creates a **hole** by **accepting** an electron. This creates an **acceptor energy level ($E_A$)** just **above the valence band ($E_v$)**.
* **Charge Carriers:** **Holes** are the **majority** carriers; electrons are minority carriers. $\mathbf{n_h \gg n_e}$.
* **Fermi Level ($E_F$):** Lies in the forbidden energy gap near the **valence band**.

---

Summary Table: Intrinsic vs. Extrinsic Semiconductors

| Point | Intrinsic Semiconductors | Extrinsic Semiconductors |
| :--- | :--- | :--- |
| **1.** | These are **pure** semiconducting tetravalent crystals. | These are semiconducting tetravalent crystals **doped** with impurity atoms of group III or V. |
| **2.** | Electrical conductivity is **low**. | Electrical conductivity is **high**. |
| **3.** | Number of free electrons ($n_e$) equals the number of holes ($n_h$). | $n_e \neq n_h$. |
| **4.** | Conductivity depends **only on temperature**. | Conductivity depends on **temperature as well as on dopant concentration**. |

Summary Table: n-type vs. p-type Semiconductors

| Point | n-type Semiconductors | p-type Semiconductors |
| :--- | :--- | :--- |
| **1.** | Doped with **group V (pentavalent)** impurities (Donors). | Doped with **group III (trivalent)** impurities (Acceptors). |
| **2.** | The donor impurity level lies just **below the conduction band** ($E_c$). | The acceptor impurity level lies just **above the valence band** ($E_v$). |
| **3.** | **Electrons** are the **majority** charge carriers. | **Holes** are the **majority** charge carriers. |
| **4.** | $\mathbf{n_e \gg n_h}$. | $\mathbf{n_h \gg n_e}$. |
