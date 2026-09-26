# Experiment 3
# SSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** The baseband signal that will be modulated.
* **Carrier Signal:** A high-frequency signal used for modulation.
* **Analytic Signal:** Constructed using the Hilbert transform to get the in-phase and quadrature components.

### 3. SSBSC Modulation:

* **Modulated Signal:** Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

### 4. SSBSC Demodulation:

* **Mixing:** Multiply the SSBSC signal with the carrier to retrieve the message signal.
* **Low-pass Filtering:** Apply a low-pass filter to remove high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION
<img width="960" height="1280" alt="WhatsApp Image 2026-09-26 at 9 48 00 AM" src="https://github.com/user-attachments/assets/27c0ed34-bada-4f42-982e-bd8f5d633ca2" />




---


## output 
<img width="1071" height="634" alt="image" src="https://github.com/user-attachments/assets/1233d9fc-7833-45cf-96e5-0bae79cde9b5" />

## Results 
<img width="1280" height="497" alt="WhatsApp Image 2026-09-26 at 11 58 17 AM" src="https://github.com/user-attachments/assets/69db12df-44d8-4024-95d9-b773311ff53f" />

 Successfully performed SSBSC modulation and demodulation using SCI LAB
