# ECE444-F2022-Lab6
Code here is a copy of the original repo found [here](https://github.com/mjhea0/flaskr-tdd)
## Unit Tests in Project
Added unit tests to test course backend ratings [here](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-18-caffeinated/blob/dev/Education_Pathways/tests/test_course_ratings.py), all unit tests in file written by me.

Added unit tests to test course backend reviews [here](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-18-caffeinated/blob/dev/Education_Pathways/tests/test_course_reviews.py), unit tests by me are indicated.

Added unit tests to test hss and cs course eligibility backend [here](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-18-caffeinated/blob/dev/Education_Pathways/tests/test_hss_cs_eligibility.py), all unit tests in file written by me.
## Pros and Cons of TDD
The advantages that come with TDD mainly revolve around the decoupling of code and the resulting high modularity as well as the certainty that each module is behaving as expected. TDD puts the programmer in a position where they are designing one component of the overall feature at a time and writing accompanying test code as they go. This allows a larger problem to be decomposed into smaller parts with the assurance each part is working as intended before moving on. This helps avoid debugging large areas of code which is both confusing and time consuming. Additionally, the modular nature of the code allows it to be easier to maintain as modifications can be done on specific modules instead of searching across the code base for the areas one would like to change. Additionally, TDD acts as another way to document the code with other programmers able to view the test code and gather how the code is meant to be used.

The disadvantages revolve around added work to achieve the desired functionality of a project. Having to write tests for each facate of the development process will take more time and code will have to be adjusted and modularized to allow for unit tests to be written. Additionally, when modules are redesigned and changed the tests must be updated. Furthermore, if the entire team does not commit to unit testing TDD quickly falls apart as tests cannot be used as a measure of codebase functionality as parts will remain untested.

