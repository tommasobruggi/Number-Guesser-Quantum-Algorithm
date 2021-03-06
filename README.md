# Number Guesser Quantum Algorithm

Quantum computing utilises three basic ingredients inherent to quantum mechanics: superposition, interference and entanglement. These phenomena allow for an enhanced performance of quantum algorithms, which translates to a speed-up compared to the best corresponding classical alternatives.

The  field  of  quantum  computing  attempts  to  follow  the  general  ideas  of  classical computing.   However,  rather  than  electric  currents  moving  bits  of  data  around,  in quantum  computing  the  quantum  mechanical  state  vector  is  evolved  and  the  goal of the subject is to extract the information contained in the state vector in  a  form  useful  for  computing  purposes.

Quantum  computers  could  spur  the  development  of  new  breakthroughs  in  science, medications  to  save  lives,  machine  learning  methods  to  diagnose  illnesses  sooner, materials  to  make  more  efficient  devices  and  structures,  financial  strategies  to  livewell  in  retirement,  and  algorithms  to  quickly  direct  resources  such  as  ambulances. A thorough understanding of quantum algorithms is crucial for the success of future quantum computers.


## Description

A simulation of a quantum computer was implemented on a classical computer using the Python programming language. All basic components of a quantum computer were created and the Bernstein-Vazirani quantum algorithm was implemented and successfully run using Qiskit, by IBM.

## Bernstein-Vazirani Algorithm

The Quantum Algorithm attempts to determine a secret string of ![equals1](http://latex.codecogs.com/svg.latex?1)s and ![equals1](http://latex.codecogs.com/svg.latex?0)s. 

This project transforms the string of ![equals1](http://latex.codecogs.com/svg.latex?1)s and ![equals1](http://latex.codecogs.com/svg.latex?0)s from a binary to a decimal number. The Bernstein-Vazirani algorithm is therefore used to determine a secret number ![real](http://latex.codecogs.com/svg.latex?n%20%5Cin%20%5Cmathbb%7BN%7D), rather than a string. This solves the famous game of "guess my number".

## Result

The Quantum Algorithm successfully guesses the input number in ![equals1](http://latex.codecogs.com/svg.latex?1) try. Because of the nature of the algorithm the accuracy is ![equals1](http://latex.codecogs.com/svg.latex?100)%. It therefore has time complexity ![real](http://latex.codecogs.com/svg.latex?O(1)) and provides a polynomial speedup with respect to the best classical alternative of ![real](http://latex.codecogs.com/svg.latex?O(N)), where ![real](http://latex.codecogs.com/svg.latex?N) is the number of bits. These results corroborate those by Vazirani et al in ![equals1](http://latex.codecogs.com/svg.latex?1992). 
