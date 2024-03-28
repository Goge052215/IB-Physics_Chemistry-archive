# B.2 Thermodynamics

## 1. Internal Energy

Internal energy is the sum of the random kinetic energy of the molecules and their total potential energy.

Hence, for an ideal gas, the internal energy is just the total kinetic energy of all its molecules.

We know that the average kinetic energy ($\overline{E_k}$) of a gas molecule is proportional to the absolute temperature of the gas ($T$) only and is given by:

$\displaystyle \overline{E_k} = \frac{3}{2}k_B T$

where $k_B$ is the Boltzmann constant.

Assume there are $N$ gas particles, each of which has an average kinetic energy of $\frac{3}{2}k_B T$, the total internal energy $U$ will be:

$\displaystyle U = N × \frac{3}{2}k_B T$

Using $R = k_B × N_A$ where $R$ is the ideal gas constant and $N_A$ is the Avogadro’s number:

$\displaystyle U = \frac{3}{2} × N ×\frac{R}{N_A} T$

because $\displaystyle n = \frac{N}{N_A}$,

$\displaystyle U = \frac{3}{2} nRT$

### Worked Example

Calculate the internal energy in $1 \text{ mol}$ of a monatomic gas at $273 \text{ K}$.

$\displaystyle U = \frac{3}{2} nRT = \frac{3}{2} × 1 × 8.31 × 273 = 3400 \text{ J}$

## 2. Work done on/by a gas

Consider a gas piston, as shown below:

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.2.1.1-Gas-in-a-piston-expands-slightly,-doing-work.9e8904d0ea5b4c48caf2.png?w=1200&auto=compress" width = "600" height = "auto">

(Source: Kognity)

When we expand slightly with a distance of $Δx$, the volume increases by $ΔV$. Assume that the cross-sectional area is $A$, and the pressure is $p$. The work done by the gas particles is given by:

$W = F × s = pA × Δx = pAΔx$

because the increase in volume $ΔV$ equals to $AΔx$, the formula above can be rewritten as:

$W = pΔV$

## 3. The First Law of Thermodynamics

The region external to the system with which it interacts is called the surroundings

If part of the surroundings is designed to provide heat or absorb heat, we refer to this as a reservoir

If a quantity of energy $Q$ is supplied to a gas, it can gain internal energy $ΔU$ and/or do work on its surroundings $W$. So, from the law of conservation of energy:

$Q = ΔU + W$

### Worked Example

**Q1:** In a thermodynamic process, $75 \text{ J}$ of work is done on an ideal gas when it is compressed. If its internal energy decreases by $14 \text{ J}$, how much thermal energy is removed from a gas?

$W = -75 \text{ J}$
$ΔU = -14 \text{ J}$

**Q2:** An ideal gas of volume $0.020 \text{m}^3$ expands to a volume $0.025 \text{m}^3$ at a constant pressure of $1.1 × 10^5 \text{ Pa}$ by applying a thermal energy of $9.0 × 10^3 \text{ J}$. What is the change in the internal energy of the gas?

$W = pΔV = -550 \text{ J}$
$ΔU = 9000 \text{ J}$
$Q = ΔU + W = 9000 - 550 = 8450 \text{ J}$

### Isothermal & Isovolumetric Process

During an isothermal process, the temperature remains constant. This means that internal energy remains constant.

$ΔU = 0 \text{ J}$
$Q = W$

During an isovolumetric process, volume remains constant. This means that no work is done on or by the gas.

$W = 0 \text{ J}$
$Q = ΔU$

### Isobaric & Adiabatic Process

During an isobaric process, pressure remains constant.

During an adiabatic process, no thermal energy is transferred between a gas and its surroundings.

$W = -ΔU$

For a fixed quantity of an ideal, monatomic gas, when its state changes adiabatically from pressure $p_1$ and volume $V_1$ to pressure $p_2$ and volume $V_2$ then:

$p_1V_1^{\frac{5}{3}} = p_2V_2^{\frac{5}{3}}$

In other words, for an adiabatic change of an ideal, monatomic gas:

$pV^{\frac{5}{3}} = \text{Constant}$

We can further derive the equation from the ideal gas law:

$T_1V_1^{\frac{2}{3}} = T_2V_2^{\frac{2}{3}}$

where $T$ is the temperature measured in Kelvin.

## 4. Diagrams

Boyle's Law explains that the pressure of a fixed mass of gas is inversely proportional to its volume, at a fixed temperature, and the curves, called isotherms, show this relationship:

$\displaystyle p ∝ \frac{1}{V}$

This means that:

**The faster the volume decreases, the higher the temperature is.**

We can visualize the four processes in the figure below:

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.2.3.2%20A%20pV%20diagram%20representing%20four%20different%20processes.88cfabd960b994531236.png?w=1200&auto=compress" width="600" height="auto">

(Source: Kognity)

The table below the change of state for each of the four processes, in terms of changes to its pressure, volume, or temperature.

|  | Process | Pressure | Volume | Temperature |
|:--|:--|:--|:--|:--|
| $X → A$ | Isobaric | No Change | Increase | Increase |
| $X → B$ | Isovolumetric | Decrease | No Change | Decrease |
| $X → C$ | Isothermal | Decrease | Increase | No Change |
| $X → D$ | Adiabatic | Decrease | Increase | Decrease |

### Example Questions - IV Diagrams

What is the work done by a gas changing from state A to state B, as indicated in the following $pV$ diagram? Give your answer with units and correct two significant figures.

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/23768.83c7444a774d8665fdbb.png?w=1374&h=657&fit=&crop=&auto=compress&q=null" width = "600" height = "auto">

(Source: Kognity)

$Q = ΔU + W$
$W = ΔU - Q = 3 × 10^5 × 6 × 10^{-6} + \frac{1}{2} × 3 × 10^5 × 6 × 10^{-6} = 1.8 \text{ J} + 0.9 \text{ J} = 2.7\text{ J}$

## 5. Entropy & 2nd Law of Thermodynamics

Entropy ($S$) is a measure of the amount of disorder in a system.

We can define the change in entropy ($ΔS$) which occurs when heat ($ΔQ$) is transferred to or from a system at constant temperature ($T$, measured in Kelvin) as:

$ΔS = \frac{ΔQ}{T}$

the unit of entropy is ($\text{JK}^{-1}$)

**Note:** This formula can be only used for changes that occur at constant temperature.

### The 2^nd Law of Thermodynamics

The second law of thermodynamics can be understood in terms of entropy changes that take place in an isolated system.

Imagine you break a dish plate, this process is **irreversible**, you cannot fix a broken plate. However, if your ice cream melts in a hot summer, it is possible to reverse this process.

In thermodynamics, a reversible process is one **whose direction is reversed by an infinitesimal change** to a property of the system **without** increasing its entropy.

All natural processes are **irreversible**. This is an important consequence of the second law of thermodynamics, which can be stated in three different ways.

This leads us to the Planck Statement, which:

- In an irreversible process, the total entropy of an isolated system increases. In a reversible process, the total entropy of a system remains unchanged.

Remember that increased entropy is associated with increased disorder and that the second law is applied to an isolated system.

### The Clausius statement

Thermal energy cannot **spontaneously** be transferred from a cold to a hot body.

Work must be done to transfer thermal energy from a cold to a hot body.

### The Kelvin statement

In a cyclic process, it is impossible to completely convert heat into work.

### Example Questions - Entropy

What is the change in entropy when a $2.0 \text{ kg}$ block of ice melts slowly at $0.0° \text{C}$? (The specific latent heat of fusion of ice is $330 \text{ kJkg}^{-1}$)

$ΔS = \frac{ΔQ}{T} = \frac{mL}{T} = \frac{2 × 330}{273} = 2.4 \text{ kJ K}^{-1}$

## 6. Thermodynamic Cycles

A thermodynamic cycle is a sequence of processes that in turn vary the pressure, volume, and temperature of a gas, but eventually, return it to its initial state.

The cycle consists of an isothermal expansion, then an isovolumetric cooling, and an adiabatic compression to return the gas to its initial state.

The main objective of a heat engine is to absorb thermal energy and cause gas to expand, therefore doing useful work.

In general, the efficiency of any process is given by the equation in the Physics Data Booklet:

$\displaystyle η = \frac{\text{useful workdone}}{\text{total output}}$

**Key point:** The work done by a system in a thermodynamic cycle is equal to the area enclosed by the cycle on a $pV$ diagram.

### The Carnot Cycle

The Carnot Cycle consists of four basic reversible processes meaning that the cycle as a whole is also reversible. The four reversible processes are:

1. Isothermal expansion
2. Adiabatic expansion
3. Isothermal compression
4. Adiabatic compression

The 4 steps are visualized in the image below:

<img src="https://mechaniclove.com/wp-content/uploads/2017/12/Screen_shot_2010-10-30_at_8.56.41_PM.png" width = "600" height = "auto">

(Source: MechanicLove)

**Note:** The process moves between two isotherms: Cold and Hot. The Hot isotherm located above, aligns partly with the isothermal expansion curve, whereas the Cold isotherm located below, aligns partly with the isothermal compression curve.

As the cycle returns the system to its initial temperature, there can be no overall change in internal energy. Hence, the total work done by the gas in a single cycle will just be the net heat absorbed:

$W = Q_{12} - Q_{34}$

From $2$ to $3$ or $4$ to $1$ there is no thermal energy exchanged with the surroundings, so no change in entropy. The total change in entropy in one cycle will therefore be:

$ΔS = ΔS_{12} + ΔS_{34}$

$\displaystyle ΔS = \frac{ΔQ_{12}}{T_{\text{Hot}}} - \frac{ΔQ_{34}}{T_{\text{Cold}}}$

Because the reaction returns to the initial state,

$ΔS = 0$

$\displaystyle \frac{ΔQ_{34}}{T_{\text{Cold}}} = \frac{ΔQ_{12}}{T_{\text{Hot}}}$

$\displaystyle \because η = \frac{\text{useful workdone}}{\text{total output}}$

$\displaystyle \therefore η = \frac{Q_{12} - Q_{34}}{Q_{12}} = 1 - \frac{Q_{34}}{Q_{12}}$

$\displaystyle \because \frac{Q_{12}}{Q_{34}} = \frac{T_{\text{Hot}}}{T_{\text{Cold}}}$

$\displaystyle \therefore η_{\text{Carnot}} = 1 - \frac{T_{\text{Cold}}}{T_{\text{Hot}}}$

### Example Question - Thermodynamic Cycles

**Q1:** What is the efficiency of a Carnot engine operating between reservoirs at $45°\text{C}$ and $345°\text{C}$?

$\displaystyle η_{\text{Carnot}} = 1 - \frac{T_{\text{Cold}}}{T_{\text{Hot}}} = 1 - \frac{45 + 273}{345 + 273} = 0.485$

**Q2:** What is the maximum efficiency for a heat engine operating between reservoirs at $320\text{ K}$ and $390\text{ K}$?

$\displaystyle η = 1 - \frac{T_{\text{Cold}}}{T_{\text{Hot}}} = 1 - \frac{320}{390} = 0.18$

**Q3:** What is the net work done on gas during one cycle of the thermodynamic process illustrated in the following $pV$ diagram? Give your answer in MJ.

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/23770.f72c7ee058649e5ec496.png?w=1374&h=657&fit=&crop=&auto=compress&q=null" width = "600" height = "auto">

$W = (7-2) × \frac{1}{2} × (7-3) × 10^5 = 1 \text{ MJ}$

**Q4:** What is the efficiency of a Carnot engine operating with a cold reservoir at $0.0°\text{C}$ and a hot reservoir at $110°\text{C}$?

$\displaystyle η = 1 - \frac{T_{\text{Cold}}}{T_{\text{Hot}}} = 1 - \frac{273}{883} = 0.29$

**Q5:** A heat engine operates the Carnot cycle with a hot reservoir at $90°\text{C}$ and a cold reservoir at $25°\text{C}$. During a cycle, it absorbs $940 \text{J}$ of energy from the hot reservoir and returns $560 \text{J}$ to the cold reservoir. What is the change in entropy during one complete cycle?

$\displaystyle ΔS = \frac{940}{363} - \frac{560}{298} = 0.71 \text{JK}^{-1}$

## Key Formulas

### Internal Energy

$\displaystyle U = \frac{3}{2} nRT$

### Work done

$W = pΔV$

### The 1^st Law of Thermodynamics

$Q = ΔU + W$

$pV^{\frac{5}{3}} = \text{Constant}$

$p_1V_1^{\frac{5}{3}} = p_2V_2^{\frac{5}{3}}$
$T_1V_1^{\frac{2}{3}} = T_2V_2^{\frac{2}{3}}$

### Entropy

$\displaystyle ΔS = \frac{ΔQ}{T}$

### Carnot Efficiency

$\displaystyle ΔS = \frac{ΔQ_{12}}{T_{\text{Hot}}} - \frac{ΔQ_{34}}{T_{\text{Cold}}}$

$\displaystyle η = \frac{\text{useful workdone}}{\text{total output}}$

$\displaystyle η_{\text{Carnot}} = 1 - \frac{T_{\text{Cold}}}{T_{\text{Hot}}}$
