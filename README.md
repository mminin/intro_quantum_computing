# Introduction to quantum computing.

Many people are interested in quantum computing, but there are very few tutorials on the subject.
Tutorials that do exist are highly technical and esotheric, most people would not be able to understand them.
I'll be throwing my own notes into this repo while trying to stick to a language an amateur would understand.
The tutorial assumes highschool level of linear algebra and calculus; and basic programming skills in python.

## Terms and definitions.

### Fock space

TLDR; Fock space is an algebraic construct to model quantum states of many particals in n-dimensional space.
```
The Fock space is an algebraic construct of the quantum states space of several identical particles from a single particle Hilbert space. 
Hilbert space extends methods of vector algebra and calculus to a number of dimensions greater than 3. (According to Wiki)
```
### Bra-ket notation
Aka Dirac notation ```<f|v>```
https://en.wikipedia.org/wiki/Bra%E2%80%93ket_notation
Bra is ```<f|```, ket is ```|v>```

Ket ```|v>``` means vector. 
(There are some minor technical differeces between kets and vectors, but its similar enough to think of kets as simply vectors in n-dimensional space).

Here is a lecture from MIT on Bra-ket notation:
https://www.youtube.com/watch?v=r2NMWEsNcTs

## Basic concepts from MIT Quantum Physics course 1
(ref: https://ocw.mit.edu/courses/physics/8-04-quantum-physics-i-spring-2016/video-lectures/part-1/)

### Linear operator
Function L() is a linear operator if the following is true:

aL(x)=L(ax) and L(a+b)=aL+bL

POI: Quantum Mechanics is linear.

(From video L1.1 of aforementioned course)

