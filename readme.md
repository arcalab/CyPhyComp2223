# Introduction and objectives

Welcome to the webpage of the module "Cyber-Physical Computation",
edition 2022/2023.

Cyber-physical systems are networks of computational devices that
closely interact with physical processes in order to reach a
prescribed goal; for example a desired velocity, a desired temperature
or, more generally, a desired energy level. They range from small
medical devices, such as pacemakers and insulin pumps, to networks of
autonomous vehicles and district-wide smart grids. This module is
devoted to such systems.

The main learning goal is two-fold: 1) to prepare the student to a
*disciplined* way of developing and analysing cyber-physical systems,
by presenting their *basic principles*, adequate *models of
computation*, and respective *tools*; 2) and to introduce the student
to the main limitations of the area's state-of-the-art 
-- via pedagogical illustrations extracted from real world-scenarios
involving e.g. cruise controllers, sampling algorithms, and timed
variants of concurrent algorithms.

At the end of the module, the student will:

+ know the basic principles and representative models of
  cyber-physical computation;
+ have a broad knowledge of languages, tools, and techniques for
  engineering cyber-physical systems;
+ be proficient with the tools [Uppaal]([http://www.uppaal.org/]) and [Lince]([http://arcatools.org/assets/index.html#arcatools]), which cover model
  checking, testing, and simulation for cyber-physical systems;
+ be able to understand in which ways the state-of-the-art (of
  cyber-physical computation and engineering) is limited, and 
  the potential outcomes of solving these limitations.

# Syllabus

+ Labelled transition systems, their role as semantic objects, and
  corresponding notions of equivalence;
+ Timed labelled transition systems and corresponding notions of
  equivalence, composition, and synchronisation. Zeno behaviour;
+ From theory to practice: the tool [Uppaal]([http://www.uppaal.org/]);
+ A while-language and its operational semantics;
+ A hybrid while-language and its operational semantics;
+ From theory to practice: the tool [Lince]([http://arcatools.org/assets/index.html#arcatools]);
+ Cyber-physical behaviour as yet another computational effect: the
  notion of a monad, the hybrid monad, and monad combination.
  
# Summaries

  - __14 feb. 2023__ – Introduction to the module and its dynamics ([slides-1](slides/1-intro.pdf))
  - __21 feb. 2023__ - Formalising and reasoning over labelled transition systems ([slides-2](slides/2-behaviour.pdf))
  - __28 feb. 2023__ - Equivalence of labelled transition systems ([slides-2](slides/2-behaviour.pdf))
  - __3 mar. 2023__ - Exercises on equivalences; Introduction to Timed automata ([slides-3](slides/3-timed-automata.pdf))
  - __14 mar. 2023__ - Formalisation of Timed Automata (TA) and its composition ([slides-3](slides/3-timed-automata.pdf))
  - __17 mar. 2023__ - Exercises on the composition of TA; Semantics TA ([slides-3](slides/3-timed-automata.pdf))
  - __21 mar. 2023__ - Semantics and equivalence of Timed automata ([slides-3](slides/3-timed-automata.pdf))
  - __24 mar. 2023__ - Introduction to UPPAAL model checker ([slides-4](slides/4-verification-uppaal.pdf))
  - __28 mar. 2023__ - Modelling in Uppaal and introduction to CTL ([slides-4](slides/4-verification-uppaal.pdf))
  - __31 mar. 2023__ - Verification using CTL in UPPAAL ([slides-4](slides/4-verification-uppaal.pdf))
  - __31 mar. 2023__ - Compensation lecture: modelling adventurers on a bridge ([Instructions](adventurers/adventurers.pdf)) ([My solution](adventurers/adventurers.xml))
  - __11 apr. 2023__ - Operational semantics of simple languages. Recalling Haskell ([Slides](slides/hybridProgramming.pdf)) ([Code](slides/lectureCPC.hs))
  - __14 apr. 2023__ - Implementations of different semantics in
 Haskell ([Code](code.zip))
  - __18 apr. 2023__ - Introduction to hybrid semantics ([Slides](slides/hybridProgramming.pdf))
  - __28 apr. 2023__ - A zoo of hybrid programs ([Slides](slides/hybridProgramming.pdf))
  - __02 may  2023__ - A brief overview of simply-typed lambda-calculus ([Slides](slides/Monads/lambdaCalc.pdf))
  - __05 may  2023__ - Continuation of the previous lecture ([Slides](slides/Monads/lambdaCalc.pdf))
  - __16 may  2023__ - lambda-calculus and algebraic operations ([Slides](slides/Monads/stlcE.pdf))
  - __19 may  2023__ - Written assessment.
  - __23 may  2023__ - Working with monads ([Code](slides/Monads/code.zip))
# Assessment

Assessment consist of the following items:

+ Two individual sets of exercises to do at home. 
  * [TPC1 (15%)](assignments/tpc1-cpc.pdf)
  * [TPC2 (15%)](assignments/tpc2-cpc.pdf) 
+ Individual test (30% - 19th May);
+ [Group assignment](tp.pdf) (40% - 26th June);
  


# Bibliography

<p><a name="alur1994theory"></a>
Rajeev Alur and David&nbsp;L Dill.
 A theory of timed automata.
 <em>Theoretical computer science</em>, 126(2):183--235, 1994.
[&nbsp;<a href="bib/biblioCPC_bib.html#alur1994theory">bib</a>&nbsp;]
</p>

<p><a name="henzinger2000theory"></a>
Thomas&nbsp;A Henzinger.
 The theory of hybrid automata.
 In <em>Verification of digital and hybrid systems</em>, pages 265--292.
  Springer, 2000.
[&nbsp;<a href="bib/biblioCPC_bib.html#henzinger2000theory">bib</a>&nbsp;]
</p>

<p><a name="winskel1993formal"></a>
Glynn Winskel.
 <em>The formal semantics of programming languages: an introduction</em>.
 MIT press, 1993.
[&nbsp;<a href="bib/biblioCPC_bib.html#winskel1993formal">bib</a>&nbsp;]
</p>

<p><a name="goncharov2020implementing"></a>
Sergey Goncharov, Renato Neves, and Jos&eacute; Proen&ccedil;a.
 Implementing hybrid semantics: From functional to imperative.
 In <em>International Colloquium on Theoretical Aspects of
  Computing</em>, pages 262--282. Springer, 2020.
[&nbsp;<a href="bib/biblioCPC_bib.html#goncharov2020implementing">bib</a>&nbsp;]
</p>

<p><a name="lipovaca2011learn"></a>
Miran Lipovaca.
 <em>Learn you a haskell for great good!: a beginner's guide</em>.
 no starch press, 2011.
[&nbsp;<a href="bib/biblioCPC_bib.html#lipovaca2011learn">bib</a>&nbsp;]
</p>

<p><a name="wadler1995monads"></a>
Philip Wadler.
 Monads for functional programming.
 In <em>International School on Advanced Functional Programming</em>,
  pages 24--52. Springer, 1995.
[&nbsp;<a href="bib/biblioCPC_bib.html#wadler1995monads">bib</a>&nbsp;]
</p>
<!-- 
<hr><p><em>This file was generated by
<a href="http://www.lri.fr/~filliatr/bibtex2html/">bibtex2html</a> 1.99.</em></p> -->

## Supplementary bibliography

<p><a name="jacobs2017introduction"></a>
Bart Jacobs.
 <em>Introduction to coalgebra</em>, volume&nbsp;59.
 Cambridge University Press, 2017.
[&nbsp;<a href="bib/sup_bib.html#jacobs2017introduction">bib</a>&nbsp;]
</p>

<p><a name="ellison2012executable"></a>
Chucky Ellison and Grigore Rosu.
 An executable formal semantics of c with applications.
 <em>ACM SIGPLAN Notices</em>, 47(1):533--544, 2012.
[&nbsp;<a href="bib/sup_bib.html#ellison2012executable">bib</a>&nbsp;]
</p>
<!-- 
<hr><p><em>This file was generated by
 <a href="http://www.lri.fr/~filliatr/bibtex2html/">bibtex2html</a> 1.99.</em></p> -->

   

# Contact

The day and time for _appointments_ is Wednesday afternoon (Renato Neves) or Thursday morning (José Proença). Please
email us the day before if you wish to meet. If you prefer you
can also just send an email with your questions to [Renato Neves](mailto:nevrenato@di.uminho.pt) or to [José Proença](mailto:pro@isep.ipp.pt), or we can try to book an online meeting.
