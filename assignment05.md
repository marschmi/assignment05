# The Maintenance of Biodiversity in a Dispersal-Limited Strains of E. coli
Edna Chiang and Marian Schmidt  
November 24, 2014  


##The Problem
1. How do local dispersal and species interactions influence biodiversity? 
2. How do global dispersal and species interactions influence biodiversity?


##Our Assumptions
* Simple community that perfectly follows Rock-Paper-Scissors model:
      + Resistant *E.coli* (R) beats colicin-producing *E.coli* (C)
      + Sensitive *E.coli* (S) beats R 
      + C beats S 
* No top-down or bottom up controls on community.
      + No outside disturbance.
      + No spatial or temporal environmental heterogeneity.
* Assume 2 extremes:
      + Local includes only adjacent cells.  Location is everything.
      + Global includes entire community.  All interactions created equally, location doesn't matter.
* Assumes background death rates are constant for each strain.
* Assumes no evolution of each strain (e.g. no evolution of S to R).


##Reproduction of Figure 1a-d

![plot of chunk unnamed-chunk-1](./assignment05_files/figure-html/unnamed-chunk-1.png) 


##GIFs  




##Experiment
As you can see above, R wins the global scenario.  This is because R has a slighly lower death rate of 10/32 than the C, which has a death rate of 1/3, so R can outcompete C.  We are curious as to the outcome if both death rates are equivalent.

**Research questions:**  
1.  If R and C have the same death rate, do R, C, & S coexist in the **local** simulations?  
2.  If R and C have the same death rate, do R, C & S coexist in the **global** simulations?    
**Hypotheses:**   
1.  R, C, and S will coexist if R & C have the same death rate in **local** simulations.  
2.  R and C will coexist, and S will go extinct if R & C have the same death rate in **global** simulations.   


![plot of chunk unnamed-chunk-2](./assignment05_files/figure-html/unnamed-chunk-2.png) 






```
## Warning: package 'animation' was built under R version 3.1.1
```



##GIF
