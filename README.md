# Cellular-Automaton
Cellular automaton using rule 30 and Conway's automaton. 

This is a parallel program that uses OPENMP. At first the program separates the threads in two teams the first one will handle the rule 30 automaton which will process a text line with N bytes. The result of it is passed to the queue so that it feeds the team two which is in charge of the Conway's automaton. The users decides how many bytes are going to be processed per line as well as the amount of iterations the program will run. For space matters the Conway's automaton will only create a file with the last 10 iterations.

Topics
-Parallel Programming
-Automatons 
