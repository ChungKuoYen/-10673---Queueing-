# -10673---Queueing-
Description

You need to write a program to simulate a queue of names.  Each name is a string consisting of English letters only.  There are three operations:

1.         “Push [name]”, which means to enque name in the queue.

2.         “Pop”, which means to deque. If the queue is empty, this operation takes no effect.

3.         “Front”, which means to print out the name in the front of queue. If the queue is empty, print "empty" (without quotes).

 

Case1 : #operation <= 10^2, There will be no "Pop" and "Front" command when queue is empty.
Case2 : #operation <= 10^3. There will be no "Pop" and "Front" command when queue is empty.
Case3 : #operation <= 10^4.
Case4 : #operation <= 10^6.
Input

Each line contains one of the following operations. “Push [name]” (without quotes), “Pop” (without quotes), “Front”(without quotes). The length of each name is at most 10.
Output

For each “Front” operation, print out the name in the front of the queue.
