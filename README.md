
### Sefl-Driving Car Nanodegree Program. Term 3
<img style="float: left;" src="https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg">

## Project 12: Functional Safety of a Lane Assistance System

### Overview
---
The goal of this project is to create a report that documents the functional safety of a lane assistance system. The project includes:

* Safety Plan
* Hazard Analysis and Risk Assessment
* Functional Safety Concept
* Technical Safety Concept
* Software Safety Requirements and Architecture Document

### Project directory content:

* [README.md](README.md) - This file.
* [docs/](docs/) folder - The documents in Microsoft Office format
* [pdf/](pdf/) folder - The documents in PDF format

### Reflection

#### General

In the project I went through the high-level steps that the [ISO 26262](https://www.iso.org/standard/43464.html) standard requires for building a functional safety case of the Lane Assistance item. ISO 26262 is the world-recognized standard for automotive functional safety.


#### Safety Plan

In the [Safety Plan](pdf/01_SafetyPlan_LaneAssistance.pdf) document I provided an overall framework for the Lane Assistance project and defined roles and responsibilities between the players involved in the project.

#### Hazard Analysis and Risk Assessment

In the [Hazard Analysis and Risk Assessment](pdf/02_HazardAnalysisAndRiskAssessment.pdf) document I identified the mulfunctions and evaluated thier risk level for the Lane Assistance item. I performed a situational analysis, hazard identification, hazardous event classification, ASIL and derived the safety goals for the item. I included two additional cases of the hazard analysis: one is analyzing a case when the LDW fuction provides not enough oscillating torque for a driver to respond and the second one is analising driving on the road with a construction site. 

#### Functional Safety Concept

In the [Functional Safety Concept](pdf/03_FunctionalSafetyConcept_LaneAssistance.pdf) document I refined the safety goals in functional safety requirements and defined which part of the Lane Assistance system architecture will implement each requirement. I also expanded the system architecture with new element blocks - safety blocks for Lane Departure Warning (LDW) and Lane Keep Assistance (LKA) functions. 

#### Technical Safety Concept

In the [Technical Safety Concept](pdf/04_TechnicalSafetyConcept_LaneAssistance.pdf) document I turned functional safety requirements into technical safety requirements and allocated the technical safety requirements to the system architecture. 

#### Software Safety Requirements and Architecture

In the [Software Safety Requirements and Architecture](pdf/05_SoftwareRequirementsAndArchitecture_LaneAssistance.pdf) document I defined software requirements and the software architecture that will ensure functional safety of the Lane Assistance item. 
