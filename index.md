---
site: sandpaper::sandpaper_site
---

This is a new lesson built with [The Carpentries Workbench](https://carpentries.github.io/sandpaper-docs/index.html). 

---

The HPC Advanced User Software Carpentry lesson is aimed at researchers with
some background in using scientific computing.
This lesson will teach scientists to understand and deal with performance issues
that arise when moving from a personal computer
to a High-Performance Computing (HPC) environment (a SuperComputer).
The basic concepts
that affect performance are covered in a general manner, then a survey of
the capabilities and performance of many languages commonly used in
scientific computations are discussed along with example codes illustrating
the performance concerns of each language.  Each person who completes this lesson
should have a good general overview of what each computer language can
do and what performance bottlenecks to avoid.

## Prerequisites

Each user must begin with some knowledge of Linux and at least one
of the languages that this lesson covers (Python, R, C/C++, Fortran, Matlab).
The examples in the first part of this lesson are available in
Python, R, C/C++, and Fortran with Matlab versions still needed.
Each user may also need to know how to run
jobs in an HPC environment.  These prerequisites may all be covered by
having an HPC Unix Shell carpentry lesson taught right before this one.


:::::::::: instructor

If there is no preceeding HPC Unix Shell lesson presented then there
should be a more in depth discussion of what an HPC system is and how
it is used.

 * One or more head nodes where you log in and do code setup.
 * Many compute nodes where the jobs actually get run, each having multiple cores.
 * The Linux operating system with a command line interface (CLI).
 * Possibly a more graphical interface like OnDemand.
 * A batch queue system that schedules jobs to compute nodes.
 * A common file system available on all head nodes and compute nodes.
 * Possibly some GPU cards for accelerating some scientific codes.
 * A module system for loading compilers and scientific applications.

The user logs into a head node, edits code, input files, and job scripts,
then submits the job script to the batch queue where it gets scheduled
to run on the compute nodes when there is space available.

:::::::::::::::::::::

