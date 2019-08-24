# TransRepair

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
└── labeled data
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

The mutants and the manual assessment results can be found in the ```labeled data```.

The full results of Figure 4 (Comparison of metrics scores and manual inspection of translation consistency) can be found in ```Correlation between metrics and manual inspection```.

The full results of Table 6 (Influence of mutant number on testing and repair) can be found in ```Influence of Mutant Number```.

We also provide the correlation between different metrics including the original BLEU in ```Correlation between different metrics```.
