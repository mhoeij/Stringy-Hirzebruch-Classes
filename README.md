# Stringy-Hirzebruch-Classes
Computer files accompanying the paper "Stringy Hirzebruch classes of Weierstrass fibrations"
available at:  arxiv.org/abs/1810.10150

The file Q_Simplified contains the formulas copied from Section 8 of the paper (the
file Q_Simplified2 contains the same data presented in a slightly different way).

To verify these formulas, run the file RunAll in Maple. RunAll will read the
file MapleCode (which contains the algorithms) and the files E6.txt ... USp4.txt
which contain data specific to each case.
It will compute expressions Q_Y(l,s) for each case and compares them with the expressions
in the file Q_Simplified to ensure that the formulas in the paper are correct. Next it
computes terms of the series chi (to change the number of computed terms, change the
value of ORDER). This computation led to files chi_order_4, chi_order_6, and CalabiYau
(see these files for more details on the settings of options).
