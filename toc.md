---
layout: default
title : Introduction to Univalent Foundations of Mathematics with Agda
date : 2019-03-04
---
## <a name="lecturenotes">Introduction to Univalent Foundations of Mathematics with Agda</a>

### <a name="contents"></a> Table of contents

  1. [Front matter](index.html#lecturenotes)
     1. [Lecture Notes in Univalent mathematics with Agda](index.html#lecturenotes)
     1. [Introduction](index.html#introduction)
     1. [Homotopy type theory](index.html#homotopytypetheory)
     1. [General references](index.html#generalreferences)
     1. [Choice of material](index.html#plan)
  1. [MLTT in Agda](MLTT-Agda.html)
     1. [A spartan Martin-Löf type theory (MLTT)](MLTT-Agda.html#spartanmltt)
     1. [What is Agda?](MLTT-Agda.html#whatisagda)
     1. [Getting started with Agda](MLTT-Agda.html#gettingstartedagda)
     1. [Universes `𝓤,𝓥,𝓦`](MLTT-Agda.html#universes)
     1. [The one-element type `𝟙`](MLTT-Agda.html#onepointtype)
     1. [The empty type `𝟘`](MLTT-Agda.html#emptytype)
     1. [The type `ℕ` of natural numbers](MLTT-Agda.html#naturalnumbers)
     1. [The binary sum type constructor `_+_`](MLTT-Agda.html#binarysum)
     1. [`Σ`-types](MLTT-Agda.html#sigmatypes)
     1. [`Π`-types](MLTT-Agda.html#pitypes)
     1. [The identity type former `Id`, also written `_≡_`](MLTT-Agda.html#identitytype)
     1. [Basic constructions with the identity type](MLTT-Agda.html#basicidentity)
     1. [Proofs involving negation](MLTT-Agda.html#negation)
     1. [Example: formulation of the twin-prime conjecture](MLTT-Agda.html#twinprime)
     1. [Operator fixities and precedences](MLTT-Agda.html#infix)
  1. [Univalent Mathematics in Agda](HoTT-UF-Agda.html)
     1. [Our univalent type theory](HoTT-UF-Agda.html#axiomaticutt)
     1. [Subsingletons (or propositions or truth values) and sets](HoTT-UF-Agda.html#subsingletonsandsets)
     1. [Example: the types of magmas and monoids](HoTT-UF-Agda.html#magmasandmonoids)
     1. [The identity type in univalent mathematics](HoTT-UF-Agda.html#identitytypeuf)
     1. [Identifications that depend on identifications](HoTT-UF-Agda.html#dependentequality)
     1. [Equality in Σ-types](HoTT-UF-Agda.html#sigmaequality)
     1. [Voevodsky's notion of hlevel](HoTT-UF-Agda.html#hlevel)
     1. [The univalent principle of excluded middle](HoTT-UF-Agda.html#em)
     1. [Hedberg's Theorem](HoTT-UF-Agda.html#hedberg)
     1. [A characterization of sets](HoTT-UF-Agda.html#setscharacterization)
     1. [Subsingletons are sets](HoTT-UF-Agda.html#subsingletonsaresets)
     1. [The types of hlevel 1 are the subsingletons](HoTT-UF-Agda.html#hlevel1subsingleton)
     1. [The types of hlevel 2 are the sets](HoTT-UF-Agda.html#hlevel2set)
     1. [The hlevels are upper closed](HoTT-UF-Agda.html#hlevelsupper)
     1. [Example: ℕ is a set](HoTT-UF-Agda.html#naturalsset)
     1. [Retracts](HoTT-UF-Agda.html#retracts)
     1. [Voevodsky' notion of equivalence](HoTT-UF-Agda.html#fibersandequivalences)
     1. [Voevodsky's univalence axiom](HoTT-UF-Agda.html#univalence)
     1. [Example of a type that is not a set under univalence](HoTT-UF-Agda.html#notsets)
     1. [Exercises](HoTT-UF-Agda.html#lefttothereader)
     1. [Solutions](HoTT-UF-Agda.html#solutions)
     1. [Function extensionality from univalence](FunExt.html#funextfromua)
     1. [Variations of function extensionality and their logical equivalence](FunExt.html#hfunext)
     1. [The univalence axiom is a (sub)singleton type](FunExt.html#univalencesubsingleton)
     1. [`hfunext` and `vvfunext` are subsingletons](FunExt.html#hfunextsubsingleton)
     1. [More applications of function extensionality](FunExt.html#morefunextuses)
     1. [Subsingleton truncation](Inhabitation.html#truncation)
     1. [The univalent axiom of choice](Inhabitation.html#choice)
     1. [Structure of identity principle](Inhabitation.html#sip)
     1. [Operator fixities and precedences](HoTT-UF-Agda.html#infix)
  1. [Appendix](Appendix.html)
     1. [Additional exercises](Appendix.html#moreexercises)
     1. [Solutions to additional exercises](Appendix.html#mlttexercisessol)
     1. [Agda files automatically extracted from these notes](https://github.com/martinescardo/HoTT-UF-Agda-Lecture-Notes/tree/master/agda)
     1. [The sources for these notes](https://github.com/martinescardo/HoTT-UF-Agda-Lecture-Notes)
     1. [License](LICENSE)