# Experiments 11–20
Advanced Communication System and Design Laboratory (NEC_4203)

---

<details>
<summary>Experiment 11 - Sampling and Reconstruction</summary>

### Objective
To demonstrate signal sampling and reconstruction and verify the Nyquist sampling theorem.

### Introduction
Sampling converts a continuous-time analog signal into a discrete-time signal by measuring its amplitude at regular intervals. According to the Nyquist theorem, the sampling frequency must be at least twice the highest signal frequency to avoid aliasing. In this experiment, the signal is sampled and reconstructed using filtering techniques to observe how the original waveform can be recovered.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Function generator  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
No programming code was required. The configuration was implemented using telecom trainer modules.

### Results and Discussion
The signal was sampled at different frequencies. Proper sampling allowed accurate reconstruction of the original signal while undersampling produced distortion and aliasing effects.

### Reflection / Learning Summary
This experiment demonstrated how proper sampling frequency ensures accurate signal reconstruction in digital communication systems.

</details>

---

<details>
<summary>Experiment 12 - PCM Encoding</summary>

### Objective
To convert an analog signal into a digital PCM signal through sampling, quantization, and encoding.

### Introduction
Pulse Code Modulation (PCM) is a digital communication technique that converts analog signals into digital form. The process involves sampling the signal, quantizing the values, and encoding them into binary form. PCM is widely used in digital telephony and audio communication because it provides reliable signal transmission.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
PCM encoding was implemented using telecom trainer modules.

### Results and Discussion
The analog signal was sampled and converted into a digital binary sequence representing the quantized signal levels.

### Reflection / Learning Summary
The experiment demonstrated the process of converting analog information into digital data for reliable communication.

</details>

---

<details>
<summary>Experiment 13 - PCM Decoding</summary>

### Objective
To decode a PCM signal and reconstruct the original analog waveform.

### Introduction
PCM decoding converts a digital PCM signal back into an analog signal. The decoder interprets the binary codes, reconstructs the quantized levels, and applies filtering to smooth the signal. This process is essential in digital receivers to recover transmitted information.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
PCM decoding implemented using telecom trainer modules.

### Results and Discussion
The decoded signal closely resembled the original analog waveform after passing through the reconstruction filter.

### Reflection / Learning Summary
This experiment demonstrated how digital signals can be decoded and restored into their original analog form.

</details>

---

<details>
<summary>Experiment 14 - BW Limiting and Restoring Digital Signals</summary>

### Objective
To observe the effects of bandwidth limitation on digital signals and analyze signal restoration methods.

### Introduction
Bandwidth limitations in communication channels can distort digital signals by altering pulse shapes and causing intersymbol interference. This experiment demonstrates how limited bandwidth affects signal transmission and explores techniques used to restore distorted signals.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
No programming code required.

### Results and Discussion
Bandwidth limitation caused signal distortion and pulse spreading. Restoration techniques improved waveform clarity.

### Reflection / Learning Summary
The experiment emphasized the importance of adequate bandwidth in maintaining digital signal integrity.

</details>

---

<details>
<summary>Experiment 15 - Amplitude Shift Keying (ASK)</summary>

### Objective
To generate and analyze ASK modulated signals for digital communication.

### Introduction
Amplitude Shift Keying (ASK) is a digital modulation technique where the amplitude of a carrier signal changes according to binary data. A high amplitude represents binary “1” while a lower amplitude or absence of the carrier represents binary “0”. ASK is one of the simplest digital modulation schemes used in communication systems.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
ASK modulation implemented using telecom trainer modules.

### Results and Discussion
The carrier amplitude varied according to the digital input signal, representing binary information.

### Reflection / Learning Summary
This experiment demonstrated how digital information can be transmitted through amplitude variations of a carrier signal.

</details>

---

<details>
<summary>Experiment 16 - Frequency Shift Keying (FSK)</summary>

### Objective
To generate and observe FSK modulated signals representing binary data.

### Introduction
Frequency Shift Keying (FSK) is a digital modulation technique in which the carrier frequency changes according to the binary input signal. Two different frequencies represent binary “0” and binary “1”. FSK is widely used in communication systems due to its resistance to noise.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
Implemented using telecom trainer modules.

### Results and Discussion
The output waveform showed two distinct frequencies corresponding to the binary input signals.

### Reflection / Learning Summary
This experiment demonstrated how digital data can be transmitted using frequency variations of a carrier signal.

</details>

---

<details>
<summary>Experiment 17 - Binary Phase Shift Keying (BPSK)</summary>

### Objective
To generate and analyze BPSK modulated signals.

### Introduction
Binary Phase Shift Keying (BPSK) is a digital modulation technique where the phase of the carrier signal changes between two states to represent binary data. A phase shift of 0° typically represents binary “0”, while a 180° phase shift represents binary “1”. BPSK is widely used due to its reliability and strong noise immunity.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
BPSK implemented using telecom trainer modules.

### Results and Discussion
The carrier phase shifted according to the binary input signal producing two phase states.

### Reflection / Learning Summary
The experiment demonstrated how phase changes can represent digital information.

</details>

---

<details>
<summary>Experiment 18 - Quadrature Phase Shift Keying (QPSK)</summary>

### Objective
To generate and analyze QPSK signals for efficient digital transmission.

### Introduction
Quadrature Phase Shift Keying (QPSK) is an advanced digital modulation technique that transmits two bits per symbol by shifting the phase of the carrier signal among four different phase states. This improves bandwidth efficiency and data transmission rate compared to simpler modulation methods.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
QPSK implemented using telecom trainer modules.

### Results and Discussion
The output waveform displayed four phase states representing two-bit combinations.

### Reflection / Learning Summary
This experiment demonstrated improved data transmission efficiency using quadrature phase modulation.

</details>

---

<details>
<summary>Experiment 19 - DSSS Modulation and Demodulation</summary>

### Objective
To demonstrate Direct Sequence Spread Spectrum (DSSS) modulation and demodulation.

### Introduction
Direct Sequence Spread Spectrum (DSSS) spreads the signal over a wider bandwidth using a pseudo-random spreading code. This technique improves resistance to noise, interference, and signal interception. DSSS is used in modern wireless communication systems such as Wi-Fi and GPS.

### Materials and Components Used
- Emona Telecoms-Trainer 101  
- Oscilloscope  
- Patch cords  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
DSSS implemented using telecom trainer modules.

### Results and Discussion
The data signal was spread using a pseudo-random sequence and successfully recovered during demodulation.

### Reflection / Learning Summary
The experiment showed how spread spectrum techniques improve communication reliability.

</details>

---

<details>
<summary>Experiment 20 - Understanding Software Defined Radio</summary>

### Objective
To understand the concept and architecture of Software Defined Radio (SDR).

### Introduction
Software Defined Radio (SDR) is a communication system in which traditional hardware components such as modulators, demodulators, and filters are implemented using software. This allows flexible and reconfigurable communication systems capable of supporting multiple standards and applications.

### Materials and Components Used
- Computer system  
- SDR software platform  
- Communication modules  

### Circuit Diagram
<div align="center">
<img src="INSERT_DIAGRAM_HERE" width="500">
</div>

### Code
Software tools were used to configure communication system parameters.

### Results and Discussion
The SDR platform demonstrated how communication functions can be implemented and modified through software.

### Reflection / Learning Summary
This experiment introduced the concept of flexible radio systems that can be configured through software instead of fixed hardware.

</details>
