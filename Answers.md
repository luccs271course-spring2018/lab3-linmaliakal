# Answers
TestIterator & TestList
- What difference does using a `LinkedList` v. a `List` have?  
Using a LinkedList allows the user to add and remove elements anywhere in the list in
constant time, making it easier and faster to add and remove frequently if needed. Using
an `ArrayList/List` must operate in linear time if using the add and remove methods since they
would need a loop to move the elements based on what is added/removed. 

TestIterator
- What happens if you use `list.remove(77)`?  
It would only remove the value 77 the first time it appears in the list, if the remove
method is not used in the while loop. Having the while loop and using a variable to keep track
of where 77 appears in the list allows one to remove 77 every time it appears in the list.

TestList
- What does .remove method do for Lists (`list.remove(5)`)?  
This method removes the element at the index position given and moves the other elements 
back one as if the element at the removed position was never there. The elements that were
further down in the list after the element that was removed now move up one in the line.
- What does `list.remove(Integer.valueOf(5))` do?  
This removes the value '5' from wherever it may appear in the list. The rest of the 
elements in the list that were after where the '5's were located move forward in the line.

TestPerformance
- Which of the two lists performs better as the size increases?  


Link to testing data on Google Sheets:  
https://docs.google.com/spreadsheets/d/1DXZykRYbJdBBi889wSGraDQ3FjDCs2Y8PNrZ59n_9Zc/edit?usp=sharing
