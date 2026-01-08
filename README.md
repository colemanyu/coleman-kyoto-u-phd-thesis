# Coleman's PhD Thesis
## Pending Tasks of mpmf
- [] Future Work
- [] Definition of time series forecasting
    - single step vs multi step
    - lag feature
- [] Define Evaluation
    - Rolling
    - Teacher forcing
- [] GBRT
    - XGBoost
- [] Matrix Profile
    - How to compute them
    - For the subsequence's definition, mention it is by the end point instead of the starting point
    - Exclusion zone
    - Three information:
        - $h$ subsequence points
        - distance between the query and the nearest neighbor
        - the location (i.e., idx)
- [] Update progress to Akutsu and Raymond
- [] Experiments
    -  Debug of top-1 motif, add distance directly and add as a denominator, normalize, trend
    - Refract the top-k method: Use the top-1 method for k time instead of using a for-loop for each index
        - How to merge different inmeridate subsequence    
    - Debug of top-k motif
        - Check why there is an error when no_of_points_after = 9
		- There are no enough points after the motif 
    - Test the base experiment for all the four datasets
    - If have time, also test the single-step dataset
    - autocorrelation graph (autocorrelation curve) or feature importance
    - top-k experiments
- [] Related Work
- [] Preliminaries
- [] Conclusion
- [] Abstract

## Checklist of the while thesis
- [] Capital/lower case letters in Section titles
are not consistently used.
- [] For Abstract, Introduction, Conclusion etc, change the contributions into three instead of two.
- [] Add figure into Chapter 2
- [] (6) Section 2.2.1
It may not be appropriate to use ED to denote Euclidean Distance
because in many cases ED is used to denote the edit distance.
- [] Furthermore Eq. (2.1) is more general than Euclidean Distance
(it is L_p norm).
- [] (6) Section titles
Some section titles should be changed as below
(in order to avoid overlap with Chapter titles).
3.5 Conclusion ==> Concluding Remarks
4.1 Introduction ==> Background
4.6 Conclusion and Future Work ==> Concluding Remarks
- [] (7) References
Author names are not consistently used.
(For example, see [5] vs. [6].)
- [] Such words as DNA, SVM, DTW in the paper titles should
be given in the capital letters.

## Remarks
- This template is downloaded at [[2403.15757] User-Side Realization](https://arxiv.org/abs/2403.15757).
    - From [佐藤竜馬（さとう りょうま）'s website](https://joisino.net/).
