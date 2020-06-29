# JUnits-tutorial

JUnits course on udemy:

https://www.udemy.com/course/junit-tutorial-for-beginners-with-java-examples/

Testing public and void methods
https://examples.javacodegeeks.com/core-java/junit/junit-test-void-method-example/

for Junit, assertions will be like
assertEquals("expected", "actual");

@Before, @Test, @Test(expected = Exception-name.class) (incase expecting any exception), @After

if we are writing Junits using Spring framework then that test class should annotate like below
@RunWith(SpringJunit4ClassRunner.class)

we can mock private and static and void methods by using PowerMockito
To test the class with PowerMockito, the test class should be annotated like below
@RunWith(PowerMockRunner.class)

https://www.softwaretestinghelp.com/mock-private-static-void-methods-mockito/
