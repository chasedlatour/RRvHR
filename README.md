# RRvHR
Code used to generate analyses for Latour et al. 2023.

This publication is based on research using information obtained from data.projectdatasphere.org, 
which is maintained by Project Data Sphere. Neither Project Data Sphere nor the owner(s) of any information 
from the web site have contributed to, approved or are in any way responsible for the contents of this publication. 
Data cannot be made available on GitHub but is freely available for download, after signing an appropriate
data use agreement, from Project Data Sphere. 

The study team received an 80% random sample of data from two clinical trials of treatment for metastatic
colorectal cancer. Files for data cleaning are not provided in this GitHub repository. However, data from
these two trials were stacked into one dataset. The following variables were created:

1. trt: 1 = panitumumab + standard of care chemotherapy (SOCC), 0 = SOCC at randomization
2. days: time from randomization to the event for censoring
3. event: 1 = disease progression or death, 0 = censored

The uploaded file is an R Markdown document that was also attached as supplemental material to the article.
This RMD file is written to be knitted as an HTML file.
