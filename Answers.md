TestList Class
1. also try with a LinkedList - does it make any difference?
    - No, it does not really make any difference. Both arraylist and linked list are dynamic data structures
    and run at linear time when iterating through the list.
2. list.remove(5); // what does this method do?
    - Removes the element at the specified position(index 5) in the list
3. list.remove(Integer.valueOf(5)); // what does this one do?
    - Remove the value of 5 in the list.

TestIterator
1. What happens if you use list.remove(Integer.valueOf(77))?
   - It will remove the value of 77 from the list.

TestPerformance
Which of the two lists performs better as the size increases?
The arraylist performs better as the size increases.

n = 10
TestPerformance = 129ms
  testArrayListAccess = 10ms
  testPerformance.testLinkedListAddRemove = 43ms
  testPerformance.testLinkedListAccess = 14ms
  testPerformance.testArrayListAddRemove = 62ms

n = 100
TestPerformance = 192ms
TestPerformance.testArrayListAccess = 10ms
TestPerformance.testLinkedListAddRemove = 40ms
TestPerformance.testLinkedListAccess = 20ms
TestPerformance.testArrayListAddRemove = 122ms

n = 1000
TestPerformance = 895ms
TestPerformance.testArrayListAccess = 11ms
TestPerformance.testLinkedListAddRemove = 50ms
TestPerformance.testLinkedListAccess = 329ms
TestPerformance.testArrayListAddRemove = 505ms

n = 10000
TestPerformance = 8s 330ms
TestPerformance.testArrayListAccess = 21ms
TestPerformance.testLinkedListAddRemove = 39ms
TestPerformance.testLinkedListAccess = 4s 294ms
TestPerformance.testArrayListAddRemove = 3s 976ms