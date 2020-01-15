# Quality Assurance Technical Vocabulary
by Brave Nick


 

Quality Assurance - is the way of preventing errors, mistakes or defects in process of software or hardware product development. In other words QA is responsible for product working as for client needs.

Testing - is the process of identifying defects, where a defect is any variance between actual result and expected result. It’s like being a detective you are trying different scenarios, strategies and possibilities to catch a bad guy. In our case we are chasing bugs.

Bug - is an error, flavor failure or defect in the software that causes it to produce incorrect or unexpected result.

Bug Cycles - start when bug found and filed and finishes up when bug fixed and closed. The common cycles or you can call them stages are New, Open, Assigned to, Fixed, Verified, Closed, Reopen, Rejected. 

New - When a defect is logged and posted for the first time.
Open - Its state when the developer starts analyzing and working on the defect fix.
Assigned - Once the bug is posted by the tester and reviewed by developer. It can be assign to a proper person.
Rejected - If appears that bug is not reproducible, QA Lead thinks that this is not a bug or maybe its a duplicate of existing one, bug can be rejected.
Fixed - When developer makes local code changes and verifies those changes from his side.
Verified - Tester must verify if the bug is fixed.
Closed - Test will close the bug.
Reopen - Reopen bug again if needed.

Verification - Focuses on process-related activities on to ensure if the product or deliverables meet specified requirements. Verification can be done by: Business, Technical or Management reviews.

Validation - Also focuses on process-related activities it determine if the system or product meet client expectations. 
And now ez explanation. Verification answers the question: Are we build the product right? And Validation answers the question - Are we building the right product?




Quality - The level of excellence for a given product or service. From the Quality Assurance stand point, we can divide our answer into two parts. From customer side, quality is level of satisfaction. Just remember that all customers are different and this will be very subjective meaning. From a quality assurance tester perspective quality is how accurately a product matches feature requirements.

Quality Control - We already talked about what is the Quality Assurance is, this two terms are relay to each other. But first let’s define what is Quality Control is. It’s a process of inspecting a product or a software to ensure if they meet quality standards. While talking about QA and QC you should remember the difference. QA focuses on a process that are used during development while QC is responsible for identifying and trying to take the defect products out. 

Software Development Life Cycle - It’s a structured approach of creating and maintaining a system. Some of SDLC models have 5 or even 10 stages. A typical SDLC framework used for a software development might include several main stages: Planning, Designing, Building, Testing, Deployment and Maintenance. In order to understand SDLC image that you are building a house. 

Planning - First things first you should have a plan and idea of product that you want to build. I’m using house as an example =)
Designing - We need to choose what type of building it will be. One or two floors. Do we need a garage and so on. Here we are doing drawings of our future house. 
Building - Process of product development. Team of contractors are building our house. 
Testing - Verification that all product requirements are completed. And our house looks like we expected =) 
Deployment - We are shipping our product. We are ready to move in. 
Maintenance - Product must properly maintained. We need to cut grass next to our house, sometimes it will require painting e.t.c. 

Test Scenario - Any functionality of you software that can be tested. We as a testers verifying that end to end functionality and business process flows are working fine. Test Scenario is like a high level Test Case.







Test Case - Is a set of activities/steps/actions that must be executed to verify software functionality.

Standard Test Case Format

1. Test Case ID
     Example: id123456

2. Test Scenario/Test Name
     Example: Verify that new folder can be created

3. Test Steps
     Example:
     - Launch Notes Application 
     - Tap new folder 
     - Add folder name 
     - Press "Save" button
     - Verify that folder name is properly saved

4. Test Data
     Input Data:
     - TestFolder 😂
     - testemail@gmail.com
     - 123456

5. Expected Result 
    Result:
    - Folder successfully created 

6. Actual Result 
    Result:
    - Folder successfully created (PASSED)
    - Failed to create new folder (FAILED)
 

