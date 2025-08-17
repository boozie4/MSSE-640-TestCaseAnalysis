# SECTION 1: Introduction

Control Flow Testing is a method of software testing often implemented by developers to test their own system or application. The reason for this is that the structure, design, and code should already by known by whoever is testing using this method. This method of software testing is used in order to test the logic of the code. This helps to ensure that all user requirements can be fulfilled. 

Some objectives of Control Flow Testing include:
* Path Coverage - The tester confirms that all paths through the system or application are run at least once.
* Branch Coverage - The tester confirms that all decision points are tested at least once.
* Decision Coverage - The tester executes each decision point at least once to ensure that all potential outcomes of the system or application running are tested at least once. 
* Error-Handling Paths - Allows the tester to observe how the system or applciation handles errors.
* Integration Testing - Allows the tester to observe how different components of the application or system interact with each other.

# SECTION 2: Table/Diagram

graph TD
    A[Start] --> B{Is condition met?};
    B -- Yes --> C[Do something];
    B -- No --> D[Do something else];
    C --> E[End];
    D --> E;

| Inputs | State 1 | State 2 | State 3 | 
| ---------- | ---------- | ---------- | ---------- |
| 1 | S1 (Act 1) | S2 (Act 2) | S3 (Act 3) |
| 2 | S3 (Act 4) | S2 (Act 5) | S1 (Act 6) |
| 3 | S3 (Act 7) | S3 (Act 8) | S3 (Act 9) |

# SECTION 3: When Should This Type of Testing Be Used



# SECTION 4: Describe the Limitations



# SECTION 5: Reference or Discussion About How You Used an AI Tool

