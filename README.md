# qiskit-fast-shor

A faster implementation of Shor's algorithm from Qiskit. It achieves significant speedups (upwards of 20x: 126 seconds vs. 5.9 seconds on N=15) over the implementation bundled in Qiskit Aqua by avoiding conversions from and to QuantumCircuit when composing.