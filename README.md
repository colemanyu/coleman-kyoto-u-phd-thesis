# Coleman's PhD Thesis

## Checklist of the whole thesis

- [] "Introduction ==> Background", "Conclusion ==> Concluding Remarks" to avoid overlap with Chapter titles
- [] The term "this paper" should not be used.
- [] Check figures, tables size.
- [] Any text exceed margin.
- [] Check References
    -  The use of capital letters and lowercase letters in paper titles should be consistent.
    -  Bold fonts should be used for such terms as DNA, program names, and MicroRNA in the titles of the papers.
- [] No line numbers

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

## Raymond's suggestions

- 50 slides
- Don't include the formal definition, as it will distract the audience. Put them in backup slides.
- Put the evaluation metric in backup slides for completeness
- Tell the whole story instead of three individual works

```
Organziation:
--------------------------------------------------------
Bioinformatics



bioinformatics
  Slides 44-68
dynamic DTW
  Slides 7-27
forecasting
  Slides 29-43

============================
Intro (2-5 slides) (5-10 mins)
(3 problems)
paper list (1 slide)

Intro
- story telling

time series
multiple series



============================

bioinformatics (5-10 minutes)
(state clearly that you have presented it 
in the previous presentation. so, we just
highlighted the major points and skipped
the details. The details could be asked in
the Q&A session or in the thesis).
- 2-3 slides (background and problem definition)
- 1-2 slide (related work and limitation)
- 1 slide (contribution)
- 1-2 slide (major idea of your approach)
- 1-2 slide (exp. setup and result)

============================

DTW (15-20 mins)
----------------

a. Background
   - applications (3)
   - problem definition (e.g. or definition)
     e.g., 
b. Related Work and Limitation
   category 1 
   category 2  (e.g., "[Bioinformatics22]")
     (describe ==> limitation)
c. Contribution
   I. propose XXX which <major idea>
      which addresss Limitiaton 1 .... 2....3
   ii. experimetns on 4 real dataset
     that algorithm is faster than <model> XXX tiems
     in most datasets (e.g., dataset wigh size at least XXX)
d. Proposed Method
   1-3 slide (major idea)
   several slides (algorithm following the major idea) (example)
    
e. Experiment
   - setup (dataset, baseline, measurement, factors)
   - figures/tables 
f. Conclusion

============================
forecasting (15-20 mins)
----------------


a. Background
   - applications (3)
   - problem definition (e.g. or definition)
     e.g., 
b. Related Work and Limitation
   category 1 
   category 2  (e.g., "[Bioinformatics22]")
     (describe ==> limitation)
c. Contribution
   I. propose XXX which <major idea>
      which addresss Limitiaton 1 .... 2....3
   ii. experimetns on 4 real dataset
     that algorithm is faster than <model> XXX tiems
     in most datasets (e.g., dataset wigh size at least XXX)
d. Proposed Method
   1-3 slide (major idea)
   several slides (algorithm following the major idea) (example)
    
e. Experiment
   - setup (dataset, baseline, measurement, factors)
   - figures/tables 
f. Conclusion


============================

PPT Conclusion (1-3 slides)
---------------------------
summary (1 slides)
future work (1-2 slides)

============================


--------------------------------------------------------
```

```
DP skeleton:
--------------------------------------
Problem 

Method - Dynamic programming

a. Major idea:
  dynamic programming

consider a problem P of size N

consider a subproblem P1
consider a subproblem P2

Assume that we know the solution S1 of P1
and the solution S2 of P2

We could use these 2 solutions to find
the solution of problem P
e.g., .....

exactly the core element of DP

------------------
formulate DP as follows


formal dp

Solution <-- S1 union S2 

Base case:
-.....

----------------

pseudo code

----------------
```


## Remarks

- This template is downloaded at [[2403.15757] User-Side Realization](https://arxiv.org/abs/2403.15757).
    - From [佐藤竜馬（さとう りょうま）'s website](https://joisino.net/).
