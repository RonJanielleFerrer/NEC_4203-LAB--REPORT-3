# NEC_4203-LAB--REPORT-3
This laboratory report for Advanced Communication System and Design Laboratory (NEC_4203) covers Experiments 11–20 on phase modulation, sampling, pulse modulation, digital encoding, and system integration. The activities reinforce advanced analog and digital communication system design principles.

# Experiment 11 – Phase Modulation (PM)

## Objective
The objective of this experiment is to generate and analyze a phase-modulated signal and understand how a message signal affects the phase of a carrier waveform.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
A phase modulation block was configured where the message signal controls the phase of a high-frequency carrier.

## Procedure / Experimental Setup
1. A carrier signal was generated.
2. A low-frequency message signal was applied to the phase control input.
3. The output waveform was observed using the oscilloscope.
4. Modulation index was adjusted and analyzed.

## Theory and Concepts
Phase modulation varies the phase angle of a carrier signal in proportion to the message amplitude. Unlike AM, the amplitude remains constant while phase changes encode information.

## Results and Observations
Waveform phase shifts were observed corresponding to message amplitude variations.

## Conclusion
The experiment successfully demonstrated phase modulation and its relationship to frequency modulation.

## Reflection / Learning Summary
I learned how phase variation carries information and how modulation index affects waveform behavior.

# Experiment 12 – Comparison of AM, FM, and PM

## Objective
The objective of this experiment is to compare amplitude, frequency, and phase modulation techniques in terms of waveform behavior and signal characteristics.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
Separate setups were created for AM, FM, and PM generation.

## Procedure / Experimental Setup
1. AM, FM, and PM signals were generated individually.
2. Waveforms were observed and compared.
3. Signal bandwidth and noise resistance characteristics were analyzed.

## Theory and Concepts
AM varies amplitude, FM varies frequency, and PM varies phase. Each technique offers different bandwidth requirements and noise performance.

## Results and Observations
FM and PM showed better noise immunity compared to AM.

## Conclusion
The experiment highlighted the advantages and limitations of each analog modulation technique.

## Reflection / Learning Summary
This comparison improved my understanding of when each modulation method is used in real communication systems.

# Experiment 13 – Sampling and Reconstruction

## Objective
The objective of this experiment is to understand signal sampling and verify the Nyquist sampling theorem.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
A sampler and low-pass filter were used to sample and reconstruct the message signal.

## Procedure / Experimental Setup
1. A sinusoidal signal was generated.
2. The signal was sampled at different sampling frequencies.
3. The sampled signal was passed through a reconstruction filter.
4. Outputs were observed and compared.

## Theory and Concepts
According to the Nyquist theorem, a signal must be sampled at least twice its highest frequency to avoid aliasing.

## Results and Observations
Undersampling caused aliasing, while proper sampling allowed accurate signal reconstruction.

## Conclusion
The experiment validated the Nyquist sampling theorem.

## Reflection / Learning Summary
I understood the importance of sampling frequency in digital communication systems.

# Experiment 14 – Pulse Amplitude Modulation (PAM)

## Objective
The objective of this experiment is to generate and analyze pulse amplitude modulated signals.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
A sampler block was used to produce PAM signals.

## Procedure / Experimental Setup
1. A message signal was applied to the sampler.
2. Sampling pulses were generated.
3. PAM output was observed on the oscilloscope.

## Theory and Concepts
In PAM, the amplitude of each pulse corresponds to the instantaneous value of the message signal.

## Results and Observations
The pulse heights matched the message signal amplitude at sampling instances.

## Conclusion
The experiment successfully demonstrated PAM signal generation.

## Reflection / Learning Summary
I learned how analog signals are converted into pulse-based representations.

# Experiment 15 – Pulse Width Modulation (PWM)

## Objective
The objective of this experiment is to generate and observe pulse width modulated signals.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
A comparator and ramp signal were used to produce PWM signals.

## Procedure / Experimental Setup
1. A message signal and ramp waveform were applied.
2. PWM output was generated.
3. Pulse width variations were observed.

## Theory and Concepts
In PWM, the width of pulses varies according to the message signal amplitude while amplitude remains constant.

## Results and Observations
Pulse width increased and decreased in proportion to the message signal.

## Conclusion
The experiment demonstrated PWM signal characteristics.

## Reflection / Learning Summary
This experiment showed how information can be encoded through time variation instead of amplitude.

# Experiment 16 – Pulse Position Modulation (PPM)

## Objective
The objective of this experiment is to generate pulse position modulated signals.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
PWM signals were converted into PPM signals.

## Procedure / Experimental Setup
1. A PWM signal was generated.
2. The PWM output was converted to PPM.
3. Pulse position shifts were observed.

## Theory and Concepts
In PPM, pulse timing varies according to the message signal amplitude.

## Results and Observations
Pulse positions shifted left and right depending on signal level.

## Conclusion
PPM encoding was successfully demonstrated.

## Reflection / Learning Summary
I learned how pulse timing can represent information efficiently.

# Experiment 17 – Pulse Code Modulation (PCM)

## Objective
The objective of this experiment is to understand and generate pulse code modulated signals.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
A sampler, quantizer, and encoder were used.

## Procedure / Experimental Setup
1. The signal was sampled.
2. The sampled signal was quantized.
3. Binary encoding was observed.

## Theory and Concepts
PCM converts analog signals into binary digital form through sampling, quantization, and encoding.

## Results and Observations
Digital bit streams corresponded to quantized signal levels.

## Conclusion
PCM conversion was successfully demonstrated.

## Reflection / Learning Summary
I gained understanding of how analog signals are converted into digital data.

# Experiment 18 – Line Coding Techniques

## Objective
The objective of this experiment is to study different line coding methods for digital transmission.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
Various line coding schemes were configured.

## Procedure / Experimental Setup
1. Digital bit streams were generated.
2. Different encoding schemes were applied.
3. Waveforms were compared.

## Theory and Concepts
Line coding techniques such as NRZ and Manchester coding affect bandwidth and synchronization.

## Results and Observations
Different coding schemes showed distinct waveform characteristics.

## Conclusion
The experiment demonstrated how encoding affects signal transmission.

## Reflection / Learning Summary
I learned the importance of choosing proper line coding for reliable communication.

# Experiment 19 – ASK and FSK Modulation

## Objective
The objective of this experiment is to generate and analyze amplitude shift keying and frequency shift keying signals.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
Digital input controlled carrier amplitude and frequency.

## Procedure / Experimental Setup
1. Binary data was generated.
2. ASK and FSK modulation circuits were configured.
3. Outputs were observed.

## Theory and Concepts
ASK varies amplitude, while FSK varies frequency to represent binary data.

## Results and Observations
Distinct waveform changes represented digital bits.

## Conclusion
Digital modulation techniques were successfully demonstrated.

## Reflection / Learning Summary
I understood how digital information is transmitted using carrier modulation.

# Experiment 20 – Digital Communication System Integration

## Objective
The objective of this experiment is to integrate digital modulation, transmission, and demodulation into a complete communication system.

## Materials and Components Used
- Emona Telecoms-Trainer 101
- Oscilloscope
- Patch leads

## Circuit / Block Diagram
A full transmitter-receiver chain was assembled.

## Procedure / Experimental Setup
1. Digital data was generated.
2. Modulation was applied.
3. Signal was transmitted and demodulated.
4. Output was verified.

## Theory and Concepts
A complete communication system consists of a transmitter, channel, and receiver working together to transfer information reliably.

## Results and Observations
Recovered digital signals matched transmitted data.

## Conclusion
The integrated system functioned successfully.

## Reflection / Learning Summary
This final experiment connected all previous concepts into one complete communication system.
