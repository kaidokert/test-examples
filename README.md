[![Build Status](https://travis-ci.org/tkh/test-examples.svg?branch=master)](https://travis-ci.org/tkh/test-examples) [![CircleCI](https://circleci.com/gh/tkh/test-examples.svg?style=svg)](https://circleci.com/gh/tkh/test-examples) [ ![Codeship Status for tkh/test-examples](https://app.codeship.com/projects/c3f85ce0-e33e-0134-12a6-3ae0b9756505/status?branch=master)](https://app.codeship.com/projects/205976) [![Code Climate](https://codeclimate.com/github/tkh/test-examples/badges/gpa.svg)](https://codeclimate.com/github/tkh/test-examples)

# Test examples S
A repository of some simple testing examples to demo various test cases and
usage of mocking.

## Set up and requirements
Create a virtual environment and install from `requirements.txt`:

    pip install -U -r requirements.txt

Both Python 2 and 3 should work fine for these examples. `mock` is installed as
a requirement rather than standard library to run on Python 2.

## Running tests from console
Helper script:

    ./run.sh

Manually in bash:

    PYTHONPATH=. py.test

Using tox:

    tox

## Running independently or from an IDE
Set your `PYTHONPATH` environment variable to the root of the repository.
