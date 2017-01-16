## Purpose

To learn advanced functional programming techniques, specifically to:

- Know the motivation behind a particular technique or language feature.
- Learn how to use the technique or feature in practice.
- Understand how different techniques/features achieve the same goal. 

We will primarily concern us with languages such as: Haskell, Idris, Scala, OCaml, and Standard ML.

## Organization

- Each week will follow a 1 + 1 hour schedule, i.e. expect about one hour of *reading at home* followed by a *one hour discussion* at university.
- We will aim for light-weight reading material focused on practical usage.
- The format of each meeting will be Q & A with a walk-through of one or more of the examples.

## Schedule

#### Advanced Pattern Matching (Week 1)

- [Introduction to F# Active Patterns](https://blogs.msdn.microsoft.com/chrsmith/2008/02/21/introduction-to-f-active-patterns/) - Christian Smith, blog post.
- [Active Patterns in F#](https://docs.microsoft.com/en-us/dotnet/articles/fsharp/language-reference/active-patterns) - F# documentation.
- [The Neophyte's Guide to Scala Part 1: Extractors](http://danielwestheide.com/blog/2012/11/21/the-neophytes-guide-to-scala-part-1-extractors.html) - Daniel Westheide, blog post.
- [The Neophyte's Guide to Scala Part 2: Extracting Sequences](http://danielwestheide.com/blog/2012/11/28/the-neophytes-guide-to-scala-part-2-extracting-sequences.html) - Daniel Westheide, blog post.
- [24 Days of GHC Extensions: View Patterns](https://ocharles.org.uk/blog/posts/2014-12-02-view-patterns.html) - Oliver Charles, blog post.
- [24 Days of GHC Extensions: Pattern Synonyms](https://ocharles.org.uk/blog/posts/2014-12-03-pattern-synonyms.html)  - Oliver Charles, blog post.
- [View Patterns](https://downloads.haskell.org/~ghc/8.0.1/docs/html/users_guide/glasgow_exts.html#view-patterns) - Haskell documentation.
- [Pattern Synonyms](https://downloads.haskell.org/~ghc/8.0.1/docs/html/users_guide/glasgow_exts.html#pattern-synonyms) - Haskell documentation.

#### Modules, Signatures, and Functors (Week 2)

- [Modules in Standard ML](https://en.wikipedia.org/wiki/Standard_ML#Module_system) - Standard ML Module System, Wikipedia.
- [A Crash Course on ML Modules](http://jozefg.bitbucket.org/posts/2015-01-08-modules.html)
- [SML Modules](http://homepages.inf.ed.ac.uk/mfourman/teaching/mlCourse/notes/sml-modules.html)
- [OCaml Modules](https://ocaml.org/learn/tutorials/modules.html)

#### Generalized Algebraic Data Types 

- [Monad Reader](https://themonadreader.files.wordpress.com/2013/08/issue221.pdf)

#### Type Classes I

- [Theorems for Free](http://www.cs.sfu.ca/CourseCentral/831/burton/Notes/July14/free.pdf)
- [Learning ScalaZ](http://eed3si9n.com/learning-scalaz/index.html)
- [The Typeclassopedia](https://wiki.haskell.org/wikiupload/8/85/TMR-Issue13.pdf) - Brent Yorgey, the Monad Reader, Issue 13

#### Type Classes II

- [Towards ScalaZ (Part I)](http://typelevel.org/blog/2013/10/13/towards-scalaz-1.html)
- [Towards ScalaZ (Part II)](http://typelevel.org/blog/2013/12/15/towards-scalaz-2.html)
- [Introduction to Cats](http://underscore.io/blog/posts/2015/06/10/an-introduction-to-cats.html)
- [Shapeless 2.0 Feature Overview](https://github.com/milessabin/shapeless/wiki/Feature-overview:-shapeless-2.0.0)
- [The Type Astronauts Guide to Shapeless](https://github.com/underscoreio/shapeless-guide/blob/develop/dist/shapeless-guide.pdf)

#### Type Classes III

- [Profunctors in Haskell](http://blog.sigfpe.com/2011/07/profunctors-in-haskell.html) - Blog Post on Profunctors,
- [I love profunctors. They're so easy](https://www.schoolofhaskell.com/school/to-infinity-and-beyond/pick-of-the-week/profunctors) - Blog Post, School of Haskell
- [Rotten Bananas](http://comonad.com/reader/2008/rotten-bananas/) - Blog Post on Exponential Functors,
- [Why Free Monads Matter](http://www.haskellforall.com/2012/06/you-could-have-invented-free-monads.html) - Blog Post, Haskell
- [Free Monads are Simple](http://underscore.io/blog/posts/2015/04/14/free-monads-are-simple.html) - Blog Post, Scala
- [Free Monads, What and Why](https://softwaremill.com/free-monads/) - Blog Post, Scala
- [Understanding Free Monads](http://perevillega.com/understanding-free-monads) - Blog Post, Scala
- [Overview of the Free Monad](https://blog.scalac.io/2016/06/02/overview-of-free-monad-in-cats.html) - Blog Post, Scala

- exponential, profunctors, contravariant
- Free monads
- Functional Depedencies

#### Monad Transformers



#### Rank-N Types

- [Arbitrary Rank Polymorphism](https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/glasgow_exts.html#arbitrary-rank-polymorphism) - GHC Doc
- [24 Days of GHC Extensions: Rank N Types](https://ocharles.org.uk/blog/guest-posts/2014-12-18-rank-n-types.html)
- [Explaining Haskell RankNTypes for All](http://sleepomeno.github.io/blog/2014/02/12/Explaining-Haskell-RankNTypes-for-all/)
- [Higher-rank and higher-kinded types](https://www.stephanboyer.com/post/115/higher-rank-and-higher-kinded-types)

#### Lenses

- [Lens Tutorial](https://hackage.haskell.org/package/lens-tutorial-1.0.2/docs/Control-Lens-Tutorial.html) - Haskell
- [Optics for Scala](http://julien-truffaut.github.io/Monocle/)

#### Higher Kinded Types

- [What is a Higher-Kinded Type?](http://stackoverflow.com/questions/6246719/what-is-a-higher-kinded-type-in-scala) - StackOverflow
- [Scala: Types of a Higher Kind](http://blogs.atlassian.com/2013/09/scala-types-of-a-higher-kind/) - Atlassian
- [Generics of a Higher Kind](http://adriaanm.github.io/files/higher.pdf) - Adriaan Moors, Frank Piessens, and Martin Odersky.

#### Row Polymorphism

- [Row Polymorphism Isn't Subtyping](https://brianmckenna.org/blog/row_polymorphism_isnt_subtyping) - Blog Post
- [What are the Major Differences Between Row Polymorphism and Subtyping?](http://cs.stackexchange.com/questions/53998/what-are-the-major-differences-between-row-polymorphism-and-subtyping) - StackOverflow

#### Type Families

#### Codata/Corecursion/Comonad

#### Type Level Programming

- [Type-Level Instant Insanity](https://wiki.haskell.org/wikiupload/d/dd/TMR-Issue8.pdf) Conrad Parker, Monad Reader, Issue 8

#### Phantom Types

- [Phantom Type](https://wiki.haskell.org/Phantom_type) - Haskell Wiki
- [Phantom Types](https://en.wikibooks.org/wiki/Haskell/Phantom_types) WikiBooks
- [Motivation Behind Phantom Types](http://stackoverflow.com/questions/28247543/motivation-behind-phantom-types) - StackOverflow
- [Phantom Types in Scala](https://blog.codecentric.de/en/2016/02/phantom-types-scala/) - Blog Post
- [Using Phantom Types for Extra Safety](http://blog.jakubarnold.cz/2014/07/08/using-phantom-types-for-extra-safety.html) - Blog Post

#### Existential Types

#### Singleton Types

#### Continuations and Coroutines

- Control Monad
- Delimited Continuations

#### Higher-Order Abstract Syntax

- [Higher-Order Abstract Syntax](https://en.wikipedia.org/wiki/Higher-order_abstract_syntax) - Wikipedia
- [Higher-Order Abstract Syntax](http://www.cs.cmu.edu/afs/cs/Web/People/fp/papers/pldi88.pdf) - Frank Pfenning & Conal Elliott (PLDI '88)


#### Functional Reactive Programming

#### Arrows

- [Programming with Arrows](http://www.cse.chalmers.se/~rjmh/afp-arrows.pdf) - Research Paper, John Huges
- [Understanding Arrows](https://en.wikibooks.org/wiki/Haskell/Understanding_arrows) - Wikibooks
- [Arrow Tutorial](https://wiki.haskell.org/Arrow_tutorial) - Haskell Wiki
- [An Introduction to Arrows](http://blog.thecrossbowstore.com/2016/04/06/an-introduction-into-building-your-own-arrows/) - Blog Post

#### Unsorted

- [What, If Anything, Is A Declarative Language?](https://existentialtype.wordpress.com/2013/07/18/what-if-anything-is-a-declarative-language/)
- [Dynamic Languages are Static Languages](https://existentialtype.wordpress.com/2011/03/19/dynamic-languages-are-static-languages/)
- [Boolean Blindness](http://www.cs.yale.edu/homes/perlis-alan/quotes.html)
- [Epigrams in Programming](http://www.cs.yale.edu/homes/perlis-alan/quotes.html)
- [A Working Programmer’s Guide to Type-Indexed Values](https://blogs.janestreet.com/a-working-programmers-guide-to-type-indexed-values/) Blog Post, Jane Street.
- [Revisiting Tagless Final Interpreters with Dotty](https://gist.github.com/OlivierBlanvillain/48bb5c66dbb0557da50465809564ee80) - GitHub

## Topics to be covered at a later time...

#### Macros

- Quasiquotation

#### Implementation of Functional Languages

- Partial Evaluation
- Graph Reduction

#### Staging and Meta-Programming

- [Lightweight Modular Staging: A Pragmatic Approach to Runtime Code Generation and Compiled DSLs](https://infoscience.epfl.ch/record/150347/files/gpce63-rompf.pdf)
