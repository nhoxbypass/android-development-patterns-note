# Testing

Testing your app is an integral part of the app development process. By running tests against your app consistently, you can verify your app's correctness, functional behavior, and usability before you release it publicly.

I’ve come to love testing so much that I feel uncomfortable writing code in a codebase without tests. If your entire application does one thing (like school projects), then testing manually is still okay. But what happens when there are 100 different things the application does? 

**Think testing as documentation. It’s documentation for my assumptions about the code. Tests tell me how I (or the person before me) expect the code to work, and where all they expect things to go wrong.**

Testing also provides you with the following advantages:

* Rapid feedback on failures.
* Early failure detection in the development cycle.
* Safer code refactoring, letting you optimize code without worrying about regressions.
* Stable development velocity, helping you minimize technical debt.

## Fundamentals of Testing

* [Iterative development workflow (TDD)](testing_fundamentals.md#iterative-development-workflow-(tdd))
* [Testing Pyramid](testing_fundamentals.md#testing-pyramid)
* [Threads in tests](testing_fundamentals.md#threads-in-tests)
* [Write small tests](testing_fundamentals.md#write-small-tests)
* [Instrumented tests](testing_fundamentals.md#instrumented-tests)
* [Write medium tests](testing_fundamentals.md#write-menidum-tests)
* [Write large tests](testing_fundamentals.md#write-large-tests)
* [Create more readable assertions](testing_fundamentals.md#create-more-readable-assertions)


## JUnit4 rules with AndroidX Test

AndroidX Test includes a set of JUnit rules to be used with the `AndroidJUnitRunner`. JUnit rules provide more flexibility and reduce the boilerplate code required in tests.

* [ActivityTestRule](junit_rules_with_androidx_test.md#activitytestrule)


## Testing terminology

* [Test coverage](terminology.md#test-coverage)
* [Test Driven Development (TDD)](terminology.md#test-driven-development-tdd)
* [Test Doubles](terminology.md#test-doubles)
