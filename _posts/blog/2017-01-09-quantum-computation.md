---
layout: post
title: Quantum Computing
modified:
categories: blog
excerpt:
tags: [Quantum Physics]
author : toshi_physics
comments: true
image:
  feature:
date: 2017-01-09T10:19:07+00:00
---
___The following article was written for and published by the annual newsletter of Dept. of Physics, IIT Bombay in collaboration with Insight, the student media body of IITB, in the Autumn semester of my freshmen year (2015). It is aimed at providing a brief info to the latest advancements in the field of quantum computing and what lies ahead.___

![Quantum Computation](http://www.doc.ic.ac.uk/~ids/dotdot/misc/images/dilbert-dt970322_295.gif)

### A New Hope

Our story begins with a team of researchers at The University of New South Wales(UNSW), Australia, led by Andrew Dzurak who have successfully 
accomplished the making of a two qubit logic gate in silicon, which is a crucial hurdle overcome in making quantum computers
a reality. “What we have is a game changer,” says team leader Prof. Dzurak.

“We’ve demonstrated a two qubit logic gate the central building block of a quantum computer and, significantly, done it in silicon. 
Because we use essentially the same device technology as existing computer chips, we believe it will be much easier to manufacture 
a fullscale processor chip than for any of the leading designs, which rely on more exotic technologies.”
The key idea behind the working of the UNSW team has been the morphing of normal transistors, into defining quantum bits or ‘qubits’, 
by ensuring that each transistor has a single electron associated with it, and representing the binary equivalent of numbers 0 and 1 
by spin of the electron.

The sentence makes sense quite ephemerally, so let's deconstruct the concept in lyman's language and restore freedom to our bound curiosity...

### The Very Begining

Essentially the concept of quantum computing involves use of quantum bits or ‘qubits’ instead of conventional bits in boolean algebra, 
that can be coupled in a scalable manner to make up one and two qubit logic gates. 
The numerous physical realisations of qubits, single photons, trapped ions, silicon and semiconductor quantum dots, 
single defects or atoms in diamond etc. have to be sufficiently fault tolerant and conserved under time evolution, 
with discrete and spaced eigenvalues that can be mapped onto an effective spin 1/2 system.

The ideation for representing qubits as the spin of an electron was primarily proposed in 1968, 
and sparked up with eminent physicist Richard Feynman proposing the possibility of a quantum computer in 1982.

### That which makes all the difference

The edge that a quantum system has over the conventional is the property of entanglement and superposition of states, 
i.e. a qubit’s existence is governed by superposition of the two basis states that denote conventional bits 0 and 1, 
mathematically, a linear combination.

![Bloch Sphere](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/Bloch_sphere.svg/237px-Bloch_sphere.svg.png)

The bloch sphere shown in the article, is a representation of a qubit with associated probability amplitudes, 
with the two basis states represented in standard Dirac notation (The braket notation). 
Thus considering two interacting qubits, four possible combinations yield, each weighed by a coefficient 
that denotes the probability of existence of the system in that state.
To specify a combination of two conventional bits, two information are coded, the value of both the bits, 
while for the quantum system four information, the four coefficients. 
Thus the information represented by an ‘n’ qubit system is exponentially large in comparison with its classical counterpart, 
the former is essentially two raised to the latter.

### But the world is not all cupcakes and rainbows

The state of superposition cascades down to one of its basis states on observation,
termed as the collapse of the governing Schrodinger wave function, essentially leading to us losing our data that boasted
of exponentially large capacities to normal bit sized information.
Thus, here lies the spinner, specific algorithms have to be applied to extract specific information out of a quantum system.
Many such brilliant minds have risen to the occasion, among them, notably and famed are Peter Shor (Shor’s Algorithm, 1994), 
Daniel Simon (Simon’s Algorithm, 1994) and Lov K. Grover (Grover’s Algorithm, 1996).

Let's take a look at what specific information can be extracted out - 

Shor’s algorithm is a quantum algorithm that addresses the problem of discrete logarithms and integer factorisation, 
a problem so intricate that our public key cryptography schemes like the RSA rely on the computational intractability 
in factoring large numbers for the most advanced classical computers.

Simon’s algorithm deals with the computational analysis of decision tree complexity and solves the problem exponentially 
faster than any known classical algorithm.

Grover’s algorithm addresses database search, i.e. given a unique output produced by a black box function 
(A function with unknown formulation but known mapping) it figures out the input with high probability, 
addressing the problem in quadratically fewer queries than classical.

Many more such algorithms exist, attacking with brute force, the issues that lie beyond the scope of classical computers.
Another problem is that many of the quantum algorithms give probabilistic solutions, solutions with probability very close to one, 
and which can be improved upon by repeated iterations but nevertheless its probabilistic. 
Many others however, are fully deterministic and hence efficacious.

The quantum computers can only respond to specific algorithms and tasks exponentially efficiently than classical, thus, 
they are not the substitute for them, but an aid, for more technological and advanced sector. 
Not every task that a normal personal computer does can be effectively performed with them.
So wish the genie to show you a movie, and quantum computer would be useless trash. Wish to crack security codes for all online credit
transfers, ye ol' quantum computer would watch the world burn as it decrypts transactions.

### Further, not-so-farther difficulties ahead

A big hurdle now is to remove decoherence from the system, isolating the system from the
surroundings, cutting down its interactions that make the system decohere, and to do so
economically and feasibly. Decoherence is irreversible and nonunitary and thus must be
controlled if not eradicated. Currently superconducting qubits can be configured to remove
setting in of significant decoherence in physically avoidable time lag, which typically ranges 
between the order of nanoseconds to seconds at low temperatures, by cooling the qubit to 20milli kelvin or lower temperatures.

Another problem that is now faced is to scale this system up to vast numbers of stable qubit registers or “q-registers”, 
quantum mechanical analogues of classical processor registers.

Unless a very efficient way is developed, optimum working is an impossibility.
In this direction, Prof. Dzurak notes that the team has “recently patented a design for full scale
quantum computer chip that would allow for millions of our qubits, all doing the same kind of calculations 
we’ve just experimentally demonstrated.”

The UNSW team’s research breakthrough has attacked three of the major requirements -  
1) qubits that can be initialised to arbitrary values, 
2) qubits with successful readout fidelities, 
3) a universal CNOT quantum gate, faster than the decoherence time of the system, 
with the fabrication process compatible with standard Complementary Metal Oxide Semiconductor (CMOS) technology that already exists
 for manufacturing classical Si based semiconductor chips.
Future experiments by this team will include improvements to facilitate full two qubit tomography. 
Improvement by lowering the sensitivity to electrical noise is also targeted. 
Though the two qubit system represents the smallest scalable system so far, it is consistent with current transistor sizes, offering the prospect of realizing a largescale
quantum processor using the same silicon manufacturing technologies that have enabled the current information age.

And lastly, on a more tender note,
“Computers are physical objects, and computations are physical processes.
What computers can or cannot compute is determined by the laws of physics alone.”
– David Deutsch

So we mustn’t lose faith. More breakthroughs are yet to arrive!
