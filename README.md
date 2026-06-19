# trivial-quandle-colorings
GAP code for [this MathOverflow answer](https://mathoverflow.net/a/512177/592688).

Based on the [online rack and quandle library](https://www.cs.du.edu/~petr/libraries_of_algebraic_structures.html) of Petr Vojtěchovský and Seung Yeop Yang.

This program is designed to find quandles Q such that (i) the trefoil has only trivial Q-colorings but also (ii) the granny knot has nontrivial Q-colorings. The result is that taking Q := LRQ.Quandle(8,1543) in Vojtěchovský and Yang's library suffices; in fact, the granny knot has 80 colorings by this choice of Q. Moreover, this Q is the minimal example in the sense that for all other quandles of order up to 8 other than Q, condition (i) holds but condition (ii) does not hold.

The code is designed to skip any coloring quandles Q that are faithful. Indeed, every faithful quandle that satisfies condition (i) will not satisfy condition (ii); this can be seen by combining (4.3) with Lemma 4.2 in [this paper](https://arxiv.org/abs/1901.10996).
