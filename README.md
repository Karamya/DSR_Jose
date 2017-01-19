# DSR_Jose

Based on the data science course offered by Jose Quesada

1) SVM.SVC

Played mainly with the tuning parameter

C is treated as a tuning parameter that is generally chosen via cross validation. C controls the bias variance tradeoff. When C is small we seek narrow margins that are rarely violated. This amounts to a classifier that highly fits the data, which ma have low bias but high variance. On the other hand when C is large, the margin is wider and we allow more violations to it; this amounts to fitting the data less hard and obtaining a classifier that is potentially more biased but may have less variance.
