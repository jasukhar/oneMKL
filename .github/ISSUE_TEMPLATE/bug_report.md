---
name: Report a bug or a performance issue
about: Use this template to report unexpected behavior
title: ''
labels: ''
assignees: ''
---

# Summary
Provide a short summary of the issue. Sections below provide guidance on what
factors are considered important to reproduce an issue.

# Version
Report oneMKL version and githash.

# Environment
oneMKL works with multiple HW and backend libraries and also depending on the compiler and build environment. Include
the following information to help reproduce the issue:
* HW you use
* Backend library version
* OS name and version 
* Compiler version 
* CMake output log

# Steps to reproduce
Please check that the issue is reproducible with the latest revision on
master. Include all the steps to reproduce the issue. 

# Observed behavior
Document behavior you observe. For performance defects, like performance
regressions or a function being slow, provide a log including output generated
by your application. 

# Expected behavior
Document behavior you expect.