# Photon Detection Simulation

This repository contains a simulation code developed to mimic the photon detection process using a photodetector. The simulation generates the output current response for each photon entry and plots the resulting current waveform over a 5 millisecond time interval. The simulation assumes a triangular current response for PD.

## Features

- Simulates photon detection process for photodetector PD.
- Generates random release times for electrons based on a quantum efficiency coefficient of 0.09.
- Plots the output current waveform for different received power levels.

## Results

The following figure shows the output current waveform for different received power levels in time domain.(assuming a triangular current response for PD)

![Output current waveform](/Publish/Q2_01.png)

---
The following figure shows the output current waveform for different received power levels in frequency domain(PSD).(assuming a triangular current response for PD)

![Output current waveform](/Publish/Q2_02.png)

---

The following figure shows the output current waveform for different received power levels in time domain.(assuming a rectangular current response for PD)

![Output current waveform](/Publish/Q2_03.png)

---

The following figure shows the output current waveform for different received power levels in frequency domain(PSD).(assuming a rectangular current response for PD)

![Output current waveform](/Publish/Q2_04.png)

---


