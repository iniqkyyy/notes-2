# AD/DC Dictionary
### Terms
- #Coulomb a coulomb $$C$$ is the total charge possessed by $$6.25x10^{18}$$ electrons. A single electron has a charge of $$e=1.6x10^{-19}$$.
- #Conductors have high current flow, used in wires, large number of free electrons, characterized by 1-3 valence electrons
- #Semiconductors are characterized by having exactly four valence electrons, Silicon, Boron, etc. can be manipulated to be an insulator or conductor.
- #Insulators have no free electrons, their valence electrons are bound to the atoms, does not allow electric current to pass through.
- #Resistivity is the resistive value of a specific element, whereas resistance depends on length is a total amount.
- #Ground is the point in a circuit where the voltage is 0.
### Formulas
- #Voltage voltage is depicted by $$V=\frac{W}{Q}$$ where $$V$$ is Voltage in Volts, $$W$$ is Work (or energy) in Joules, and $$Q$$ is Charge in Coulombs.
- #Amperage amps are depicted by $$I=\frac{Q}{t}$$ where $$I$$ is Current in Amps, $$Q$$ is Charge in Coulombs, and $$t$$ is Time in Seconds.
- #Ohms-Law $$\text{V}=\frac{\text{I}}{\text{R}}$$ can be rewritten to solve for current or resistance.
- #Watts-Law $$\text{P}=\text{V}\text{I}$$ can be rewritten as $$\text{P}=\frac{\text{V}^2}{\text{R}}$$ and $$\text{P}=\text{I}^2\text{R}$$
- #Wire-Resistance $$R=\frac{pl}{A}$$ where $$p$$ is the Resistivity in Circular Mill Ohms per Foot, $$l$$ is Length in Feet, and $$A$$ is the cross sectional area in Circular Mills.
- #Conductance is the reciprocal of Resistance $$G=\frac{1}{R}$$ where $$G$$ is Conductance in Siemens, and $$R$$ is Resistance in Ohms.
- #Ohms-Law $$I=\frac{V}{R}$$ where $$I = $$ Current, $$V = $$ Voltage, and $$R = $$ Resistance.
### Measuring
- Voltmeter connected in SERIES.
- Ammeter connected in PARALLEL.
- Ohmmeter connected in SERIES.
### Series Circuits
- $$\text{R}_T = \sum_{n=1}^{\text{\#ofR}}\text{R}_n$$
- Voltage drop across Series circuit sums to voltage source. (KVL)
- Current is constant throughout series, labeled $$\text{I}_T$$
- Voltage divider (voltage across a single resistor in a series circuit).
  - $$V_x=V_S\frac{R_x}{R_T}$$
- Power divider (power across a single resistor in a series circuit).
  - $$P_x=P_S\frac{R_x}{R_T}$$
### Parallel Circuits
- $$\text{R}_T = (\sum_{n=1}^{\text{\#ofR}} \frac{1}{R_n})^{-1}$$
- Voltage across parallel circuit is constant, labeled $$\text{V}_S$$
- Current divider (current across single resisistor in parallel circuit).
  - $$\text{I}_x=\text{I}_T(\frac{\text{R}_T}{\text{R}_x})$$
### Series Parallel Circuits
![for example](https://www.electronics-tutorials.ws/wp-content/uploads/2024/09/combination-series-parallel-circuits.jpg?fit=400%2C282)
  - R1 and R8 are in series with everything else and eachother 
    - $$\text{R}_1+\text{R}_8=\text{R}_{18}$$
  - R6 and R7 are in parallel with eachother
    -  $$\text{R}_6\space\vert\vert\space\text{R}_7$$
  - this is in series with R5 so add in series 
    - $$\text{R}_5 + (\text{R}_6\space\vert\vert\space\text{R}_7)$$
  - R2 R3 and R4 are in series 
    - $$\text{R}_2+\text{R}_3+\text{R}_4 = \text{R}_{234}$$
  - this is in parallel with R5/6/7 
    - $$(\text{R}_{234})\space\vert\vert\space(\text{R}_5 + \text{R}_6\space\vert\vert\space\text{R}_7)$$
  - add in series with R1 and R8
    - $$\text{R}_T=\text{R}_{18}+(\text{R}_{234}\space\vert\vert\space(\text{R}_5 + (\text{R}_6\space\vert\vert\space\text{R}_7)))$$
### RC Circuits
- Capacitors (units of Farads) store charge (volts) and release over time, also charge over time.
  - $$C = \frac{Q}{V}$$
    - C is capacitance, Q is charge, V is volts.
  - $$W=\frac{1}{2}CV^2$$
    - W is energy, C is capacitance, V is volts.
  - $$C=8.85\text{E-12}\frac{\epsilon_{r}A}{d}$$
    - C is capacitance, 8.85E-12*epsilon is the dielectric constant, A is the area of the plates, and d is the distance between plates.
  - $$V_x=V_S(\frac{C_T}{C_x})$$
    - Voltage divider for capacitors.
  - Behave **opposite** to resistors, in parallel sum capacitance, in series take reciprocal of sum of reciprocals.
  - Universal Time Consetant
    - $$\tau=RC$$
    - takes 5*RC seconds to fully charge/discharge
  - Instantaneous Voltage
    - $$v_c=V_F + (V_i - V_F)e^{\frac{-t}{RC}}$$
- Reactance
  - 
