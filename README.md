# ABExperimentReport
Html knitted from RMD in RStudio

This is my statistical analysis of an A/B experiment designed and run on whether or not to launch a pop up window
in between the "Start Free Trial" and course enrollment page. 

My invariant metrics:
- number of unique cookies that viewed the course listing page
- number of cookies to click "Start Free Trial" (this was shown before the tested change)

My evaluation metrics:
- gross conversion (probability of enrollment based on number of "Start Free Trial" clicks)
- net conversion (probability of continuing the trial through 14 days based on the number of "Start Free Trial" clicks)

The data was supplied by the course, but based on the provided numbers, an alpha of 0.05 and a 1-beta of 0.2, I found that
the experiment produced the desired effect: gross conversion changed significantly from the control, and the net conversion did not change significantly (with some caveats). 

