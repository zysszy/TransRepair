# TransRepair

TransRepair is a fully automatic approach for testing and repairing the consistency of machine translation systems. TransRepair combines mutation with metamorphic testing to detect inconsistency bugs (without access to human oracles). It then adopts probability-reference or cross-reference to post-process the translations, in a grey-box or black-box manner, to repair the inconsistencies.

This homepage contains the detailed results that do not appear in paper "Automatic Testing and Improvement of Machine Translation" (due to space reason). 

The file tree of TransRepair
```
.
├── Correlation between different metrics
│   └── Pearson correlation between different metrics.png
├── Correlation between metrics and manual inspection
│   ├── metric-human-compare-BLEU.pdf
│   ├── metric-human-compare-ED.pdf
│   ├── metric-human-compare-LCS.pdf
│   └── metric-human-compare-tfidf.pdf
├── Influence of Mutant Number
│   └── Influence of mutant number.png
└── Labeled data
    ├── RQ2 Inconsistency-revealing
    │   ├── README.md
    │   ├── Test-GT.txt
    │   ├── Test-Transformer.txt
    │   └── Threshold-Learning-data-GT.txt
    └── RQ3 Bug repair
        ├── Readme.md
        ├── RQ3-Bug-repair.GT.LCS.txt
        ├── RQ3-Bug-repair.Trans.LCS.txt
        └── RQ3-Bug-repair.Trans.Prob.txt
```

The mutants and the manual assessment results can be found in the ```Labeled data``` folder.

The full results of Figure 4 (Comparison of metrics scores and manual inspection of translation consistency) can be found in ```Correlation between metrics and manual inspection``` folder.

The full results of Table 6 (Influence of mutant number on testing and repair) can be found in ```Influence of Mutant Number``` folder.

We also provide the correlation between different metrics including the original BLEU in ```Correlation between different metrics```.
