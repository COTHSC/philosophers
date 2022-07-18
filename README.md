# philosophers

## ⚠️ Disclaimer ⚠️

this code was written as part of a school project. The main focus was to learn, the code quality may be uneven and there are definitely some rough edges. Given the nature of the projects, and the diminishing returns of polishing up a project when it comes to learning opportunities, I do not intend to go back over this code.

## Subject:

The aim of this project is to solve the dining philosophers problem using c and mutex’s, each philosopher is a thread, and each fork is a mutex. As a result philosophers cannot duplicate forks and must wait for each other to be done “eating”. Once a philosopher cannot eat for a set amount of time given as an argument, it dies and the simulation ends.
