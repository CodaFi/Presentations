# A Type System From Scratch: Swift Types in Context

## Functional Swift Conference, 2017

## Abstract

This presentation seeks to acquaint users of the Swift language - who interact
frequently with semantic analysis - about type inference and type checking in the
abstract.  It then continues on to describe concrete examples utilizing
"natural" versions of the classic typechecking algorithms M and W.  An emphasis 
is placed on plain English explanations and metaphors to decode jargon and 
notation.  The presentation concludes with a discussion of the challenges Swift 
faces with its own type system, and how we use techniques from constraint 
programming to tackle them.

## Discussion Questions

What about cascading failures of type inference?

What techniques can be used to speed up type inference in our programs?

Why not just implement one of the more expressive type theories on the cube and
lower Swift through it for typechecking purposes?

## External Links

- 3-SAT in Swift: https://gist.github.com/CodaFi/5add20c3d1fb23475e476fbdfa59a355
- Homework problems: https://gist.github.com/CodaFi/ca35a0c22fbd96eca505b5df45f2509e

- [Swift Documentation](https://github.com/apple/swift/tree/master/docs)
- [Type Inference in Context](http://www.cs.ru.nl/~james/RESEARCH/msfp2010-paper.pdf)
- [OutsideIn(X): Modular Type Inference with Local Assumptions](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/jfp-outsidein.pdf)
- [Associated Types with Class](http://simonmar.github.io/bib/papers/assoc.pdf)
- [Type Inference in the Presence of Overloading, Subtyping, and Recursive
Types](http://dl.acm.org/citation.cfm?id=141540)
- [Algorithmic Aspects of Type Inference with Subtypes](https://theory.stanford.edu/~jcm/papers/lincoln-mitch-92.pdf)
- "A Second Look at Overloading" (Odersky, Wadler, Wehr)
- [Constraint Satisfaction Problems](http://aima.cs.berkeley.edu/2nd-ed/newchap05.pdf)
- [Algebraic Subtyping](https://www.cl.cam.ac.uk/~sd601/thesis.pdf)
- [F-ing Modules](https://people.mpi-sws.org/~dreyer/courses/modules/f-ing.pdf)

