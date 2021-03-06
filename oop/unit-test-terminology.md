# Terminology Used by Unit Testing Frameworks

(taken from: https://docs.python.org/3/library/unittest.html)



**Test Fixture**

A *test fixture* represents the preparation needed to perform one or more tests, and any associate cleanup actions. This may involve, for example, creating temporary or proxy databases, directories, or starting a server process.

**Test Case**

A *test case* is the individual unit of testing. It checks for a specific response to a particular set of inputs. [`unittest`](https://docs.python.org/3/library/unittest.html#module-unittest) provides a base class, [`TestCase`](https://docs.python.org/3/library/unittest.html#unittest.TestCase), which may be used to create new test cases.

**Test Suite**

A *test suite* is a collection of test cases, test suites, or both. It is used to aggregate tests that should be executed together.

**Test Runner**

A *test runner* is a component which orchestrates the execution of tests and provides the outcome to the user. The runner may use a graphical interface, a textual interface, or return a special value to indicate the results of executing the tests.