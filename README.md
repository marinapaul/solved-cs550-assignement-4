Download Link: https://assignmentchef.com/product/solved-cs550-assignement-4
<br>









Part I







<ol>

 <li>Write a constraint satisfaction problem specification for a 4 color map problem with colors: pink, green, blue, and red as per the following map:</li>

</ol>




<ol start="2">

 <li>Given the vehicle assembly example given in slides 7-9, draw the constraint graph.</li>

 <li>Explain in your own words how conflict-directed backjumping works. As always, be very careful to avoid plagiarizing.</li>

</ol>




Part II:  Programming Assignment




The code package for this assignment on Blackboard contains a partially implemented constraint satisfaction problem class for solving Sudoku puzzles.  The sudoku module implements the class Sudoku that is derived from a CSP class (both in module csp_lib).  The code and comments explain the data structures that are used and contain a sample instantiation of a Sudoku puzzle.  The module also provides two sample puzzles, one that can be solved with constraint satisfaction, the other without.




There is no work to do in the sudoku and csp modules other than to read them and understand how they work.  The task in this assignment is to implement AC3 constraint propagation, backtracking search, and a driver.  Template functions are provided for AC3 and backtracking_search in modules constraint_prop and backtrack.  Both of these operate on a sudoku puzzle and update the current assignments.  When calling your




csp_lib.backtrack_util).




Your driver program should create both the easy and hard sudoku problems and then solve them.





