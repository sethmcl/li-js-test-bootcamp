<link href="https://raw.github.com/sethmcl/li-js-test-bootcamp/master/css/markdown.css" rel="stylesheet"></link>

#JavaScript Unit Testing Bootcamp
Test Driven Development with JavaScript
Purpose
To convince you to that making automated testing part of your development workflow is worth it

```javascript
function() { }
```

What does TDD mean to me?
 - Not about neccsarily writing tests first

 - It's about automating that which would be otherwise manual and time consuming
 - It's about writing code that's testable
 - It's about writing tests that clearly specify what the code needs to achieve

The bottom line 
TDD helps you design better code structures
Automated tests for JavaScript are vital due to its dynamic nature

But isn't this extra work?
In the long run. No.

Let's write some tests
Requirement: Test support of Object.keys in desktop and mobile browsers

// Setup
var testObject = {
  c: 'Value c'
  5: 
  a: 'Value a',
  b: 'Value b',
}

// TDD forces into creating a strategy for testing.
// Makes us think about 'what' we are really testing
// Provides reusability

// Exists?
typeof Object.keys === 'function'


Let's write some tests
 - It's not like you don't spend time testing your code?
 - The lifespan of your code ultimately dictates the value of automated tests
 - A Test-Driven approach helps you write testable, modular and focussed code

But now I have two code bases to maintain? How is that not extra work?
 - When was the last time you created comprehensive documentation for the type of code you write everyday?
 - Think of your automated tests as your documentation phase?
 - It also works like the Rubber Ducking problem solving phenomena
 - You just get testing for free

Tests and ROI
 - Instant gratification through manual testing lasts for an instant
 - Automated tests last longer
 - Have you ever refactored any code? Automated tests allow more aggressive and efficient refactoring.

It is not a silver bullet though
 - Like any codebase, automated tests can have bugs
 - Even a comprehensive set of tests can allow new bugs and/or regressions to slip through
 - But this is not about silver bullets. This is about building solid testable code. TDD helps!

Still not convinced?
Even if you don't write tests, write the specs without the actual tests
You'll still get the benefits of documenting the tasks your code performs
It should influence the code you're writing to make it more testable
The actual tests can be written later
