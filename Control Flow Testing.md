# SECTION 1: Introduction

Control Flow Testing is a method of software testing often implemented by developers to test their own system or application. The reason for this is that the structure, design, and code should already by known by whoever is testing using this method. This method of software testing is used in order to test the logic of the code. This helps to ensure that all user requirements can be fulfilled. 

Some objectives of Control Flow Testing include:
* Path Coverage - The tester confirms that all paths through the system or application are run at least once.
* Branch Coverage - The tester confirms that all decision points are tested at least once.
* Decision Coverage - The tester executes each decision point at least once to ensure that all potential outcomes of the system or application running are tested at least once. 
* Error-Handling Paths - Allows the tester to observe how the system or applciation handles errors.
* Integration Testing - Allows the tester to observe how different components of the application or system interact with each other.

# SECTION 2: Table/Diagram

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

# SECTION 3: When Should This Type of Testing Be Used

This method of testing should be used when the logic of the code needs to be tested to ensure all user requirements are fulfilled. Testers can utilize this method of testing to ensure all paths of the system or application are tested and behave as expected. 

# SECTION 4: Describe the Limitations

* It is difficult to ensure all paths are tested if the code and the test model are written by the same person. 
* Larger projects with more complex flow can become more difficult.

# SECTION 5: Reference or Discussion About How You Used an AI Tool

No AI tools were used in this research. However, the following resources were used:

* Practical Software Testing by Ilene Burnstein
* https://www.geeksforgeeks.org/software-testing/control-flow-software-testing/
* https://www.geeksforgeeks.org/software-engineering/software-engineering-control-flow-graph-cfg/