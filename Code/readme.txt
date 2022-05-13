Files and their purposes are listed in this document. 
    
dim.docx

It contains the dimensions of the problem.
1st line contains the number of Classes(C).
2nd line contains the number of teachers(T).
3rd line contains number of rooms(R).

matrix.docx

First k rows of the file indicate the number of times each class-teacher pair is to meet each other in room floor(k/C) across P periods.
where floor is greatest integer fumction.

UCTP.cpp

It contains the Code to solve the problem. It uses IBM ILOG CPLEX Optimization Studio to solve the integer programming formulation of the problem.

outputk.txt

Has the output for hdttk where k lies from 4 to 8 in sentence format for easier understanding of the allotment. 
