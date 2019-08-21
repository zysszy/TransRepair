This directory includes the files of the manual assessment results in RQ3.

We manually inspect the changed translation pairs after repairing.

We compared three dimensions: 

1) the translation consistency before and after repair;

2) the quality of the changed translations, which includes the changed translations for both the original sentence and the mutant.

```RQ3-Bug-repair.GT.LCS.txt```: the changed translation in Google Translate with cross-reference.

```RQ3-Bug-repair.Trans.Prob.txt```: the changed translation in Transformer with probability-reference .

```RQ3-Bug-repair.Trans.LCS.txt```: the changed translation in Transformer with cross-reference.

In these files, each changed translation is decomposed into 12 lines.

Line 1: the translation quality of the original sentence

Line 2: the translation quality of the original mutant

Line 3: the translation consistency after repairing

Line 4: the translation of the original sentence before repairing

Line 5,7: the original sentence

Line 6: the translation of the original sentence after repairing

Line 8: the reference sentence in the test set.

Line 9: the translation of the mutant before repairing

Line 10,12: the mutant

Line 11: the translation of the mutant after repairing
