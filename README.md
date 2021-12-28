# Office-Hour-Simulation
Prompt: You are tasked with helping your professor schedule his office hours. The professor is teaching 2 classes this semester, class A and class B, and is holding shared office hours for both classes in his office. The professor can have a large number of students showing up for his office hours, so he decides to impose several restrictions. 
# Restrictions
•	No more than 3 students can be inside the office at the same time, if the office is full and new students arrive, they will have to wait outside
•	Only students from the same class can be in the office at the same time
•	After helping 10 students the professor needs to take a break so no new students will be allowed to enter the office till the break is over
•	To ensure fairness the professor will help a student from the other class if he helps 5 consecutive students from a single class
•	A student will not be forced to wait assuming the criteria for entering are fulfilled i.e. the professor os not on break, they are not the 6th consecutive student, they are in the same class as the other students in the office, etc.
•	The program will not deadlock
# Functions
•	Multithreading
•	Parallel programming
•	Concurrency controls
# Program Execution
•	As the program uses pthread.h make sure to add the -lpthread option during compilation
•	Also I have included several test cases in the test_cases folder to run with the program 
