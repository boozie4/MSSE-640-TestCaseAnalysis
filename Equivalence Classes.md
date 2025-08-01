# SECTION 1: Introduction

Equivalence Class Partitioning is a method of software testing that divides the input or output domain into separate classes of data. These separate classes of data are known as equivalence classes. The input conditions are typically included in the specifications listed for the software being tested. The tester separates the input conditions into different subsets, which are the equivalence classes. Using these equivalence classes, test cases are developed. When setting the equivalence classes, the tester should use both valid and invalid classes in order to ensure productive testing results. The invalid classes are used to represent unexpected input. Often, selecting the equivalence classes is done in a trial-by-error processes. When looking at the same sets of conditions, different testers will often select different classes. 

# SECTION 2: Table/Diagram

Below is a table which represents possible equivalence classes for the Triagle Checker program that was written for class:

| Class | Data |
| ---------- | ---------- |
| EC1 | The input variable is a positive integer, valid |
| EC2 | The input variable is not a positive integer, invalid |
| EC3 | The value of side a plus side b is greater than side c, valid |
| EC4 | The value of side a plus side b is less than or equal to side c, invalid |

# SECTION 3: When Should This Type of Testing Be Used

This type of testing should be used when the input conditions are required to be within a specified range. For instance, if the software has to check that someone that is older than 18 years old but younger than 65 years old. In this scenario, three examples of equivalence classes would be for any input value lower than 18, any input values that is at least 18 but no higher than 65, and lastly, any input value that is higher than 65. This would test both the valid range of 18 to 65 and the invalid ranges of younger than 18 and older than 65. 

Another example of when this type of testing could be used is when a password needs to be created. Often times, passwords have a length criteria that must be met. Let's say that criteria in this example as that the password has to be at least characters long but no longer than 15 characters. Again, three examples of equivalence classes can be any input value that is lass than 8 characters, any input values that is at least 8 character but no more than 15 characters, and any input value that is more than 15 characters. This again would test the valid range of 8 character to 15 characters and the two invalid ranges of less than 8 characters and more than 15 characters.

# SECTION 4: Describe the Limitations

There are some limitations that come with using equivalence class partitioning. For example, due to this type of testing focusing only on data that is represented by the classes, there is potential for defects to be missed.

Secondly, partitioning is only as good as the definition for the equivalence classes. If the definitions of the partitioning are incorrect, this could lead to gaps in testing and in turn missed defects.

Thirdly, equivalence class partitioning is a technique know as black box testing. This method of testing does look beyond the scope of the inputs. This could lead to defects that arise due to coding logic being missed.