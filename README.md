# DSA-Assignment-5pt1
TXST: 3358 Data Structures and Algorithms-Assignment 5pt1.
Grade: 100%

Assignment Description:
This part of the assignment aims at providing you with a programming exercise on the processing of a (singly-)linked list of the type illustrated in class ‒ in particular, how to manipulate a given list in some specified way.
You are to work on the Supplied Files to develop a linked-list processing function PropTarget that receives two arguments, namely,
(1) the head pointer of a given singly-linked list
(2) a given target value (the type of which matches that of the data field of a node of the given linked list)
and processes the linked list as follows:
●	If target cannot be found in the given list, a new node containing target (as data) is appended to the list (as the new tail node).
  ►	This includes the case where the given list is empty, whereby the new tail node appended also becomes the (new) head node.
●	If target appears one or more times in the given list, the target-containing nodes are to be moved so that they all appear together as the front portion of the list.
  ►	The order in which the non-target-containing nodes originally (upon entering the function) appear in the given list must be preserved.
  ►	(NOTE: Order in which the target-containing nodes originally appear does not have to be preserved; they just have to appear together as the front portion of the list.)
