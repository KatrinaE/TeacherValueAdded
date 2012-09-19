TeacherValueAdded
=================

Code I wrote to help me understand teacher value-added data. 
Free to use and distribute under the MIT license.

generateBivariateDataset.R:

Contains a function, gbd, for generating two random, normally distributed datasets 
with a given variance.  
Load the function into the command line and use from there.
You can adjust the correlation between the datasets. 

gbd will output two graphs:
The first graph plots the density curve of the first dataset factored by the 
quartile of the corresponding point in the second dataset.
The second graph plots the probability that an observation in a given percentile 
in the first dataset will fall in a given quartile in the second dataset.

I wrote this code to simulate the teacher value-added data discussed by the 
MET Project in their Learning About Teaching paper, available at:
 
http://www.metproject.org/reports.php

I used some assumptions described by Jesse Rothstein in the Technical Appendix 
to his review of this paper, available at:

greatlakescenter.org/docs/Think_Twice/TT_Rothstein_MET.pdf