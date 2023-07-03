A paper by Rochon described the application of the piecewise exponential (PE) regression model for
performing overall survival (OS) and conditional survival (CS) analysis. It indicates how to
formulate the model, derive the associated OS and CS probabilities together with their
confidence limits, and perform tests of significance using Wald chi-squared procedures.
The methodology is illustrated using an example published by Moertel et al. evaluating
long-term survival following treatment for colon cancer. Code was written in SAS to
implement this methodology and perform the analyses. It is now being made available
to the wider research community so that it can be applied to similar problems. 

This package contains software to implement this methodology. It consists of the
following components.

. Users Guide.pdf – A users guide to the software.
. Colon.csv – The Moertel dataset downloaded from GitHub
. C Colon Cancer.pdf – The associated documentation
. IML Macros for OS and CS Analysis.sas –PROC IML macros
. PE Model with LIFEREG.sas – The SAS code implementing the PE model. 
. IML Code to Analyze Moertel Cancer Data.sas – IML code for OS and CS probs
. Results from OS and CS Analysis of Moertel Cancer Data.txt – Moertel results

DISCLAIMER:
THIS SOFTWARE IS PROVIDED BY JAMES ROCHON AS A PUBLIC SERVICE.  IT IS PROVIDED "AS IS."
THERE ARE NO WARRANTIES, EXPRESSED OR  IMPLIED, AS TO ITS FITNESS FOR A PARTICULAR
PURPOSE OR REGARDING THE ACCURACY OF THE MATERIALS OR CODE CONTAINED HEREIN.

It is being provided under a Creative Commons CC BY-NC license. You are allowed to 
distribute, remix, adapt, and build upon this material in any medium or format but for
noncommercial purposes only. Further, You must give appropriate credit to the author,
and indicate if any changes were  made. You may do so in any reasonable manner,
but not in a way that suggests that the author endorses you or your use.  You may not
apply legal terms or technological measures that  legally restrict others from doing
anything the license permits.


