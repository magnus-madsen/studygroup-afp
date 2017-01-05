## Purpose

To learn about advanced functional programming techniques, specifically to

- Understand the motivation for each technique/language feature.
- Learn how and when to use that technique/feature.
- Compare and contrast different techniques.
- Gain practical (i.e. conding) experience with each technique.

In particular, we will look into features from languages such as: Haskell, Idris, Scala, Racket, OCaml, Standard ML, etc. The content *is* biased towards Haskell, but our goal is to go beyond that when possible.

## Organization

Each week will cover one topic with approximately one hour of reading material before the one hour meeting.
The format of each meeting will be a questions-and-answers along with a walkthrough of one or more examples on the projector by the person responsible for the particular topic.

## Schedule

### Modules, Signatures, and Functors

- [Modules iN Standard ML](https://en.wikipedia.org/wiki/Standard_ML#Module_system) - Wikipedia
- [A Crash Course on ML Modules](http://jozefg.bitbucket.org/posts/2015-01-08-modules.html)
- [SML Modules](http://homepages.inf.ed.ac.uk/mfourman/teaching/mlCourse/notes/sml-modules.html)
- [OCaml Modules](https://ocaml.org/learn/tutorials/modules.html)

### Week 1: Type Classes

- Type Classes, Functional Depedencies
- [Learning ScalaZ](http://eed3si9n.com/learning-scalaz/index.html)
- [Towards ScalaZ (Part I)](http://typelevel.org/blog/2013/10/13/towards-scalaz-1.html)
- [Towards ScalaZ (Part II)](http://typelevel.org/blog/2013/12/15/towards-scalaz-2.html)
- [Introduction to Cats](http://underscore.io/blog/posts/2015/06/10/an-introduction-to-cats.html)
- [The Type Astronauts Guide to Shapeless](https://github.com/underscoreio/shapeless-guide/blob/develop/dist/shapeless-guide.pdf)
- [Shapeless 2.0 Feature Overview](https://github.com/milessabin/shapeless/wiki/Feature-overview:-shapeless-2.0.0)
- [Theorems for Free](http://www.cs.sfu.ca/CourseCentral/831/burton/Notes/July14/free.pdf)

### Week 2: Monad Transformers

### Week 3: Advanced Functors

- exponential, profunctors, contravariant

### Week 3: Generalized Algebraic Data Types 

### Week x: Functional Reactive Prorgamming

### Week x: Arrows

- [Programming with Arrows](http://www.cse.chalmers.se/~rjmh/afp-arrows.pdf) - John Huges
- [Understanding Arrows](https://en.wikibooks.org/wiki/Haskell/Understanding_arrows) - WikiBooks
- [Arrow Tutorial](https://wiki.haskell.org/Arrow_tutorial) - Haskell Wiki
- [An Introduction to Arrows](http://blog.thecrossbowstore.com/2016/04/06/an-introduction-into-building-your-own-arrows/)

### Week x: Continuations

- Control Monad
- Delimited Continuations

### Week x: Macros

- Quasiquotation

### Week x: Rank-N Types

- [Arbitrary Rank Polymorphism](https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/glasgow_exts.html#arbitrary-rank-polymorphism) - GHC Doc
- [24 Days of GHC Extensions: Rank N Types](https://ocharles.org.uk/blog/guest-posts/2014-12-18-rank-n-types.html)
- [Explaining Haskell RankNTypes for All](http://sleepomeno.github.io/blog/2014/02/12/Explaining-Haskell-RankNTypes-for-all/)
- [Higher-rank and higher-kinded types](https://www.stephanboyer.com/post/115/higher-rank-and-higher-kinded-types)

### Week x: Misc

- [What, If Anything, Is A Declarative Language?](https://existentialtype.wordpress.com/2013/07/18/what-if-anything-is-a-declarative-language/)
- [Dynamic Languages are Static Languages](https://existentialtype.wordpress.com/2011/03/19/dynamic-languages-are-static-languages/)
- [Boolean Blindness](http://www.cs.yale.edu/homes/perlis-alan/quotes.html)
- [Epigrams in Programming](http://www.cs.yale.edu/homes/perlis-alan/quotes.html)

### Week x: Lenses

- [Lens Tutorial](https://hackage.haskell.org/package/lens-tutorial-1.0.2/docs/Control-Lens-Tutorial.html) - Haskell
- [Optics for Scala](http://julien-truffaut.github.io/Monocle/)

### Higher-Order Abstract Syntax

- [Higher-Order Abstract Syntax](https://en.wikipedia.org/wiki/Higher-order_abstract_syntax) - Wikipedia
- [Higher-Order Abstract Syntax](http://www.cs.cmu.edu/afs/cs/Web/People/fp/papers/pldi88.pdf) - Frank Pfenning & Conal Elliott (PLDI '88)

### Higher Kinded Types

- [What is a Higher-Kinded Type?](http://stackoverflow.com/questions/6246719/what-is-a-higher-kinded-type-in-scala) - StackOverflow
- [Scala: Types of a Higher Kind](http://blogs.atlassian.com/2013/09/scala-types-of-a-higher-kind/) - Atlassian
- [Generics of a Higher Kind](http://adriaanm.github.io/files/higher.pdf) - Adriaan Moors, Frank Piessens, and Martin Odersky.

### Staging and Meta-Programming

- [Lightweight Modular Staging: A Pragmatic Approach to Runtime Code Generation and Compiled DSLs](https://infoscience.epfl.ch/record/150347/files/gpce63-rompf.pdf)

### Row Polymorphism

- [Row Polymorphism Isn't Subtyping](https://brianmckenna.org/blog/row_polymorphism_isnt_subtyping) - Blog Post
- [What are the Major Differences Between Row Polymorphism and Subtyping?](http://cs.stackexchange.com/questions/53998/what-are-the-major-differences-between-row-polymorphism-and-subtyping) - StackOverflow

### Implementation of Functional Languages

- Partial Evaluation
- Finally Tagless
- Graph Reduction

### To be sorted.

Existential Types
Codata/Corecursion/Comonad
Type Families
Generic Programming
Type Level programming
Singleton Types
macros
Free monads, extensisble effects
Phantom types
Type-indexed values
