# SECTION 1: Introduction

State transition testing is based on the concept of states. A "state" is an internal configuration of a system which defines the values or status of the particular variables that represent the system at a specific time. State transition testing allows the tester to view the application or system in terms of its states, the transitions between the different states, and the inputs that trigger the transitions between states. 

# SECTION 2: Table/Diagram

Given an example of a system that has three separate states and three different input paramenters, the following is a state table for this example:

| Inputs | State 1 | State 2 | State 3 | 
| ---------- | ---------- | ---------- | ---------- |
| 1 | S1 (Act 1) | S2 (Act 2) | S3 (Act 3) |
| 2 | S3 (Act 4) | S2 (Act 5) | S1 (Act 6) |
| 3 | S3 (Act 7) | S3 (Act 8) | S3 (Act 9) |

# SECTION 3: When Should This Type of Testing Be Used

State Transition Testing is best utilized when there is a system or application that has transitions that need to be tested. The input being passed is changed and the behavior of the system or application is observed as this change happens. 

# SECTION 4: Describe the Limitations

Some limitations of State Transition Testing include the following:

* There are times in which it may be difficult to recognize or determine what every state of a system or applicatino is. 
* Individual state transitions are the primary focus of this method of testing. Because of this, defects which are the result of a combinations of states may be missed.

# SECTION 5: Reference or Discussion About How You Used an AI Tool

No AI tools were used for this research. However, the following resources were used:

* Practical Software Testing by Ilene Burnstein
* https://www.geeksforgeeks.org/software-engineering/state-transition-testing/