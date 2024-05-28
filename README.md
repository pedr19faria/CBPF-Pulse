# CBPF-Pulse
The collection of notebooks are all studies on Qiskit-Pulse and Quantum control techquiniques, such as Composite Pulses and Dynamical Decoupling. Complete-Pulse notebook provides an introduction to Qiskit-Pulse with good examples and even a method to find the optimal amplitude for a $\pi$ pulse, using scipy. Calibration-and-T1T2-Pulse provides a notebook for finding the optimal frequency and amplitude for a $\pi$ pulse using a Rabi Experiment and uses this to find T1 and T2 in ibm_osaka, IBM Quantum Computer. T2 is done with Hahn Echoes, which is serves as an introduction to Dynamical Decoupling. In Composite-Pulses I investigate the use of composite pulses for errors is duration and amplitude, showing robustness against this errors. Also try to replicate the results for $\pi$ pulses with broad and narrowband pulses from Vitanov and Borosov article cited below. In Simulação-Rotação - a notebook written in Portuguese- I use rotation gates avaiable in qiskit to simulate composite pulses with errors in the angle of rotation. Furthermore, in the near future I hope to bring notebooks that better explore Dynamical Decoupling Routines, Quantum Error Correction and more about Composite Pulses.

---
This is all part of my research iniatiation program done at CBPF with Alexandre Martins de Souza. Funded by CNPQ.

---

Introduction to Qiskit Pulse.
[1] Alexander, T., Kanazawa, N., Egger, D. J., Capelluto, L., Wood, C. J., Javadi-Abhari, A., & McKay, D. C. (2020). Qiskit pulse: programming quantum computers through the cloud with pulses. Quantum Science and Technology, 5(4), 044006.

---

The ideias for the inital code were taken from this video:
Qiskit Pulse Tutorial | Sophy | CIT QH 2022 |Ms. Soyoung Shin. (2022, October 22).
Qiskit Pulse Tutorial — Sophy — CIT QH 2022 —
.https://www.youtube.com/watch?v=u2recVv7MLc&t=1206s

---

Liang, Z., Cheng, J., & Wang, H. (2023, November, 1). Enhance Variational Quantum Algorithms with Qiskit Pulse and Qiskit Dynamics. Medium. https://medium.com/qiskit/enhance-variational-quantum-algorithms-with-qiskit-pulse-and-qiskit-dynamics-768249daf8dd

---

IBM Quantum. 2023. IBM Quantum Documentation - Qiskit Pulse. Retrieved from https://docs.quantum.ibm.com/build/pulse

---
Qiskit. 2023. Calibrating Qubits: Pulse. Qiskit Textbook. Retrieved from https://qiskit.org/textbook/ch-quantum-hardware/calibrating-qubits-pulse.html

---
S. V. P. Whittall, N. M. Linke, N. Ares, G. J. Boyle, N. A. Kauffman, T. M. Hazard, A. L. Burin, M. G. Bason, "Dynamical decoupling for superconducting qubits: a performance survey", arXiv:2207.03670 [quant-ph]; Phys. Rev. Applied 20, 064027 (2022). DOI: 10.1103/PhysRevApplied.20.064027

---
Boyan T. Torosov e Nikolay V. Vitanov. “Experimental demonstration of composite pulses on
IBM’s quantum computer”. Em: (2022). arXiv: 2202.09647 [quant-ph].





