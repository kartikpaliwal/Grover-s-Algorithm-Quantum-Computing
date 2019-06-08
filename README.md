# Grover's-Algorithm-Quantum-Computing

Implementation of Grover’s algorithm by using amplitude amplification, and analysis of the performance of the algorithm.

The concept of the algorithm was initially not well defined in 1928.  Algorithms were performed using paper and pencil. For example, multiplication and division algorithms were long and used for huge numbers. In classical computing, the bit is the basic unit of information. The information can be broken down into patterns of 00s and 11s. They can be altered using binary operations.

Quantum computers are based on quantum bits. A quantum bit can have state 0 or 1 and it can be simultaneously in 0 and 1. The state of a quantum bit is represented in a vector form. It can be represented as |0> in Dirac notation. |0> and |1> are column vectors. Let say 0.4|0>+ 0.6|1> state is a superposition of |0> and |1> . This means it is a linear combination of two states |0> and |1>. Amplitude is the coefficient of a state which is in superposition. For example, 0.5 |0> + 0.8 |1> superposition state, amplitude for |0> is 0.5 and |1> is 0.8.

Computational complexity is measured based on execution time and space used for the scenario.  The number of basic operations is the measure for the execution time. In quantum computing, quantum circuit model consists of basic quantum gates which are operations. Quantum gates operate on quantum bits.

Grover’s algorithm is of order  O(√ n) evaluations in execution time. The algorithm gives a reasonable speed advantage for unstructured search. For example, searching for a number in a list in a normal search takes n/2 steps. Grover’s algorithm takes √ n steps.(FASTEST)

