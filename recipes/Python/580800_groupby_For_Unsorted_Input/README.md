## groupby() For Unsorted Input  
Originally published: 2017-05-12 10:33:22  
Last updated: 2017-05-12 10:40:58  
Author: Alfe   
  
We all know the `groupby()` which is available in the `itertools` standard module.  This one yields groups of consecutive elements in the input which are meant to be together in one group.  For non-consecutive elements this will yield more than one group for the same key.