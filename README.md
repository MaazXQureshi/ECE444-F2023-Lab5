# ECE444-F2023-Lab5

This repo is a clone/closely follows the instruction of repo - https://github.com/mjhea0/flaskr-tdd

**Activity 2 - Unit Test Link**

https://github.com/ECE444-2023Fall/project-1-web-application-design-group5-frog/blob/124ed0856a3645b819ed47180073b2f226342cbe/tests/app_test.py#L32

Implemented test_club_info_page to test for correct response codes when accessing club pages.

Also implemented test_index and test_database above along with initializing test.tb with test data in a commit from last week:

https://github.com/ECE444-2023Fall/project-1-web-application-design-group5-frog/pull/8

**Activity 3 - Pros/Cons of TDD**

As mentioned in the lab video, some of the pros of TDD include the fact that it forces a developer to automate their testing process. This ensures that the testing process is much more efficient as it would waste a developer’s time if they had to test the code manually each time. Automation in this context allows for increased productivity as the developer can spend more time working on the code or developing new features as opposed to testing which is now automated. Secondly, it brings everyone on the same page before implementation begins. This ensures that the entire development team is in agreement about what the desired functionality of a certain component is before development for that component even begins. This avoid conflict later as different developers will not have conflicting views on what the component’s intended functionality or use was. Next, by having tests written down before the implementation begins, it ensures that there is no bias which would otherwise be introduced if the developer had written their code first and then proceeded to write tests that may have validated their own implementations and assumptions. This also ensures that the process is not rushed since all the tests are written beforehand, so that when development of a certain component finishes, there is no scramble to test out its functionality, thereby ensuring a better overall product quality.  Furthermore, a higher degree of confidence is achieved at the time of deployment since the developer worked towards achieving the functionality of the component as per the test rather than one that does not have tests implemented for it yet. This also fits in well with the Agile methodology since it matches its iterative process and the continuous integration continuous deployment.

Some of the cons of TDD include possible complexity that may arise from implementing the tests. Setting up unit, integration and end-to-end tests may be difficult initially as it may take developers time to get used to tools that they have not used before, as opposed to manual testing which is very intuitive. It may be difficult for new developers to grasp at first and may serve as a steep learning curve for some. Next, many developers may differ in their opinions of the functionality of a certain component and therefore it may be difficult to come up with appropriate tests. If the test is to be useful, it also has to account for future problems that may arise from the system. These can be tough to predict and thereby implementation of this in the tests may not always be possible. A change in the current client situation may also force developers to reimplement or revise their tests, thereby slowing down the development process considerably, since the development cycle relies heavily on these tests. On a similar note, these tests may also have to be maintained since some may prove to be unimportant or redundant due to new libraries/future developments/other situations and therefore time spent doing this can take away from a developer’s implementation time. 
