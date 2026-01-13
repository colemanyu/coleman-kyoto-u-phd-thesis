# Coleman's PhD Thesis
## Pending Tasks of mpmf
- Matrix Profile
    - How to compute them
    - For the subsequence's definition, mention it is by the end point instead of the starting point
    - Exclusion zone
    - Three information:
        - $h$ subsequence points
        - distance between the query and the nearest neighbor
        - the location (i.e., idx)
    - Some mass background
  - Other experiment result
--------------------
- Experiments
    -  Debug of top-1 motif, add distance directly and add as a denominator, normalize, trend

    - Refract the top-k method: Use the top-1 method for k time instead of using a for-loop for each index
        - How to merge different inmeridate subsequence    
    - Debug of top-k motif
        - Check why there is an error when no_of_points_after = 9
		- There are no enough points after the motif 
    - If have time, also test the single-step dataset
    - autocorrelation graph (autocorrelation curve) or feature importance
    - top-k experiments
--------------------
- Conclusion
- Preliminaries
- Abstract

## Checklist of the whole thesis
- [x] "Introduction ==> Background", "Conclusion ==> Concluding Remarks" to avoid overlap with Chapter titles
- [x] Check References
    -  The use of capital letters and lowercase letters in paper titles is not consistent.
    -  Bold fonts should be used for such terms as DNA, program names, MicroRNA in the titles of the papers.
- [x] "this paper" should not be used.
- [ ] No line numbers

---
--------------------------------
[Table 5.1]
It is strange that $w,h$ have a single value (not a pair of values).

[Section 5.4]
It is unclear whether you only used y (not used x, u).

[Table 5.2, 5.3]
It is strange that the results on Exchange-Rate for
GBRT, GBRT-NN, GBRT-NN-S are the same in both tables.

---

## Notifications
- The pre-defense 
    - Date & time: January 20: 15:00-17:00
        - I should arrive at room 131 by 14:50.
    - Place: Building 7, seminar room 2 (1F, room 131)
in Yoshida campus
    - Remarks
        - The examiners
            - Prof. Tatsuya Kawahara (kawahara@i.kyoto-u.ac.jp)
            - Prof. Hisashi Kashima (kashima@i.kyoto-u.ac.jp)
        - You must send a draft of Ph.D thesis to them
by January 13.
            - Please send the thesis separately to each examiner (without CC to Akutsu-sensei).
            - Please first send e-mail without PDF and then send PDF. (because e-mail may not reach them if PDF is large.)
            - Please ask them whether they need a hard copy. If they need, please hand over the thesis directly.        
        - The length of the presentation should be around
50 minutes.
        - Presentation slides should also be distributed to the examiners on the day of the presentation.
        - It is OK that 1 page consists of 4 slides with printed double-sided. (i.e., 1 paper can contain 8 slides.)
        - Water for examiners. Laser Pointer.

## Remarks
- This template is downloaded at [[2403.15757] User-Side Realization](https://arxiv.org/abs/2403.15757).
    - From [佐藤竜馬（さとう りょうま）'s website](https://joisino.net/).
