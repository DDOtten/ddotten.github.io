---
permalink: /path_categories
title: "Research Project on Path Categories"
layout: minimal_page
---

# Research Project on Path Categories

Path Categories form a categorical framework for homotopy theory that gives a semantics for type theory.
Path categories are simple compared to other semantics but contain enough structure to prove homotopy theoretical results.
It is a notion that is closely connected to two established frameworks: Brown’s categories of fibrant objects and Quillen’s model categories.

A *path category* is a category $$\mathcal C$$ with two classes of maps: *fibrations* and *(weak) equivalences*.
If a fibration is an equivalence then we call it *acyclic*.
In addition, the following principles should hold:
* There exists a terminal object 1 and every map $$A\to1$$ is a fibration.
* Fibrations are closed under composition.
* The pullback of a fibration along any map exists and is also a fibration.
* The pullback of an acyclic fibration is also an acyclic fibration.
* Isomorphisms are acyclic fibrations.
* Every acyclic fibration has a section.
* Equivalences satisfy 2-out-of-6: if for $$\smash{A\stackrel f\to B\stackrel g\to C\stackrel h\to D}$$ we have that both $$gf$$ and $$hg$$ are equivalences, then so are $$f$$, $$g$$, $$h$$, and $$hgf$$.
* Every object $$A$$ has a path object: an object $$PA$$ together with a fibration $$(s,t):PA\to A\times A$$ and an equivalence $$r:A\to PA$$ such that $$(s,t)r=(1_A,1_A)$$.
  Note that $$PA$$ does not have to be functorial in $$A$$.

In a path category we can define a lot of homotopy theory and prove statements such as: every map can be written as an equivalence followed by a fibration, the weak equivalences are precisely the homotopy equivalences, and the fact that the equivalences are orthogonal to the fibrations (up to fibered homotopy).

The goal of this project is to gather the existing literature in one place and to describe it in a unified and structured way.

6 ECTS, Spring 2024 \
Supervisors: [Benno van den Berg](https://staff.fnwi.uva.nl/b.vandenberg3/) and [Daniël Otten](/).

# Literature

* Papers:
  * Benno van den Berg, Ieke Moerdijk 2018 - **[Exact Completion of Path Categories and Algebraic Set Theory: Part I: Exact Completion of Path Categories](https://www.sciencedirect.com/science/article/pii/S0022404917302827).**
  * Benno van den Berg 2018 - **[Path Categories and Propositional Identity Types](https://dl.acm.org/doi/abs/10.1145/3204492).**
  * Benno van den Berg 2020 - **[Univalent Polymorphism](https://www.sciencedirect.com/science/article/abs/pii/S0168007220300178).**
* Master Theses:
  * Nils Donselaar 2016 - **[Uniform Kan Cubical Sets as a Path Category](https://studenttheses.uu.nl/bitstream/handle/20.500.12932/22925/3476022MScThesisFinal.pdf?sequence=2).**
  * Menno de Boer 2018 - **[The Gluing Construction for Path Categories](https://studenttheses.uu.nl/bitstream/handle/20.500.12932/29726/Masterscriptie_MWEdeBoer.pdf?sequence=2).**
  * Matteo Spadetto 2019 - **[Generalised Gluing and Exact Completion of Path Categories](https://spadetto.github.io/Generalised_Gluing_and_Exact_Completion_of_Path_Categories___Current_Version.pdf).**
  * Evio Paauw 2021 - **[Path Categories and ∞-groupoids](https://www.ebpaauw.com/math/pathcategoriesandinfinitygroupoids.pdf).**
* Notes:
  * Taichi Uemura 2019 - **[Fibred Path Categories](assets/papers/taichi_uemara_fibered_path_categories.pdf).**
  * Martijn den Besten 2020 - **[On Homotopy Exponentials in Path Categories](https://arxiv.org/abs/2010.14313).**
  * Benno van den Berg, Martijn den Besten 2021 - **[Quadratic Type Checking for Objective Type Theory](https://arxiv.org/abs/2102.00905).**
  * Evio Paauw 2021 - **[Path Categories and Inverse Diagrams](https://www.ebpaauw.com/math/pathcategoriesandinversediagrams.pdf).**