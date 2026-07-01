
# Learn Go with Tests

This repository documents my journey through **Learn Go with Tests**, where I'm learning the Go programming language by applying **Test-Driven Development (TDD)** from day one.

Rather than treating testing as something to add later, I'm learning Go the way it was designed to be learned—writing tests first, then implementing just enough code to make them pass, and finally refactoring while keeping everything green. The course emphasizes that Go's built-in testing support makes it an excellent language for learning TDD.

## Goals

* Learn Go fundamentals through practical exercises
* Develop a strong Test-Driven Development workflow
* Build the habit of writing tests before implementation
* Understand how tests influence API and software design
* Become comfortable with Go's standard testing tools
* Finish the entire **Learn Go with Tests** curriculum

## Learning Approach

For every chapter, I follow the Red → Green → Refactor cycle:

1. **Red** – Write a failing test.
2. **Green** – Write the simplest code that makes the test pass.
3. **Refactor** – Improve the implementation while keeping all tests passing.

This repository is intentionally organized as a learning workspace rather than a polished project. Each directory represents a concept or chapter from the course.

## Progress

* [ ] Hello, World
* [ ] Integers
* [ ] Iteration
* [ ] Arrays & Slices
* [ ] Structs, Methods & Interfaces
* [ ] Pointers & Errors
* [ ] Maps
* [ ] Dependency Injection
* [ ] Mocking
* [ ] Concurrency
* [ ] Select
* [ ] Reflection
* [ ] Sync
* [ ] Context
* [ ] Property-Based Tests
* [ ] Maths
* [ ] Files
* [ ] Templates
* [ ] Generics
* [ ] Build an Application
* [ ] Complete the full course

## Running the Tests

Run all tests:

```bash
go test ./...
```

Run tests with verbose output:

```bash
go test -v ./...
```

Run tests with coverage:

```bash
go test -cover ./...
```

## Reference

This repository follows the excellent **Learn Go with Tests** course by Chris James (quii):

* GitBook: https://quii.gitbook.io/learn-go-with-tests
* GitHub: https://github.com/quii/learn-go-with-tests

## Why I'm Doing This

My goal isn't just to learn Go syntax.

I want to build the habit of writing reliable, maintainable software by making testing part of the development process from the very beginning. By the end of this journey, I aim to be comfortable designing software with tests, not simply writing tests after the code already exists.

---

*"Code that isn't tested is code you only hope works."*
