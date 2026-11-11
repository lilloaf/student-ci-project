# student-ci-project

A small Python project used to demonstrate a Jenkins CI pipeline (CMSC 426, In-Class Activity 3).

## Contents
- `app.py`: sample application with an `add_numbers` function
- `tests/test_app.py`: unit tests for `add_numbers`

## Run the application
    python3 app.py

## Run the tests
    python3 -m unittest discover -s tests -t .

## CI
Jenkins job `Student-CI-Project` pulls this repository, runs the tests, and marks the build failed if any test fails.
Demo: CI pipeline verified.
