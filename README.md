# Assignment1 - Practice Designing Models (Template)

> * Participant name: Hsiao-Chin Chiang
> * Project Title: Hospital Trauma Capacity

## General Introduction

A **smart city** is an urban area that uses different types of electronic data collection sensors to supply information which is used to manage assets and resources efficiently.

![Image of Smart City](images/smartcity.png)

Every smart city needs an effective Emergency Management System. It is crucial for EMS management personnel to understand what resources are available during crisis situations. Knowing the maximum capacity for incoming trauma patients of a hospital's Emergency Department allows EMS management personnel to divert patients to the appropriate facilities for care. Trauma surges require short-fused support from services other than the Emergency Department. Surges pull resources away from the Intensive Care Units and ancillary services like radiology. Eventually the inpatient units may be adversely affected by the truama surge. 
Most patients of the 2016 shooting at Pulse Nightclub in Orlando were transported to Orlando Regional and some to Florida Hospital due to their proximity and trauma certification level. The influx of patients stressed the capabilities of these hospitals. Real time feedback of ED capacities could have prompted EMS to route the most critica patients to Florida Hospital and Orlando Health. Less critical patients could be transported to other area hospitals and alleviate the stress level at Orlando Regional. 
Lessons learned were published after mass casualty events such as 9/11 attacks, VA Tech shootings, and Madrid bombings. Each of the events noted a trauma surge that exceeded the capacity of local healthcare systems. Most current literature on the effects and management of trauma surges have a hospital focus rather than an EMS focus. EMS decisions on casualty transport is determined by the local hospital's divert status which is typically assigned by each ED chief.

## Requirements (Experimental Design)

Identifing maximum capacity level for receiving trauma patients by each Emergency Department facilitates transport decisions for EMS personnel. Staff ratios for trauma patients are as follow: one provider (MD or PA) to 2 patients, one nurse to 4 patients, one Patient Care Technician to 4 patients, one Unit Clerk per provider. Each patients completes treatment by either being discharged, admitted, or transferred for defenitive care. Once an ED is at max capacity, automated notifications would be sent to EMS and first responder communication systems. EMS dispatch system in turn will display the nearest alternative ED based on the EMS asset's GPS location. 

## Smart City Trauma Surge Capacity Model

* [**Object Diagram**](model/object_diagram.md) - provides the high level overview of components
* [**Class Diagram**](model/class_diagram.md) - provides details of (what are you providing details of)

## Smart City Trauma Surge Capacity Simulation

[**Hsiao-Chin Chiang**](https://github.com/IDS6145-18Spring/assignment-1-practice-designing-models-Hsiao-Chin/blob/master/analysis/README.md)


## Smart City (My Problem) Model
[**Code template**](code/README.md) - Starting coding framework for the trauma surge capacity.

## **P**ortable **O**rganic **T**rouble-free **S**elf-watering System (**POTS**) Model
Here [**we provide an overview**](code/POTS_system/README.md) of the **P**ortable **O**rganic **T**rouble-free **S**elf-watering System (**POTS**) Model and provide a source code template.
