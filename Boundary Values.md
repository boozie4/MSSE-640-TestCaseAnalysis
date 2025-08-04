# SECTION 1: Introduction

 Boundary Value Analysis is a software testing technique that is used in conjuction with equivalence class partitioning. Boundary value analysis is where the software tester chooses elements at the edge of the equivelence classes. This ensures both the upper and lower limits of an equivalence class to be tested. The boundaries that are used in this technique are those of the valid class. The values to be tested are listed below:

 * BLB - A value just Below the Lower Bound
 * LB - The value ON the Lower Bound
 * ALB - A value just Above the Lower Bound
 * BUB - A value just Below the Upper Bound
 * UB - The value ON the Upper Bound
 * AUB - A value just Above the Upper Bound

 Boundary value analysis is used to refine the results a tester gets from equivalence class partitioning. Utilizing this technique improves the likelihood the tester will find defects that may be present in the software.

# SECTION 2: Table/Diagram

Let's use a program that requires its users to be between the ages of 18 and 65. The table below reflects valid and invalid data for testing. 

Boundary Value Analysis (Ages 18 to 65)
| ---------- | ---------- | ---------- |
| Invalid (Min - 1) | Valid (min, min + 1, nominal, max - 1, max) | Invalid (max + 1) |
| ---------- | ---------- | ---------- |
| 17 | 18, 19, 41, 64, 65 | 66 |

# SECTION 3: When Should This Type of Testing Be Used



# SECTION 4: Describe the Limitations



# SECTION 5: Reference or Discussion About How You Used an AI Tool

