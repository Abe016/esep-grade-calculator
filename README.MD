# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

It supports three grade categories:
- Assignments
- Exams
- Essays

The calculator computes the weighted average of the grade categories and converts the final numerical grade to a letter grade.

## Runtime requirements:

Golang 1.24+

## Unit Tests

To run unit tests:
```
cd grade-calculator/
go test ./...
```

To run unit tests with code coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```
