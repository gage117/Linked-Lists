# Linked-Lists

## Methods

### Both file's List classes have:
- find(item): Takes a string for argument. Returns a specified item in a list. 
- findBefore(item): Takes a string for argument. Returns the item before a specified item in a list.
- findAtIndex(index): Takes an integer for argument. Returns the item at a specified index in a list.
- insertFirst(item): Takes a string for argument. Inserts item into beginning of list.
- insertLast(item): Takes a string for argument. Inserts item into end of list.
- insertBefore(item, beforeItem): Takes strings for arguments. Inserts item into list before specified item.
- insertAfter(item, afterItem): Takes strings for arguments. Inserts item into list after specified item.
- insertAt(item, index): Takes a string and an integer for arguments. Inserts item into list at the specified index.

### Both files also have functions that work with the LinkedList classes:
- size(linkedList): Takes a linked list as an argument. Returns the size of the list.
- display(linkedList): Takes a linked list as an argument. Returns a string indicating the size of the list and how the list items are linked together from first to last.
- isEmpty(linkedList): Takes a linked list as an argument. Returns a string indicating whether the list is empty or not. If not, also provides how many items are in the list.
- findLast(linkedList): Takes a linked list as an argument. Returns the last item in the list.
- reverseList(linkedList): Takes a linked list as an argument. Returns the linked list in reverse order.

### Additional functions in each file:
singlyLinkedList.js:
- findPrevious(item): Takes an item as an argument. Returns the item in the list before the specified item.
- reverseSecondHalf(linkedList): Takes a linked list as an argument. If list length is odd, second half is half-length rounded down (i.e.: listLength = 5 means secondHalf is 2 items, or 2.5 rounded down). Returns the linked list with only the second half reversed.
- thirdFromEnd(linkedList): Takes a linked list as an argument. Returns item three positions in from the last.
- middleOfList(linkedList): Takes a linked list as an argument. Returns the middle item if linked list has odd number of items, or both middle items if even (e.g.: providing linkedList = 1, 2, 3, 4, 5, 6 returns both 3 and 4.
- cycleInList(linkedList): Takes a linked list as an argument. Returns a string indicating whether or not there is a cycle in the list (a node pointing to an earlier node, creating a loop).

doublyLinkedList.js:
- displayReverse(linkedList): Takes a linked list as an argument. Returns a string indicating the size of the list and how the list items are linked together from last to first.
