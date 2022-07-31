# Qiskit Global Summer School 2022: Quantum Chemistry and Simulation
#### Jul 18 2022 — Aug 04 2022


The Qiskit Global Summer School 2022 is a two-week intensive summer program designed to empower the quantum researchers and developers of tomorrow with the skills and know-how to explore the world of quantum computing and its applications. This third-annual summer school will provide a focused introduction to quantum computing and its applications to quantum simulation, with a specific focus on quantum chemistry.




## Lab 1: Introduction to circuit composition and cost
In the first Lab we will start slowly by giving an introduction to simple one qubit gates and show how they can be seen as rotations. We will then take a look at multi qubit gates and see some examples on how they can be used to create entangled states. After that we will apply the knowledge of complexity theory, which we learned in class, to quantum circuits. We will also take another look at the Quantum Fourier Transform as well as how to generate entangled states, with complexity theory in mind.

This lab is meant as an introduction / a repetition of the basics of quantum computation, as well as for introducing some examples of the concepts shown in the lecture to help you to learn them.

## Lab 2: Advanced circuits
The formalism of quantum information theory can look rather abstract compared to the circuit model of quantum computation. The Qiskit Opflow module aims to bridge the language of quantum information theory with the framework of circuits that is used to run experiments. This will make it seamless to switch back and forth between theoretical ideas and their experimental implementation.

One example that we'll see in some detail is the simulation of the time-evolution of quantum system. Using the Qiskit Opflow module going from the definition of the Hamiltonian governing the dynamics of the system to the experiment implementing a quantum simulation of the dynamics can be done in just a few lines of code!

## Lab 3: Quantum Noise
Noise is the omnipresent evil that corrupts our quantum computers. In this lab we will delve deeper in the details of the various kinds of noise affecting our computation to build a better understanding of them. We'll also look at some simple techniques we can use to fight the noise and recover the results we were looking for!

The different facets of the quantum noise that we'll encounter in this lab are: projection noise, measurement noise, coherent noise and incoherent noise. Projection noise is the noise caused by finite sampling of the wavefunction. Measurement noise is the noise affecting the physical measurement process, which is not perfect. Coherent noise is a type of noise, like over-rotation, which has a deterministic effect on our operations while incoherent noise is a non-deterministic noise which "scrambles" the quantum information in the quantum state.


# Lab 4: Simulate a Quantum Spin-1/2 Model
One of the leading uses for quantum computers will be to simulate quantum systems such as molecules or engineered materials. Actually executing a quantum simulation on a current quantum computer, however, can be difficult and error prone. Your objective for this lab is to complete the simulation exercises and then improve on them to get the highest state tomography score.
