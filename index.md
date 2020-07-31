<img style="float: right;" src="img/1024.png" height="150px" width="150px">

# Welcome to ProjectAble Home Page 

> A Helpful Status Reporting and Forecasting App for iPhone

## What is ProjectAble?
ProjectAble uses a traditional project management technique called Earned Value Analysis to forecast the outcome of the project accurately and reliably.

### Budget Distribution
ProjectAble uses the reporting frequency, project start and project end dates, and selected budget distribution curve input by the user when setting up the project, to spread the project budget according to expectated project spend and schedule. ProjectAble provides 5 methods for distributing budgets:
1. Flat - distributes the budget evenly across the reporting periods
2. Front - loads the majority of spend at the beginning of the project
3. Normal - loads the majority of spend in the middle of the project
4. Back - loads the majority of spend towards the end of the project
5. Manual - enables the user to create per reporting period budgets manually according to their planning

ProjectAble distributes the automated budget spreads by dividing the duration into quarters and applying a rate to each reporting period within each quarter in order to profile distribution as smoothly as possible. Setting budgets manually provides greater control over budget distribution.

### Treatment Of Time
ProjectAble uses time only to calculate the project duration and number of reporting periods when a project is created. Each time a new progress update is added, ProjectAble calculates the budget percentage complete and spend for the reporting period (or uses the manual values provided). The reporting period is important but ProjectAble does not use specific date and time values in these calculations. With the final progress update, ProjectAble will set the percent complete to 100%. As with all progress updates, you can overwrite the pre-calculated values but please note, setting the percent complete to less than 100% will allow the project to continue, however, in these circumstances the calculations may behave unexpectedly.

### Completing a project
A project is set to complete automatically with the final reporting period or a project can be manually marked complete in 'Project Settings'. by clicking the button on the Project Details screen.

## Use of Earned Value (EVA) techniques
ProjectAble uses the earned value calulations discussed widely on the web and published in the **Project Management Book of Knowledge (PMBoK)** [PMI EVA](https://www.pmi.org/learning/library/make-earned-value-work-project-6001). In addition, ProjectAble makes use of two additional Estimate AT Complete methods - [IEAC1 & IEAC2](https://www.linkedin.com/pulse/earned-value-management-ieac1-ieac2-mick-higgins/) which provide further context around the likely outturn of the project.

Calculation | Method | Descriptive Method
------------|--------|-------------------
Planned Value (BCWS) | Planned PComp * BAC | Planned Percent Complete * Budget At Complete (original project budget)
Earned Value (BCWP) | PComp * BAC | Actual Percent Complete * BAC
Schedule Variance | EV - PV | Earned Value - Planned Value
Schedule Performance Index | EV / PV | Earned Value / Planned Value
Cost Variance | EV - AC | Earned Value - Actual Cost
Cost Performance Index | EV / AC | Earned Value / Actual Cost
Estimate At Complete | BAC / CPI | Project Budget / Cost Performance Index
IEAC1 (independent EAC1) | (AC + (BAC-EV)) / CPI | Actual Cost + (Budget Cost - Earned Value) / Cost Performance Index
IEAC2 (independent EAC2) | (AC + (BAC-EV)) / (CPI * SPI) | Actual Cost + (Budget Cost - Earned Value) / (Cost Performance Index * Schedule Performance Index)
Estimate To Complete | EAC - AC | Estimate At Complete - Actual Cost (to date)
To Complete Project Index | (BAC - EV) / (BAC - AC) | (Budget Cost - Earned Value) / (Budget Cost - Actual Cost)

## Notes
- ProjectAble **_is_** a helpful tool to enable project professionals to track the status and forecast of a project quickly, reliably and accurately
- ProjectAble **_is not_** intended to replace good planning, estimation, monitoring or control processes. Other tools are available for those purposes.

### Contact
email | <ProjectAble@aleynmoor.co>


<img  style="float: center;" src="img/1024.png" height="150px" width="150px">
