Aer Density-Matrix Noise Sandbox

 Simulate noisy quantum circuits in Qiskit Aer (method="density_matrix") with physics-faithful noise:
- Depolarizing (basis-agnostic mixing)
- Thermal relaxation (T₁/T₂) applied to physical gates (id/sx/x) and explicit delay(...) idles
- Optional 2-qubit noise on cx
Measure impact via purity (Tr ρ²), Bloch vector, and state fidelity. Includes parameter sweeps for idle time and CX duration.
