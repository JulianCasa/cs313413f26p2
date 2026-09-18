Project 2 Report
//TestList.java TODO questions

 list.remove(5); // TODO Question: What does this method do?
        The method list.remove(5) removes the value that exists at index 5 of the ArrayList

list.remove(Integer.valueOf(5)); // TODO Question: What does this one do?
        This method searches the list for the Integer value 5 and removes it regardless of its position

//TestIterator TODO Questions
// TODO Question: Also try with a LinkedList - does it make any difference?//
        There is very little difference when running the program using arraylist versus linked list.
        There was also no issue in the methods, most likely because both classes implement the list
        interface

i.remove(); // TODO Question: What happens if you use list.remove(Integer.valueOf(77))?
        If the method is called within the provided while loop, the program breaks because all
        the instances of the integer 77 are removed in the first loop. If implemented ouyside a loop
        it removes all instances of 77 at once
