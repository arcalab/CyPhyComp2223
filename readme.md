<style>
td:empty {
  visibility: hidden;
}
th:empty {
  visibility: hidden;
}
</style>

# Introduction and objectives

Welcome to the webpage of the module "Cyber-Physical Computation",
edition 2021/2022.

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

  - __14 feb. 2023__ – Introduction to the module and its dynamics ([slides](slides/1-intro.pdf))
  - ...



<!--
| 16 Feb. 2023 | Introduction to the module and its dynamics ([slides/1-intro.pdf](slides))|
| 23 Feb. 2022 | Labelled transition systems and their role as semantics objects. The Calculus of Communicating Systems [file:transitionSystems.pdf]([)lides]) |
| 25 Feb. 2022 | The semantics of CCS [file:transitionSystems.pdf]([)lides]). Exercises.                                                                       |
| 02 Mar. 2022 | Observational Behaviour and Observational Equivalence  [file:transitionSystems.pdf]([)lides])                                                 |
| 04 Mar. 2022 | Continuation of the previous lecture. Exercises  [file:transitionSystems.pdf]([)lides])                                                       |
| 09 Mar. 2022 | Introduction to timed automata [file:timedAutomata/timed-automata.pdf]((lides).)]                                                                        |
| 11 Mar. 2022 | Continuation of the previous lecture. Exercises  [file:timedAutomata/timed-automata.pdf]((lides)]).                                                      |
| 16 Mar. 2022 | Observational equivalence for timed automata  [file:timedAutomata/timed-automata.pdf]((lides)]).                                                         |
| 18 Mar. 2022 | Introduction to Uppaal.                                                                                         |
| 23 Mar. 2022 | Extra features of Uppaal. The logic CTL and its application to the verification of Timed Systems [file:timed-automata2.pdf]((lides)]).      |
| 25 Mar. 2022 | Tackling the adventurers' problem with Uppaal [file:Adventurers/adventurers.pdf]((description o the problem)]).                                     |
| 30 Mar. 2022 | Continuation of the previous lecture.                                                                           |
| 06 Apr. 2022 | Recalling Haskell [file:lectureCPC.hs]((ile)]).                   -->                                                                     |


# Assessment

Assessment will consist of the following items:

+ Individual test (30%);
+ Group assignment: modelling and analysis of a cyber-physical system
  via [Uppaal]([http://www.uppaal.org/]) and via [Haskell]([https://www.haskell.org/]) (40%);
+ Two individual sets of exercises to do at home (15%+15%).


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
</p><hr><p><em>This file was generated by
<!-- <a href="http://www.lri.fr/~filliatr/bibtex2html/">bibtex2html</a> 1.99.</em></p> -->

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
</p><hr><p><em>This file was generated by
<!-- <a href="http://www.lri.fr/~filliatr/bibtex2html/">bibtex2html</a> 1.99.</em></p> -->

   
# Contact

The day and time for _appointments_ is Wednesday afternoon (but please
email us the day before if you wish to meet). If you prefer you
can also just send an email with your questions to [Renato Neves](mailto:nevrenato@di.uminho.pt) or to [José Proença](mailto:pro@isep.ipp.pt)
