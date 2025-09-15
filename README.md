# Over-Complicated Distortion (OCD)

This is a highly tweakable distortion pedal based around soft-clipping diodes in feedback.

## Controls
1. **Drive:** Adds gain to push the diodes into their non-linear region.
2. **Filter:** Crossmixes between Lowpass Filter and Highpass Filter. The 2nd-order Salley-key filter occurs before the clipping stage.
3. **Bias:** Adds a DC shift to the signal prior to the clipping stage. This can be used for asymmetric clipping as would occur in many tube and transistor Class-A amplifiers if they exceed their linear range.
4. **Symmetry:** Blends betweent the forward and reverse steering diodes in the feedback path. At higher gain values, the asymmetry will be diminished as the second set of (symmetric) clipping diodes is mixed in. This is done to achieve more extreme waveshaping than is possible with the resistance from the potentiometer limitng the steering current.
5. **Attenuvert:** This acts as an ouput control that affects only the clipped signal. In the CCW direction, the signal inverts.
6. **Mix:** Mixes between the dry and wet (distorted) signals. High distortion settings with low mix can simulate the crossover distortion produced by a Class B push-pull amplifier. Reversing the polarity results in a different flavor of crossover distortion.


Despite the name, this circuit has no association or deliberate simularities with other *OCD* distortion pedals.
