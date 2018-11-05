# FunctionalSafetySDCN
Functional safety project for Udacity Self Driving Car Nanodegree

### Overview

This is the project repository for Elective Project No. 2, Functional Safety. The project is done as a part of the third term of Udacity Self Driving Car Nanodegree program. 

The goal of this project is to develop an example safety plan for one item of the vehicle in production, namely the Lane Assitance System. The safety plan for the item is developed in accordance with the Road Vehicles Functional Safety Standard [ISO 26262](https://en.wikipedia.org/wiki/ISO_26262). 

As described in the PDF documents which are part of this repository, to develop the **safety plan**, we start with the **hazard analysis and risk assessment** with respect to the item under consideration (in our case, the **Lane Assistance System**). Based on that analysis, we create the **functional safety concept**, which states the measures that we need to undertake in order to bring the risk down to the acceptable levels. The functional safety concept describes these measures from the higher level without going deep into technical details, but then the next step is development of the **technical safety concept**, which takes the functional safety concept as a starting point and provides technical details on how the safety measures will be practically implemented. Finally, from the technical safety concept, we develop the **software and hardware requirements**, which are even more detailed descriptions of the safety measures, written so that they can serve as a practical reference and precise instructions to the software and hardware design engineers working on the design of the item. 

In this project, we developed the following PDF documents that describe each of these steps in the functional safety development of the Lane Assistance System: 

- Safety Plan
- Hazard Analysis and Risk Assessment
- Functional Safety Concept
- Technical Safety Concept, and 
- Software Requirements

Please note that this safety case does not contain an entire functional safety analysis of the vehicle, but focuses on two distinct parts of the Lane Assistance System: 

- **Lane Departure Warning** - this function warns the driver in the case when the vehicle drifts over the markings of the ego lane
- **Lane Keeping Assistance** - this function helps the driver to keep the vehicle near the centerline of the ego lane, by applying additional torque to the steering wheel, in addition to the torque exerted by the driver

For more details on these two functions, as well as the safety related measures involved in their design, please see the attached PDF documents. 

### More information
For even more information on the project, please check the original Udacity project [repository](https://github.com/udacity/CarND-Functional-Safety-Project)
