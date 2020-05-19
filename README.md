MECHENG 313 Assignment 2
Authors: Reuben O'Brien and Kuan Chen

Real-time systems (also known as “cyber-physical” systems) are usually comprised of
three parts: a controlled object, a real-time computer, and a user interface to that
computer1. There are several functional requirements of any real-time system: A real-time
computer must inform the user of its state and the state of the controlled object, thereby
assisting the user in the decision-making process. Data collection -- another requirement
-- logs interactions between user and real-time computer, as well as changes in the state
of the computer.
In this assignment, you will develop a C# application that implements finite-state
machines, data logging, and threading, as well as a simple console-based user interface.

This project is broken up in to three tasks.
1. Implementing a class for finite-state tables
2. Programming a finite-state machine
3. Programming concurrent, dependent, synchronous finite-state
machines