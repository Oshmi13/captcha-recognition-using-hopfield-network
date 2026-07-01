# Hopfield Network From Scratch

A Python implementation of a **Hopfield Neural Network** built completely from scratch using NumPy. This project demonstrates how Hopfield Networks store and retrieve binary patterns, even when the input is noisy or incomplete.

---

## Overview

Hopfield Networks are recurrent neural networks that function as associative memory systems. They can memorize multiple binary patterns and recover the closest stored pattern from corrupted inputs.

This notebook implements the complete Hopfield Network without using any machine learning libraries.

---

## Features

- Hopfield Network implementation from scratch
- Random pattern generation
- Checkerboard and custom pattern creation
- Pattern visualization
- Pattern storage using Hebbian learning
- Pattern retrieval from noisy inputs
- Overlap calculation between stored and retrieved patterns
- Noise addition for testing memory robustness
- Visualization of network evolution

---

## Technologies Used

- Python
- NumPy
- Matplotlib

---

## Project Structure

```
.
├── Hopfield_Network_From_Scratch.ipynb
└── README.md
```

---

## How It Works

1. Generate binary patterns.
2. Train the Hopfield Network using Hebbian learning.
3. Corrupt one of the stored patterns.
4. Feed the noisy pattern into the network.
5. Observe how the network converges to the closest stored memory.

---

## Concepts Covered

- Recurrent Neural Networks
- Associative Memory
- Hebbian Learning
- Energy Minimization
- Pattern Completion
- Binary Image Storage
- Memory Retrieval

---

## Results

The network successfully:

- Stores multiple binary patterns
- Retrieves original patterns from noisy inputs
- Demonstrates convergence to stable states
- Visualizes overlap between stored and recovered patterns

---

## Future Improvements

- Asynchronous updates
- Energy function visualization
- Capacity analysis
- Larger datasets
- GUI for interactive pattern testing

---

## References

- Hopfield, J. J. (1982). Neural networks and physical systems with emergent collective computational abilities.
- https://neuronaldynamics.epfl.ch/online/Ch17.S2.html

---

## Author

**Oshmi Singh Sisodia**

