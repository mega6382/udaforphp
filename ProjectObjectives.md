# Project Goals #

UDA4PHP is meant to be a library that provides a uniform interface for accessing database systems from PHP. The idea is to create a core library to which DBMS vendors can then interface through an arbitrary number of drivers, thus providing a single entry point for all data access.

The goal of UDA4PHP is _not_ to provide database abstraction, but to provide database access abstraction.

# Roadmap to Version 1.0 #

There are several steps that we have identified as a roadmap to completing the library:

  1. **Agree on a CLA** —this is currently [in progress](ClaDiscussion.md).
  1. **Agree on functionality constraints** —we need to decide _what_ we want the library to do.
  1. **Design the library** —based on our technical objectives, we will design the overall library.
  1. **Write the library** —clearly the easiest part :-)
  1. **Write a driver** —we should probably decide on a reference implementation for a driver
  1. **Write the documentation** —for both driver designers and users