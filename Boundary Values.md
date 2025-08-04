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

**Boundary Value Analysis (Ages 18 to 65)**
| Invalid (Min - 1) | Valid (min, min + 1, nominal, max - 1, max) | Invalid (max + 1) |
| ---------- | ---------- | ---------- |
| 17 | 18, 19, 41, 64, 65 | 66 |

# SECTION 3: When Should This Type of Testing Be Used

Boundary Value Analysis testing is used when there are large groups of input values to be tested. Using the table in the above section as an example, if a tester would have to test several ages of people to ensure the proper output for each, the testing could become exhaustive. By using a few values at and near the boundaries, the tester is able to ensure the correct output for a whole set of inputs by focusing the testing at the boundaries. When testing, if the input value is 17 and the output is "Invalid age, please enter a valid age to proceed", and then the tester can test 18 and 19 and the software proceeds, this shows that tester that the lower bound is working as it should. The same can be said for the upper bound. If the input is 66 and the software again says "Invalid age, please enter a valid age to proceed", but when 65 or 64 is entered and the software proceeds, then the tester can be confident that the upper bound is working as well. 

# SECTION 4: Describe the Limitations

A couple of limitations when using Boundary Value Analysis

* This technique is only valuable for the tester when the software is under test.
* This technique does not take into accound the nature of the funtional dependencies of any variables.

# SECTION 5: Reference or Discussion About How You Used an AI Tool

I did not use any AI tools to help with this assignment. Rather, all information I used was found in the following:

* Practical Software Testing by Ilene Burnstein
* https://www.geeksforgeeks.org/software-testing/software-testing-boundary-value-analysis/