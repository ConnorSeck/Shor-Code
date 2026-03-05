##Shor Code Implementation

This repository contains an implementation of the Shor Code, a 9-qubit quantum error-correcting code capable of correcting both bit-flip and phase-flip errors. The project demonstrates how logical quantum information can be protected against decoherence using quantum redundancy and syndrome measurements.

The implementation is built using Python and the Qiskit quantum computing framework.

##Overview

Quantum information is extremely fragile due to noise and decoherence. Classical error correction cannot be directly applied because of the no-cloning theorem and the destructive nature of measurement.

The Shor Code, introduced by Peter Shor in 1995, was the first quantum error correction scheme capable of protecting against arbitrary single-qubit errors.

It works by combining:

Bit-flip repetition code

Phase-flip repetition code

to encode 1 logical qubit into 9 physical qubits.

##Features

Implementation of 9-qubit Shor encoding circuit

Simulation of bit-flip errors

Simulation of phase-flip errors

Syndrome measurement

Error correction verification

End-to-end simulation of logical qubit protection
