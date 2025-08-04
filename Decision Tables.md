# SECTION 1: Introduction

Before discussing decision tables, one must understand cause-and-effect graphing first. Cause-and-effect graphing is a testing technique that can be used to combine different conditions in order to create a set of test cases that is effective in disclosing inconsistensies in specifications. 

For this technique, the specifications need to be laid out in a graph similar to that of a digital logic circuit. Because of this, it is important to have knowledge and understanding of Boolean logic. Once this graph is created, then it can be converted into a decision table. 

The decision table reflects the graph that was used to create it along with the specifications for the project. This table shows the effects for all possible combinations of causes. Each column of this table lists a combination of causes, and each column represents a test case. Each cause and effect will have its own row. Each entry in the table can be represented by a "1" if a cause or effect is present, by a "0" if there is the absense of a cause or effect, and by "-" for a value that is not considered relevant. This decision table is then used by the tester to develop test cases.

# SECTION 2: Table/Diagram

Let's say as an exaple, the specifications for a project are looking for adults, ages 21 to 40. The input conditions, or the causes, would be as follows:

C1: Person who is an adult 
C2: Ages between 21 and 40

The output conditinos, or the effects, would be as follows:

E1: Adult, but not in the correct age range
E2: Adult in correct age range
E3: Not an adult

The rules, or the relationships, can then be descibed as such:

* If C1 and C2, then E2
* If C1 and not C2, then E1
* If not C1, then E3

The decision table would be shown as follows:

**Boundary Value Analysis (Adults Ages 21 to 40)**
|  | Test 1 | Test 2 | Test 3 |
| ---------- | ---------- | ---------- | ---------- |
| C1 | 1 | 1 | 0 |
| C2 | 1 | 0 | - |
| ---------- | ---------- | ---------- | ---------- |
| E1 | 0 | 0 | 1 |
| E2 | 1 | 0 | 0 |
| E3 | 0 | 1 | 0 |

This table would then be used by the tester to develop test cases.

# SECTION 3: When Should This Type of Testing Be Used

Decision tables are beneficial when used in instances where there is a large amount of different input scenarios that need to be tested. Using decion tables helps to reduce complexity and redundancy of the testing process. Although this technique can be time consuming, one advantage of using this technique is that it allows for in depth and thorough inspection of the specifications while develping the rules and contitions for the cause-and-effect graph. Therefore, any inaccuracies or inconsistencies are likely to be detected early on in the process. 

# SECTION 4: Describe the Limitations

One major limitation to this technique is trying to develop the cause-and-effect graph and the decision table when there is a large number of causes and effects to consider. It can be difficult to choose causes and effect that will produce significant results in situations like this. However, as a possible solution to this, the tester can break down some of the complex specifications into smaller and simpler components. These simpler components can them be used to create the cause-and-effect graph and the decision table.

# SECTION 5: Reference or Discussion About How You Used an AI Tool

I did not use AI for this assignment. However, I did use the following resources:

* Practical Software Testing by Ilene Burnstein
* https://testsigma.com/blog/decision-table-testing/