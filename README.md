# transmon-PPQ-system-data

This repository contains raw data of _Construction of New Type of CNOT Gate Using Cross-resonance Pulse in the Transmon-PPQ System_.

# $\mathrm{CNOT}_\mathrm{TP}$

```CNOT_TP.zip``` contains a ```.mat``` file, ```CNOT_TP.mat```.
In ```CNOT_TP.mat```, ```CNOT``` is the time evolution operator $\mathrm{CNOT}_\mathrm{TP}$.
The file includes pulse parameters (```pulseParam```) and gate fidelity (```F```) of CNOT before optimization.
It also has gate success probabilities (e.g. ```Prob00```) and trajectories of Bloch vectors (e.g. ```r_0_t```) during the CNOT operation.

The optimized parameters and gate error rate is in ```CNOT_TP_optParams.mat```.

# Single-qubit gates (Supplementary Materials)

```xpih_t.mat``` and ```xpih_p.mat``` have same structure of ```CNOT_TP.mat```.
