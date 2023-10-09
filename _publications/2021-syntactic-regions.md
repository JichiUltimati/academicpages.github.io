---
title: "Syntactic Regions for Concurrent Programs"
collection: publications
permalink: /publication/2021-syntactic-regions
date: 2021
venue: 'MFPS 2021'
paperurl: 'http://jichiultimati.github.io/files/syntactic-regions.pdf'
citation: 'Syntactic Regions for Concurrent Programs. Samuel Mimram and Aly-Bora Ulusoy. In Ana Sokolova, editor, Proceedings 37th Conference on Mathematical Foundations of Programming Semantics, MFPS 2021, volume 351 of EPTCS, page 184–199, 2021.'
---
In order to gain a better understanding of the state space of programs, with the
aim of making their verification more tractable, models based on directed
topological spaces have been introduced, allowing to take in account equivalence
between execution traces, as well as translate features of the execution (such
as the presence of deadlocks) into geometrical situations. In this context, many
algorithms were introduced, based on a description of the geometrical models as
regions consisting of unions of rectangles. We explain here that these
constructions can actually be performed directly on the syntax of programs, thus
resulting in representations which are more natural and easier to implement. In
order to do so, we start from the observation that positions in a program can be
described as partial explorations of the program. The operational semantics
induces a partial order on positions, and regions can be defined as formal
unions of intervals in the resulting poset. We then study the structure of such
regions and show that, under reasonable conditions, they form a boolean algebra
and admit a representation in normal form (which corresponds to covering a space
by maximal intervals), thus supporting the constructions needed for the purpose
of studying programs. All the operations involved here are given explicit
algorithmic descriptions.

[Download paper here](http://jichiultimati.github.io/files/syntactic-regions.pdf)
