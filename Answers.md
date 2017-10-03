# Answers
- What difference does using a LinkedList do in TestIterator & TestList?

TestIterator
- What happens if you use list.remove(77)?
It would only remove the value 77 the first time it appears in the list, if the remove
method is not used in the while loop. Having the while loop and using a variable to keep track
of where 77 appears in the list allows one to remove 77 every time it appears in the list.

- What does .remove method do for Lists?
This method removes the element at the index position given and moves the other elements 
back one as if the element at the removed position was never there. The elements that were
further down in the list after the element that was removed now move up one in the line.

- What does list.remove(Integer.valueOf(5)) do in TestList?
This removes the value '5' from wherever it may appear in the list. The rest of the 
elements in the list that were after where the '5's were located move forward in the line.

TestPerformance
- Which of the two lists performs better as the size increases?


Link to testing data on Google Sheets:
https://docs.google.com/spreadsheets/d/1DXZykRYbJdBBi889wSGraDQ3FjDCs2Y8PNrZ59n_9Zc/edit?usp=sharing
