# Quantum T Gate

The Quantum T gate, also known as the π/8 gate, is a fundamental single-qubit gate that applies a phase shift of π/4 (45 degrees) to the |1⟩ computational basis state, while leaving the |0⟩ state unchanged. It is an essential gate for universal quantum computation as it introduces a non-Clifford phase, enabling operations beyond the Hadamard and Pauli gates.

This notebook demonstrates the effect of the T gate on the six canonical input states often used to characterize single-qubit gates:

- **|0⟩** (computational basis zero state)  
- **|1⟩** (computational basis one state)  
- **|+⟩ = (|0⟩ + |1⟩)/√2** (equal superposition state)  
- **|−⟩ = (|0⟩ − |1⟩)/√2** (superposition with phase)  
- **|i⟩ = (|0⟩ + i|1⟩)/√2** (imaginary phase superposition)  
- **|−i⟩ = (|0⟩ − i|1⟩)/√2** (imaginary phase superposition)  

---

## Contents

- **Matrix Representation**: The T gate matrix is

  \[
  T = \begin{bmatrix}
  1 & 0 \\
  0 & e^{i\pi/4}
  \end{bmatrix}
  \]

- **Input States**: Each input state vector is explicitly defined in the computational basis.

- **Gate Application**: The notebook applies the T gate matrix multiplication to each input state.

- **Output States**: The resulting vectors are shown, illustrating the phase shift applied only to the |1⟩ component.

- **Explanation**: Interpretation of how the π/4 phase affects each state, especially in the context of quantum interference and computation.

---

## Why It Matters

The T gate is crucial for implementing arbitrary single-qubit rotations and achieving universal quantum computing. Its non-Clifford nature makes it indispensable for error-correcting codes and advanced quantum algorithms.

---

## Usage

Run the notebook to observe how the T gate transforms different quantum states. This foundational understanding helps in building intuition about quantum phase gates and their roles in quantum circuits.
