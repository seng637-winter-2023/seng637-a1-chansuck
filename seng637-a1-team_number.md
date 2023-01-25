>   **SENG 637- Dependability and Reliability of Software Systems**


**Lab. Report \#1 – Introduction to Testing and Defect Tracking**


| Group: Group Number      |
|-----------------|
| Nicholas Lor                |  
| Nic Hirschfeld              |  
| Student 3 name               |  
| Student 4 name                |  




**Table of Contents**


(When you finish writing, update the following list using right click, then
“Update Field”)


[1 Introduction 1](#_Toc439194677)


[2 High-level description of the exploratory testing plan   1](#_Toc439194678)


[3 Comparison of exploratory and manual functional testing  1](#_Toc439194679)


[4 Notes and discussion of the peer reviews of defect reports   1](#_Toc439194680)


[5 How the pair testing was managed and team work/effort was
divided 1](#_Toc439194681)


[6 Difficulties encountered, challenges overcome, and lessons
learned 1](#_Toc439194682)


[7 Comments/feedback on the lab and lab document itself 1](#_Toc439194683)


# Introduction # Shawn


An introduction of your lab work, and what you knew about exploratory and manual
functional testing before this lab


# High-level description of the exploratory testing plan #Shawn


Text…


# Comparison of exploratory and manual functional testing

Both the manual functional testing and the exploratory testing were useful testing methods for this project. However, all of the defects found with exploratory testing, were also found with manual functional testing. Meanwhile, manual functional testing found a couple unique defects that were not discovered through exploratory testing.


The manual functional testing was a more thorough testing experience than the exploratory testing. This was mainly due to the difference in volume of test cases performed during the exploratory testing in comparison to the manual functional testing. Exploratory testing was limited to 30 minutes, which resulted in 35 test cases run. A total of 40 test cases were run during manual functional testing. 


There are a couple manual function test cases that were very broad and provided a lot of freedom for the user to test. For example, test case #8 for the manual functional testing checks to see if any action can be performed successfully. The test case does not specify any specific action, instead, the user can pick any action and check if successful. This broad style of test case was not ever used during the exploratory functional testing. During exploratory testing, each test case was very specific in the action being tested and contained clear instructions on steps to take during each specific test. The broad test case style has the potential to miss a defect if the user tests a specific transaction but not another. However, the manual functional testing makes up for the lack of detail in test case #8 by running a lot of additional test cases (40 test cases). 


One main difference between the exploratory testing and the manual functional testing is the functional repetition performed during manual functional testing. There was minimal functional repetition performed during exploratory testing. Only proper inputs were tested and each function was only tested once. For example, improper card pin or insufficient balance checks were not tested during exploratory testing. Only the correct card pin and sufficient balance checks were tested. Due to the 30 minute exploratory testing limit, the exploratory testing plan was defined in a way to minimize extensive testing and prioritize a general test of all major functions. Manual functional testing contained a lot more extensive tests; for example, checking invalid pin extension for five separate test cases. Overall, a longer and more extensive testing method will find more defects as long as all major functions are still being tested.


Please refer to appendix A for the exploratory functional testing case results and please refer to appendix B for the manual functional testing case results. 

# Notes and discussion of the peer reviews of defect reports


The group came to a consensus and followed the outline of the following to include in the defect reports: the function being tested, the initial state of the system, detailed steps to reproduce the bug/defect, the expected outcome, and the actual outcome. With a descriptive title, and using the above points as headers in the report, there is clarity and consistency when interpreting the issues for the developers and support team to understand and effectively address the bugs. The language remains objective to not place blame or criticize, and the descriptions are clear for the issues to be reproduced. The communication in the defect reports are effective in allowing the tester and the developer to work as a team to resolve the issues. When the issues were addressed, the defect reports were also updated with detailed comments (and closed if resolved) to continue the process of team communication.


# How the pair testing was managed and team work/effort was divided


Each member of the group first familiarized themselves with the scope of the assignment and the high level requirements of the ATM simulation program. The group discussed possible features of the system to test. During the exploratory testing phase the group was split into two pairs, Nic and Shawn using Card 1, and Nick and Tania using Card 2. Given half an hour for exploratory testing, one member of each pair performed tests on the program (Shawn and Nick) while the other member of the pair documented the process (Nic and Tania) of system state, input, expected output, and actual output. After regrouping, the discovered defects were compared and compiled into a set of unique defects and divided into an equal number for each member to submit. The defects were submitted into the Issue Tracking System (GitHub Issues) to create the Defect Report.


Manual scripted tested was performed as a group on Version 1.0, following the test suite outlined in Appendix C of the assignment manual. Shawn performed the tests while the rest of the group members instructed him on the detailed steps, recorded outcomes, and created issues to submit to the Defect Report.


For regression testing, the group retested the issues initially submitted and updated the defects as resolved/closed, or in-progress/open with detailed comments on the outcomes.


A second manual scripted testing was performed as a group on Version 1.1, again following the test suite outlined in Appendix C. Again, Shawn performed the tests while the remaining group members were responsible for documentation.


# Lessons Learned from your teamwork (NICK)




# Difficulties encountered, challenges overcome, and lessons learned (NICK)


Text…


# Comments/feedback on the lab and lab document itself (NICK)


Text…

# Appendix A - Exploratory Functional Testing

Table...

# Appendix B - Manual Functional Testing

Table...

# Appendix C - GitHub Issues?


