# Photonics 1 Lesson 13
- phonons kind of "Create" positive charge by compressing nuclei together, also creating negative charge on the opposite side
- just reviewing lecture 1 and 2 at the beginning
- vibrations of atoms (phonons) have little energy but high momentum, allowing normally forbidden energy transitions

## Doping Semiconductors
- Adding a donor atom contributes a free electron, adding an acceptor creates a hole.
- n-type is a donor (Lead Pb), p-type is an acceptor (Boron B)
- arsenic is a more common donor
- Silicon
  - Acceptors
    - Boron
    - Aluminum
    - Gallium
    - Indium
  - Donors
    - Phosphorous
    - arsenicAntimony
    - Bismuth
    - Lithium
- GaAs
  - Acceptors
    - Beryllium
    - Zinc
    - Chromium
    - Silicon
  - Donors
    - Beryllium
    - Tellurium
    - Sulfur
    - Chromium
    - Silicon
    - Carbon
- Chromium and Silicon can be used as an acceptor and donor in GaAs because of how they sit in the lattice
- How to dope?
  - Silicon wafer exposed to a dopant material in gas form will slowly deposit in the surface of the material
  - could also use high-energy dopant ions accelerated towards the material which makes a deeper penetration with lower amounts on the surface
- Intrinsic = pure material
- n-type current flows in conduction band, but p-type current flows in valence band because the holes are in the valence band
- 1 dopant per 100million is light doping, 1 dopant per 1000 is heavy doping
- heavy doping is like p+ or n+
- heavily doped material is almost like a metal

## Fermi-Dirac in Dopant Ionization
- Basically number of ionized dopant atoms divided by the total number of dopant atoms is equal to the fermi-dirac statistical model
- number of excited electrons compared to the number of dopant atoms drops off at near zero temperatures, and rises rapidly at a certain high temperature solely due to heat, unrelated to doping, however there is a distinct flatline in this graph in the center

## Junctions
- P touching N type material creates a region that is "swapped", i.e the n-type has many holes and the p-type has many electrons, however this stops at a certain point because the positive>negative>positive>negative creates a voltage barrier that stops more electrons from moving across
- Connecting a voltage source to this junction where postiive flows to p-type and negative flows to n-type, the depletion region shrinks and its "resistance" is decreased allowing current to flow
- Connecting in reverse, the junction grows and decreases conductivity
- Biased Diode Junction Shockley Equation
  - $$I_D=I_S(e^{\frac{V_D}{nVT}}-1)$$
  - When V_D is very large, the exponential dominates and current increases rapidly
  - When V_D is negative, the -1 dominates and the current is practically zero
- Basically an exponential on either side (left down right up) when graphing current vs voltage, at negative voltage you're fine until the "breakdown" when current is now non-zero
- Zener diodes with an abrupt, HEAVILY doped p-n junction (<8V), making a voltage limited where after a certain reverse-bias voltage is applied, any extra voltage "flows through" due to current flow
  - these decrease breakdown voltage as temperature increases
- Zener diodes with a breakdown voltage above 8V will experience an avalanche breakdown, with the increase in temperature increasing breakdown voltage causing a chain reaction meltdown

## Interesting Technology
- ASML in Eindhoven produces silicon chips
- a machine fires 50000 drops of tin into a vacuum chamber every second and heats them to 220000C (hitting with a laser), 40x hotter than the sun. this excites the lowest energy of the atom, causing a massive energy drop, creates extreme ultraviolet light, controlled with mirrors smoother than a trillionth of a meter (picometer)
- this is like 10-125eV per photon, a wavelength of 10-121nm

- band structure doesn't work at single atom levels, and we're already around 20 atoms thick
