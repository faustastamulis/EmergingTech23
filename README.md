# Emerging Technologies Assessment 2023
This is my Github Repository to the assessment that I must complete for the 2023 Emerging Technologies module. My name is Faustas Tamulis (G00373028@atu.ie).
I am a final year full-time student at ATU(Atlantic Technological University).
The topics covered in this assessment are as follows:
*  Qiskit
*  Deutsch Algorithm

## Qiskit
IBM created the open-source software framework known as Qiskit to allow people to interact with quantum computers. It is a complete toolkit for developing quantum computers that offers a variety of software, libraries, and programming tools for creating and running quantum algorithms.

Qiskit offers a high-level programming interface that enables users to communicate with quantum processors and simulators. Python, which is the primary language used for quantum programming in Qiskit, is one of the many programming languages it supports. This makes it available to a variety of users, both experienced quantum computer users and beginners.

Users may pick and choose from a variety of components to tailor the framework to their needs because it is intended to be modular. The four primary parts are as follows:

1. Qiskit Terra: This component provides the foundational building blocks for quantum programming. It includes tools for creating quantum circuits, manipulating quantum gates, and performing quantum operations.
    
2. Qiskit Aer: Aer is a high-performance simulator that allows users to simulate the behavior of quantum circuits on classical computers. It provides different types of simulators, including state vector simulators, unitary simulators, and noise simulators.

3. Qiskit Aqua: Aqua is a library within Qiskit that focuses on quantum applications beyond basic quantum circuits. It provides a collection of high-level quantum algorithms and tools for solving problems in optimization, chemistry, finance, and more.

4. Qiskit Ignis: Ignis is a module for characterizing and mitigating errors in quantum systems. It includes tools for calibrating quantum devices, measuring and mitigating noise, and benchmarking the performance of quantum systems.

IBM Quantum, the company's cloud-based quantum computing platform, is also accessible through Qiskit. The IBM Quantum Experience offers both simulators and actual quantum computers for users to execute their programmes on.

## Deutsch Algorithm
One of the first quantum algorithms, the Deutsch algorithm (also known as the Deutsch-Jozsa algorithm), shows how quantum computing may solve some problems exponentially more quickly than traditional computers.

The Deutsch function or Deutsch problem refers to the issue that the Deutsch algorithm attempts to solve. It entails figuring out if a particular function is constant or balanced; the former produces the same value for all inputs while the latter produces various values for half of the inputs and the same value for the rest.

In order to determine whether the provided function is balanced or constant, the traditional method of addressing the Deutsch issue calls for evaluating it twice. Even with big functions and plenty of inputs, this would hold true.

With just one function evaluation, the Deutsch approach, which uses a quantum computer, addresses the issue and provides a considerable speedup. Here's how it functions:

1. Initialization: The algorithm begins with two quantum registers, each consisting of one qubit. These qubits are prepared in the state |0⟩ (zero state) initially.

2. Superposition: A Hadamard gate (H gate) is applied to the first qubit, placing it in a superposition state. Now, the first qubit is in the state |+⟩, which is an equal superposition of |0⟩ and |1⟩.

3. Function Evaluation: The given function f(x) is applied to both qubits. In a quantum computer, this function can be represented by a quantum oracle. The oracle transforms the qubits based on the function's behavior, mapping inputs to outputs.

4. Second Hadamard Gate: Another Hadamard gate is applied to the first qubit.

5. Measurement: Finally, the algorithm measures both qubits. The measurement collapses the qubits into classical bits, and the result is observed.

6. Analysis: By analyzing the measurement results, the algorithm can determine whether the function is constant or balanced.

The Deutsch algorithm's basic concept is interference. Due to interference that happens during assessment as a result of the qubits' quantum nature, certain patterns of measurement outcomes ensue. The measurement results will show constructive interference, which will result in a certain pattern if the function is balanced. The measurement findings will exhibit destructive interference and produce a distinct pattern if the function is constant.

Without re-evaluating the function, it is feasible to tell if it is constant or balanced by looking at the measurement data.

## How to run the code
1. Download and install [Git](https://git-scm.com/downloads)
2. Download and install [Python](https://www.python.org/downloads/)
3. Download and install [Visual Studio Code](https://code.visualstudio.com/)
4. Download and install [Jupyter Notebook](https://jupyter.org/install)
5. Download and install [Qiskit](https://qiskit.org/documentation/install.html)
6. Open the command line and type in the following command to clone the repository:
```bash
git clone
```
7. Navigate to the folder where you cloned the repository and open it in Visual Studio Code.
8. Open the command line in Visual Studio Code and type in the following command to run the Jupyter Notebook:
```bash
jupyter notebook
```
9. Click on the Deutsch Algorithm.ipynb file to open it.
10. Click on the Run button to run the code.
11. The code will run and the results will be displayed.
12. Repeat for the Qiskit.ipynb file.

## References
* [Qiskit](https://qiskit.org/)
* [Deutsch Algorithm](https://www.ibm.com/blogs/research/2018/03/deutsch-algorithm-quantum-computing/)
* [Git](https://git-scm.com/)
* [Python](https://www.python.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Stack Overflow](https://stackoverflow.com/)
* [Jupyter Notebook](https://jupyter.org/)





