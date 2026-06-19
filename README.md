# trivial-quandle-colorings
GAP code for the MathOverflow answer [link forthcoming]

Based on the [online rack and quandle library](https://www.cs.du.edu/~petr/libraries_of_algebraic_structures.html) of Petr Vojtěchovský and Seung Yeop Yang.

This program is designed to find quandles Q such that (i) the trefoil has only trivial Q-colorings but also (ii) the granny knot has nontrivial Q-colorings. The result is that taking Q := LRQ.Quandle(8,1543) in Vojtěchovský and Yang's library suffices; in fact, the granny knot has 80 colorings by this choice of Q. Moreover, this Q is the minimal example in the sense that for all other quandles of order up to 8 other than Q, condition (i) holds but condition (ii) does not hold.
