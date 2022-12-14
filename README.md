# FAR-Berkeley-Parser

This repository contains grammar file created by training a new grammar using scripts from the Berkeley Parser package (Petrov et al., 2006; Petrov and Klein, 2007) on the Faroese Parsed Historical Corpus (Ingason et al, 2012).

"FARPAHC-Singlefile.txt" is Faroese Parsed Historical Corpus combined into a single file.

"grammar-file" is the grammar file created when training a new grammar using "GrammarTrainer.java" from the Berkeley Parser package on the Faroese Parsed Historical Corpus. The folder "grammar-trainer-output" contains the merging, smoothing and splitting files.

"grammar-to-text-output" contains the grammar written to text.

The Berkeley Parser package contains a script ("GrammarTester.java") that tests the accuracy of our model. According to that the result is:

[Current] P: 94.73 R: 94.73 F1: 94.73 EX: 0.0
[Average] P: 98.22 R: 98.06 F1: 98.14 EX: 90.2

As seen above, the F1 scores is surprisingly high, so it is very likely that something has gone askew in the process.

References:

Ingason, A. K., Rögnvaldsson, E., Sigurðsson, E. F., and Wallenberg, J. C. (2012). Faroese Parsed Historical Corpus (FarPaHC). Version 0.1. http://www.linguist.is/farpahc.

Petrov, S. and Klein, D. (2007). Improved Inference for Unlexicalized Parsing. In Human Language Technologies: The Annual Conference of the North American Chapter of the ACL (NAACL-HLT), Rochester, NY, USA. 

Petrov, S., Barrett, L., Thibaux, R., and Klein, D. (2006). Learning Accurate, Compact, and Interpretable Tree Annotation. In Proceedings of the 21st International Conference on Computational Linguistics and the 44th Annual Meeting of the ACL, Sydney, Australia.
