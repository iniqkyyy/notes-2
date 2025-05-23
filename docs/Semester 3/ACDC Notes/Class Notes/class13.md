# ETEC 106 Lesson 13
- transformer is two inductors clsoe to eachother without being physically connected
- transformer inductance
  - $$L_M=k\sqrt{L_1L_2}$$
- ideal transformer drawn with source on left, load on right
  - whichever side has source attached is primary, load is secondary side
  - dot next to inductor means positive side of the inductor
- always use P for primary, S for secondary in all labels
- if dotted line between inductor means ferrite core
- if solid lines between inductor means iron core
- turns ratio
  - $$n=\frac{N_{sec}}{N_{pri}}$$
- if positive to positive then they are in-phase
- if positive to negative they are 180deg out of phase
- step-up or step-down transformer
  - $$V_{sec}=n*V_{pri}$$
  - can increase or decrease voltage
- isolation transformer
  - 1:1 turn ratio
  - can break a dc source while maintaining an ac source
- coupling transformer
  - if have ac and dc source, only have ac afterwards
- ideal transformer has primary power = secondary power
  - therefore voltage of primary vs voltage of secondary produces the same ratio as the turn ratio
  - same thing applies for current
  - $$n=\frac{N_{sec}}{N_{pri}}=\frac{V_{sec}}{V_{pri}}=\frac{I_{pri}}{I_{sec}}$$
- an output transformer has no impedance by itself (ignoring primary inductance/resistance)
  - $$\frac{R_{pri}}{R_{sec}}=\frac{1}{n^2}$$
  - therefore
  - $$R_{pri}=\frac{1}{n^2}R_L$$
- impedance matching
  - when internal resistance of source = R_pri then we get maximum power transfer
- non-ideal transformers
  - winding resistance loss
  - hysteresis loss (reversal of magnetic field)
  - core loss (eddy currents)
  - flux leakage (flux lost between left and right magnets)
  - winding capacitance (at high frequencies a capacitor is seen in an inductor)
- transformer efficiency
  - $$\eta=(\frac{P_{out}}{P_{in}})100\%$$
- tapped transformers
  - very common
  - literally a line in the middle of a 1:1 transformer that splits the voltage
- three phase transformers
  - three coils for a three phase source
  - transforms voltage for a three phase source, without damaging the initial phase
