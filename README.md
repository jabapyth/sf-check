sf-check
========

A grading system for Software Foundations

There are two classes of exercises in Software Foundations.

The first class provides boilerplate definitions/theorems/etc. that must be filled in by the student. 
These exercises are graded automatically by running coqc. A problem will receive credit only if all 
the parts are accepted by Coq.

The second class needs to be graded manually. The parts component is a list of all problem parts named 
(on top of mentioned) in the problem description. The entire problem will not be flagged for grading 
unless all the parts are defined in the Coq file.

