# CS300_ABCU_Course_Program

The purpose of this program is to take course data from a CSV file and structure it in a way that allows for efficient search, insertion, and traversal of the data. The 
structure that I chose to implement for the program is a binary search tree. I selected this data structure because it is relatively simple to implement while still 
providing efficient searches and superior traversal and output (when it is necessary to do so in order). This is due to the structure of the data within the tree, which 
is ordered. Thus, outputting each node in order is equivalent to outputting each node. Using other data structures, it would be necessary to first sort the data. While 
hash tables allow for faster searches, given that course numbers would be mapped to the respective course data, this speed is not entirely necessary for this purpose of 
this program. If the speed of the program was a more significant factor, I may have selected this data structure. The only roadblock that I encountered during the 
development of this project was a strange issue related to the output of courses that have no prerequisites courses. When outputting the prerequisites for these courses, 
they should simply be listed as 'none'. Instead, the course name is listed as its own prerequisite. Unfortunately, the source of this bug remains unknown.
