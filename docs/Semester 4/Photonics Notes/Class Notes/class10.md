# Photonics 1 Lesson 10
- all of these things are useful according to mark AND companies in area

## Spatial Coherence Length
- The spatial coherence of a beam is the "straightness" of rays in a cross section view
- speckle can be produced by interference from spatial non-coherence.
- 

## Temporal Coherence Length
- The coherence of the two rays in phase, how long will the rays "stay in phase" until they must be considered to be out of phase?
  - $$L_c=ct_c=\frac{c}{\Delta f}$$
  - length of coherence is related to the time of coherence times the speed of light

## Beam Diameter
- Many beams manifest a gaussian distribution (gaussian function = bell curve)
- 1/e% of the peak is one standard deviation, 1/e^2% of the peak is two standard deviations, and 1/e^3% of the peak is three standard deviations
- Plot beam intensity against distance
- #Beam-Diameter
  - We define the beam width as 2w, or between -1/e^2% and +1/e^2% intensity. 86% of beam energy is between these points.
  - $$2w=2\sigma=\frac{1}{e^2}*y_{peak}$$
- Put a circular aperture in front of the beam, plot % of light throughput against radius of aperture divided by w.
  - Resulting graph is non-linear as r reduces linearly.
- Width of beam is like an arc length
  - $$arc=r_{adius}\theta$$
  - $$w_n=(l_n\theta)+w_0$$
  - the MINIMUM divergeance is given as
  - $$\theta=\frac{w_2-w_i}{l_2-l_1}=\frac{2\lambda}{\pi w_0}$$
  - also cannot access the w0 because the laser's minimum width is usually inside the laser chamber

## Temporal Laser Outputs
- #Continuous-Wave-Laser
  - Outputs are analogous to DC.
- #Modulated-Laser 
  - Outputs are analogoous to AC.
- #Pulsed-Laser
  - For example if you had a power vs time graph you can turn it into geometric shapes and calculate the area under the curve (integrate).
  - PRT = pule repetition time
  - PRR = pule repetition rate (1/f)
  
## Beam Quality
- M^2 measurements.
- A value of 1-10 or higher, where 1 is "perfect".
- $$M^2=\frac{\pi \theta w_0}{2\lambda}$$
  - where theta is the actual divergeance angle (measured)
- It's like the characterization of how diffraction-limited the laser is, 1 means you are diverging only as much as diffraction forces you to do.
- the rest of beam quality metrics are typically less important and less used than M^2
- Beam profiling cameras can measure the actual 1/e^2 spot size
- Beam scanning techniques, looking at the beam scanning across a slit, pinhole, or knife edge
- Wavefront sensors detect "slope" and "direct phase"

## Power Stability 
- Usually given as a fraction of the average power or deviation of power after warmup.

## Efficiency
- just output / input
- showed cool graph in slides that showcased the % change in efficiency before and after beam optimization, went from 50% to 71%

## 
