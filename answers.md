# CMPS 2200 Assignment 3
## Answers

**Name:** Rhegan Barrett


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**
Both the work and span are O(n) because this is an iterative solution that goes through each element in the list.



- **d.**
The work of map, reduce, and scan are all O(n) so the work of the solution is also O(n). However, they each have different spans. Reduce and scan have the higher asymptotic bounds of O(log n), so the span of the solution is O(log n).




- **f.**
The recurrence for work of the divide and conquer solution is W(n) = 2W(n/2) + 1 because the list is being split up into two parts which get divided in half each time and the combining step is constant. The big O of the work is O(n) because it's leaf dominated. The recurrence for the span is S(n) = S(n/2) + 1, and the big O is O(log n) because it's a balanced tree.