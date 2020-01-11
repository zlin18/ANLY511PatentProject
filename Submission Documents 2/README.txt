README: Final Project
Name: Zhiyu Lin, Jingjie Ma, Thomas P. Malejko, Douglas Post, Nuo Tian, Nuoya Wu
Class: ANLY 511-01
=======================================================================================================================================

OVERVIEW OF DIRECTORY:

FILES:
ANLY511_Paper_Final.docx			Final Project Paper
ANLY511_Final Project_Patent-Script.html	Final Project R Code Submission

REQUIRED LIBRARIES FOR SCRIPT:
ggplot2
dplyr
stringer
lubridate
gridExtra
readxl
tidyr
tidyverse
zoo
ggpubr
simpleboot

REQUIRED DATA FILES:
monthly.csv					Data file from the USPTO containing information about monthly patent statistics
monthly_disposal.csv				Data file from the USPTO containing detailed information about monthly patent statistics

OUTPUT FILES:	
Patent.csv					Generated output containing the initially cleaned data set along with newly generated features including monthly turnover statistics
Patent_Cleaned.csv				Generated output containing the fully cleaned data set, including proper variable names
PatentWaitTimes.csv				Output from EDA #1 containing information about Patent Wait Times for approval
Patents Pending v Abandonded.png		Output from the EDA #2, which formed the basis for the statistical study
plot_Chemical_CatDF.png				Individual Plot from the larger EDA 2 Output
plot_Drug_Med_CatDF.png				Individual Plot from the larger EDA 2 Output
plot_InfoTech_CatDF.png				Individual Plot from the larger EDA 2 Output
plot_Mechanical_CatDF.png			Individual Plot from the larger EDA 2 Output
plot_Missing_CatDF.png				Individual Plot from the larger EDA 2 Output
plot_NotClassified_CatDF.png			Individual Plot from the larger EDA 2 Output
plot_Others_CatDF.png				Individual Plot from the larger EDA 2 Output
Prop1_Elec Patents Pending c 1996.png		Comparison Box Plot
Prop2_SemiConduct Patents Pending c 1996.png	Comparison Box Plot
Prop3_Elec Patents Abn c 2001_Scatter.png	Comparison Scatter Plot
SummaryStats511.csv				Output showing the general summary statistics for this data set.

