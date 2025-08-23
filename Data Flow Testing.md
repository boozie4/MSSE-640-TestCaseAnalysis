# SECTION 1: Introduction

Data Flow Testing is a method of software testing used to test the structure of the software. This method is used to find the test paths of the system or application based on the where the variables are defined and used. 

Data Flow Testing aims to identify issues that include the following:
* Incorrect variable definitions
* Unused variables
* Incorrect handling of data within the code

# SECTION 2: Table/Diagram

flowchart TD
    A[Start] --> B[Define x]
    B --> C[Use x]
    C --> D[Redefine x]
    D --> E[Use x]
    E --> F[End]

# SECTION 3: When Should This Type of Testing Be Used

Data Flow Testing should be used for the following when attempting to identify the following issues:
* Find variables that are used but either not defined or defined incorrectly
* Find variables that have been defined but are never used
* Find variables that have been defined multiple times before being used

# SECTION 4: Describe the Limitations

Some limitations associated with Data Flow Testing include:
* Can be a costly process
* Can be a time consuming process
* Requires knowledge and understanding of program languages

# SECTION 5: Reference or Discussion About How You Used an AI Tool

I used Copilot in VSCode to help with the example diagram. I also used the following resources for information:
* Practical Software Testing by Ilene Burnstein
* https://www.geeksforgeeks.org/software-testing/data-flow-testing/