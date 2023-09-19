---
content_type: page
description: This section provides instructions for downloading and using the software
  environment used for the course.
learning_resource_types: []
ocw_type: CourseSection
title: R Scripts and Projects
uid: b91d782c-32fe-e884-1640-42d14c5c5d5e
---

The R Projects consist of html files with the output from running R scripts in RStudio. Using a web browser, these files detail various applications of R in the course.

Interested readers may download the compressed (zipped) folders and replicate the R / RStudio computations on their own computer.

The following instructions apply to executing R scripts in the first R Project. For all other R Projects, follow the same instructions (skipping step 1) replacing "rproject1.zip" with the corresponding compressed (zipped) folder for that project.

1.  Download / Install R and the Rstudio desktop on your computer

[http://www.rstudio.com/products/rstudio/download/](http://www.rstudio.com/products/rstudio/download/)

[http://cran.rstudio.com/](http://cran.rstudio.com/)

4.  Download the compressed folder for the R Project ("rproject1.zip" for Project 1) to your computer and extract the project directory, e.g., "rproject1" (for Project 1).
5.  Start the R-Studio application. From the top bar of commands
    *   select "File", then "New Project ...", then for the "Create Project from" option select "Create Project from Existing Directory"
    *   with the browser that appears, navigate to select the extracted directory "rproject1" (for Project 1, or "rproject2" for Project 2, etc.)
6.  The R-Studio application opens with a 4-panel display. The lower left panel is a console for typing R commands directly or viewing output from executed R commands. The lower right panel has tabs \[Files|Plots|Packages|Help\]. In the lower right panel, select the Files tab and open one of the R Script files, e.g., for Project 1 select the file "Rproject1\_script1.r" by clicking on the file name. The file will open in new tab in the top left panel.
7.  Go to the file in the top left panel: Rproject1\_script1.r. Execute the script file by either pressing the "Source" button at the top tool bar of the file window, or highlighting commands in the file and typing Control-Enter or Control-r. The html file in the project directory can be re-created (compiled) by pressing the "notebook" icon at the middle of the top bar of the top-left script window. The html file is easily viewed in a web browser and documents the R commands and output from executing the R script.
8.  To exit R-Studio, either type: q() # at the console, or select "File / Quit R" from the Tool Bar at the top of R-Studio. (It asks you to type "n" or "y" to not-save or save the workspace ".RData". You can type "n" since the scripts are designed to load relevant R workspaces explicitly; typing "y" will save any objects you might have created in the R workspace.)

Note: When you restart R-Studio, the application should open automatically with the same panel of open files.

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
SES #
{{< thclose >}}
{{< thopen >}}
PROJECT HTML FILES
{{< thclose >}}
{{< thopen >}}
R FILES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
L1
{{< tdclose >}}
{{< tdopen >}}
[R Project 1: Distributions Derived from the Normal Distribution](/ans7870/18/18.443/s15/projects/Rproject1_script1.html)
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link a05efd3e-0f69-cab5-2324-f22c9779e01a "R Project 1 (ZIP)" %}} (This file contains: 1 .r file.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L5
{{< tdclose >}}
{{< tdopen >}}


[R Project 2: LeCam-Neyman Precipitation Data (MOM Estimation of Gamma)](/ans7870/18/18.443/s15/projects/Rproject2_script1_gamma_MOM.html)

[R Project 2: LeCam-Neyman Precipitation Data (MOM with MLE)](/ans7870/18/18.443/s15/projects/Rproject2_script2_gamma_MOMwithMLE.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 47e1b77b-e557-ef80-9c4a-581da464efec "R Project 2 (ZIP)" %}} (This file contains: 2 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L6
{{< tdclose >}}
{{< tdopen >}}


R Project 3: Hardy Weinberg Model / Rayleigh Distributions

[Maximum Likelihood Estimates of Multinomial Cell Probabilities](/ans7870/18/18.443/s15/projects/Rproject3_rmd_multinomial_theory.html)

[ML and MOM Estimates of Rayleigh Distribution Parameter](/ans7870/18/18.443/s15/projects/Rproject3_rmd_rayleigh_theory.html)

[Multinomial Simulation](/ans7870/18/18.443/s15/projects/Rproject3_script1_multinomial_simulation.html)

[Poisson Prussian Cavalry](/ans7870/18/18.443/s15/projects/Rproject3_script3_Poisson_PrussianCavalry.html)

[Chromatin](/ans7870/18/18.443/s15/projects/Rproject3_script4_Chromatin.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 3d7d9ff4-be99-9fc6-e687-266fb8b75bb4 "R Project 3 (ZIP)" %}} (This file contains: 3 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L8
{{< tdclose >}}
{{< tdopen >}}


R Project 4: Bayesian Estimation

[Bayesian Hardy Weinberg](/ans7870/18/18.443/s15/projects/Rproject4_Bayesian_HardyWeinberg.html)

[Bayesian Poisson](/ans7870/18/18.443/s15/projects/Rproject4_Bayesian_Poisson.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 1dd06484-bc95-7905-84f4-da5512cf8fa8 "R Project 4 (ZIP)" %}} (This file contains: 2 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L9
{{< tdclose >}}
{{< tdopen >}}


[R Project 5: Hypothesis Testing](/ans7870/18/18.443/s15/projects/RProject5_HypothesisTesting.html)

[Problem 9\_11\_1 and 6](/ans7870/18/18.443/s15/projects/Problem_9_11_1and6.html)

[Problem 9\_11\_3](/ans7870/18/18.443/s15/projects/Problem_9_11_3.html)

[Problem 9\_11\_7](/ans7870/18/18.443/s15/projects/Problem_9_11_7.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 754eff19-a244-3215-be92-3d2cf534862a "R Project 5 (ZIP)" %}} (This file contains: 4 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L10
{{< tdclose >}}
{{< tdopen >}}


R Project 6: Hypothesis Testing II

[LRTest Hardy Weinberg](/ans7870/18/18.443/s15/projects/Rproject6_LRTest_HardyWeinberg.html)

[LRTest Poisson](/ans7870/18/18.443/s15/projects/Rproject6_LRTest_Poisson.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 7c4b5e88-d582-ca43-b3be-90cffae545c6 "R Project 6 (ZIP)" %}} (This file contains: 2 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L11
{{< tdclose >}}
{{< tdopen >}}


R Project 7: Assessing Goodness of Fit

[Beeswax](/ans7870/18/18.443/s15/projects/Rproject7_5_beeswax.html)

[Lifetimes](/ans7870/18/18.443/s15/projects/Rproject7_6_lifetimes.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 0a5f6696-6ec2-e555-38c2-7a9d61ef133b "R Project 7 (ZIP)" %}} (This file contains: 6 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L13
{{< tdclose >}}
{{< tdopen >}}


R Project 8: Summarizing Data

[Problem 10\_9\_26](/ans7870/18/18.443/s15/projects/Problem_10_9_26.html)

[Windspeed](/ans7870/18/18.443/s15/projects/Rproject8_1_windspeed.html)

[ks\_test](/ans7870/18/18.443/s15/projects/Rproject8_2_ks_test.html)

[Bootstrap Location](/ans7870/18/18.443/s15/projects/Rproject8_3_bootstrap_location.html)

[Density](/ans7870/18/18.443/s15/projects/Rproject8_4_density.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link cb8e28ee-e57e-f08b-cef3-50ad6395dec0 "R Project 8 (ZIP)" %}} (This file contains: 5 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L14
{{< tdclose >}}
{{< tdopen >}}


R Project 9: Regression Analysis of CAPM

[FM Casestudy\_1\_0\_Download Data](/ans7870/18/18.443/s15/projects/fm_casestudy_1_0_DownloadData.html)

[FM Casestudy\_1\_1\_CAPM](/ans7870/18/18.443/s15/projects/fm_casestudy_1_1_CAPM.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 0aac7613-22c4-082e-4531-410c45b3b308 "R Project 9 (ZIP)" %}} (This file contains: 2 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L15
{{< tdclose >}}
{{< tdopen >}}


R Project 10: Polynomial Regressions and Weighted Regressions

[Problem 14\_9\_39](/ans7870/18/18.443/s15/projects/Problem_14_9_39.html)

[Flow Occ Regressions](/ans7870/18/18.443/s15/projects/Rproject10_flow_occ_regressions.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 26bdf414-f67c-94f0-dacc-34d1c603e0df "R Project 10 (ZIP)" %}} (This file contains: 3 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L16
{{< tdclose >}}
{{< tdopen >}}


R Project 11: Multiple Comparisons and ANOVA

[Tablets One Way Anova](/ans7870/18/18.443/s15/projects/Rproject11_Tablets_OneWayAnova.html)

[Tablets Two Sample T](/ans7870/18/18.443/s15/projects/Rproject11_Tablets_TwoSampleT.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 2372b9fd-169e-2896-a03e-622268f02f4a "R Project 11 (ZIP)" %}} (This file contains: 2 .r files.)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
L17
{{< tdclose >}}
{{< tdopen >}}


[R Project 12: Chi-square Tests and Fisher's Exact Test](/ans7870/18/18.443/s15/projects/RProject12_ChisquareTest.html)


{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 28db7170-7890-6a31-4152-e634280af779 "R Project 12 (ZIP)" %}} (This file contains: 2 .r files.)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}