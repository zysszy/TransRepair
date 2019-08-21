This directory includes the files of the manual assessment results in RQ2.

We manually assess whether the test inputs we generated are qualified for detecting inconsistency issues.

```Test-GT```: the labeled tests for Google Translate.

```Test-Transformer```: the labeled tests for Transformer.

```Threshold-Learning-data-GT.txt```: the labeled tests for learning the thresholds.

In these files, each test is decomposed into 9 lines. 

Line 1: the results of whether the test reveals a bug. 
(```True``` for inconsistent bug, ```False``` for consistent)

Line 2-5: the metrics we used

Line 6: the translation of the mutant

Line 7: the mutant

Line 8: the translation of the original sentence

Line 9: the original sentence
