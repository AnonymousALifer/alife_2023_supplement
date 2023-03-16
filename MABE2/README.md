# MABE

Version 2 of the [Modular Agent-Based Evolver framework](https://github.com/Hintzelab/MABE).

MABE is a software framework deigned to easily build and customize software for
evolutionary computation or artificial life.  The resulting systems should be
useful for studying evolutionary dynamics, solving complex problems, comparing
evolving systems, or exploring the open-ended power of evolution.

MABE version 2.0 is being re-built from scratch, using the [Empirical library](https://github.com/devosoft/Empirical).
Our goal is to allow for more modular control, flexible agents, faster run times
and portability to the web.

## ALife 2023 note
Typically, MABE2 is its own GitHub repo, and as such we do not provide the in-depth breakdown of every subdirectory like we would with other directories in this repository. 
If you are interested in MABE, here are the three main directories to check out: 
- `./source/` - All the source code (including the Empirical dependency)
- `./build/` - Use the Makefile to build MABE2, also typically where the program is executed (but not in the ALife 2023 work, it gets copied to a scratch directory). 
- `./setttings/` - Example configuration scripts, typically much simpler than those used in the ALife 2023 work.
