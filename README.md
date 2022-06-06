# Code Smells

## Learning Goals

- Give an overview of various code smells

## Introduction to Code Smells

A "code smell" is something that should give you pause and make you stop and ask
the question: is this right? Because programming is always about compromise,
seeing something that looks potentially less than ideal does not necessarily
mean you have to fix it right away - it might be something you queue up for
later (technical debt), it might be something you decide is an acceptable
compromise given the current system conditions. Or it may be something that
should be cleaned up right away because it will have an immediate impact on the
ability to maintain, scale or test the system.

There are multiple categories of code smells we're going to cover in this
section:

1. Bloaters - this is code that (eventually, and sometimes slowly) grows to
   proportions that make it difficult to understand and therefore to maintain
2. Object Orientation Abusers - when OO principles are applied incorrectly
   and/or only partially
3. Change Preventers - these are patterns that make it more difficult to change
   a specific piece of code because other areas of your code would also have to
   be changed as a result
4. Dispensables - code that is not necessary in order for your functionality to
   work and that, if removed, would make your code easier to understand and/or
   more efficient
5. Couplers - code that is too tightly coupled with one another
