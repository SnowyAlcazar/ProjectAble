<HEAD><link rel="shortcut icon" href="url to /img/favicon.ico" type="image/x-icon" /></HEAD>
       
[Home](index) <a name="Index"></a> | [News](News) <a name="News"></a> | [Gallery](gallery) <a name="Gallery"></a> | [Privacy Policy](PrivacyPolicy) <a name="Privacy Policy"></a> | [Contact Us](contactus) <a name="Contact Us"></a>


<img style="float: right;" src="img/1024.png" height="150px" width="150px">

# ProjectAble <a name="top"></a>

> A helpful status reporting and forecasting App for iPhone

<img style="border:1px solid gray;" src="img/1. Project List.png" height="200px" width="100px">   <img style="border:1px solid gray;" src="img/2. About ProjectAble.png" height="200px" width="100px">   <img style="border:1px solid gray;" src="img/4a. Project Info.png" height="200px" width="100px">  <img style="border:1px solid gray;" src="img/6. Progress History.png" height="200px" width="100px">   <img style="border:1px solid gray;" src="img/5a. Current Status Report 1.png" height="200px" width="100px">

## Current Version
Version 1.0.13 

<a href="https://apps.apple.com/gb/app/projectable/id1515134507?mt=8" style="display:inline-block;overflow:hidden;background:url(https://linkmaker.itunes.apple.com/en-us/badge-lrg.svg?releaseDate=2020-08-18&kind=iossoftware&bubble=apple_music) no-repeat;width:135px;height:40px;"></a>

## Table of contents
[What is ProjectAble?](#introduction)

[How does ProjectAble work?](#how)

[Earned Value (EVA) calculations](#ev)

## What is ProjectAble? <a name="introduction"></a>
ProjectAble harnesses the power of Earned Value Analysis to provide the Current Status of a Project and to Forecast the outcome of the project accurately and reliably. It is designed for usability and to provide useful output which can be used in discussions about project status and viability.
ProjectAble is quick and easy to use and provides valuable output.

## How Does ProjectAble Work? <a name="introduction"></a>

A ProjectAble project is quick to setup and to record progress updates. The calculations are done behind the scenes and a report is produced with commentary to help identify those areas in need of attention.

:eyeglasses: [ProjectAble User Guide](https://snowyalcazar.github.io/ProjectAble/pdfs/UserGuide.pdf) <a name="projectableuserguide"></a>

Each project has a Red, Amber, Green (RAG) status and the project list on the home screen, is sorted in order of priority enabling the project manager to quickly identify those projects in greatest need of attention. The status report clearly identifies the current performance trend along with key performance indicators and the narrative. Each progress update is recorded and can be viewed in Progress History which makes it a simple task to audit progress to date. 

ProjectAble provides several methods to automatically distribute the budget across the project duration. The automated distribution methods enable project setup with the least effort but may well not provide the level or detailed control required. For projects requiring greater control over budget distribution, there is an option to manually input the planned budget per reporting period.

Project data (both input and calculated) is stored (on the device) and can be reviewed by looking at the progress history screen. This data is stored only on the device and is not collected or shared.

### Treatment Of Time <a name="time"></a>
ProjectAble uses time only to calculate the project duration and number of reporting periods when a project is created. Each time a new progress update is added, ProjectAble calculates the budget percentage complete and spend for the reporting period (or uses the manual values provided). The reporting period is important but ProjectAble does not use specific date and time values in these calculations. With the final progress update, ProjectAble will set the percent complete to 100%. As with all progress updates, you can overwrite the pre-calculated values but please note, setting the percent complete to less than 100% will allow the project to continue, however, in these circumstances the calculations may behave unexpectedly.

### Budget Distribution  <a name="distribution"></a>
ProjectAble uses the reporting frequency, project start and project end dates, and selected budget distribution curve input by the user when setting up the project, to spread the project budget according to expectated project spend and schedule. ProjectAble provides 5 methods for distributing budgets:

Curve | Description
------|------------
Flat | distributes the budget evenly across the reporting periods
Front | loads the majority of spend at the beginning of the project
Normal | loads the majority of spend in the middle of the project
Back | loads the majority of spend towards the end of the project
Manual | enables the user to create per reporting period budgets manually according to their planning

ProjectAble distributes the automated budget spreads by dividing the duration into quarters and applying a rate to each reporting period within each quarter in order to profile distribution as smoothly as possible. Setting budgets manually provides greater control over budget distribution.

> If the duration of a project allows less than 4 reporting periods, the curve will be treated as **flat**. This does not apply if the project is using the ***manual budget*** option.

### Completing a project <a name="completing"></a>
A project is set to complete automatically with the final reporting period or a project can be manually marked complete in 'Project Settings'. by clicking the button on the Project Details screen.

[Back to top...](#top)

## Use of Earned Value (EVA) calculations <a name="ev"></a>

ProjectAble uses the earned value calulations discussed widely on the web and published in the **Project Management Book of Knowledge (PMBoK)** [PMI EVA](https://www.pmi.org/learning/library/make-earned-value-work-project-6001). In addition, ProjectAble makes use of two additional Estimate AT Complete methods - [IEAC1 & IEAC2](https://www.linkedin.com/pulse/earned-value-management-ieac1-ieac2-mick-higgins/) which provide further context and provides a range in which the final project cost is currently forecast to fall.

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

## Notes <a name="notes"></a>
- ProjectAble **_is_** a helpful tool to enable project professionals to track the status and forecast of a project quickly, reliably and accurately
- ProjectAble **_is not_** intended to replace good planning, estimation, monitoring or control processes. Other tools are available for those purposes.

## Privacy Policy <a name="privacy"></a>
- ProjectAble does not collect any personal data
- ProjectAble does not share any personal data
- All data entered in or created by ProjectAble is stored in local database on the users device

[Back to top...](#top)

<img  style="float: center;" src="img/ProjectAble_QAR.png" height="204px" width="550px">

