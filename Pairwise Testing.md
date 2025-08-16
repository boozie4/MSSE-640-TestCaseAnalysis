# SECTION 1: Introduction

Pairwise testing is a software testing method which looks at all possible combination of input requirements. This method of testing is most useful when exhaustive testing is not practical or possible. Pairwise testing can help in making the test phase more efficient, thorough, and cost-effective. 

When looking at efficiency, pairwise testing can assist by reducing the number of test cases needed while maintaining a high chance of detecting any defects that may be present. Additionally, using this method and testing all possible pairs of input parameters helps to ensure that the tester has thorough coverage of interactions between the different variables. Lastly, when looking at cost-effectiveness, pairwise testing can help save time and resources by minimizing the number of test cases while still maintaining a high level of quality in testing. 

Additional benefits of pairwise testing include the following:

* Increased Defect Detection - Pairwise testing focuses primarily on the interactions between pairings of input parameters. This method helps to enhance the detections of defects which may be missed by other methods of testing.
* This method of testing is adaptable to both small and large systems with a large number of input parameters.

# SECTION 2: Table/Diagram

As an example, suppose there is a system or application which has 6 different input parameters, each with three different possible values.

* Parameter 1: 1, 2, 3
* Parameter 2: Green, Blue, Purple
* Parameter 3: Pass, Fail, Null
* Parameter 4: A, B, C
* Parameter 5: True, False, Maybe
* Parameter 6: X, Y, Z

| Test Case | Parameter 1 | Parameter 2 | Parameter 3 | Parameter 4 | Parameter 5 | Parameter 6 |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| 1 | 1 | Green | Pass | A | True | X |
| 2 | 1 | Blue | Fail | B | False | Y |
| 3 | 1 | Purple | Null | C | Maybe | Z |
| 4 | 2 | Green | Pass | A | True | X |
| 5 | 2 | Blue | Fail | B | False | Y |
| 6 | 2 | Purple | Null | C | Maybe | Z |
| 7 | 3 | Green | Pass | A | True | X |
| 8 | 3 | Blue | Fail | B | False | Y |
| 9 | 3 | Purple | Null | C | Maybe | Z |

# SECTION 3: When Should This Type of Testing Be Used

Pairwise testing is best used when there are numerous input parameters that need to be tested, and exhaustive testing is not practicle or possible. Using Pairwise testing, the tester can combine multiple parameters for testing, which reduces the number of test cases and increases the efficiency of testing. 

# SECTION 4: Describe the Limitations

* Assumes that the input parameters are all independent. However, it is possible for input parameters to affect another, changing the behavior of the system or application being tested.
* There may be contraints in the input parameters which could limit the combinations of input parameters which produce valid test results.

# SECTION 5: Reference or Discussion About How You Used an AI Tool

No AI tools were used to help with this research. However, the following websites were used:
* https://ashok-s-nair.medium.com/qa-pairwise-testing-guidelines-and-caveats-1b7b60d2416
* https://www.testrail.com/blog/pairwise-testing/