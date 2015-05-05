# Superrepository for _math_ repository

This repository is used to run the unit tests for the _math_ repository.
It contains the submodules that the _math_ repository requires, with commits that are compatible with each other.
The Jamroot file tells Boost.Build how to test this repository when one says:

    bjam test

[![Build Status](https://travis-ci.org/rogiervd/math-test.svg?branch=master)](https://travis-ci.org/rogiervd/math-test)
