# queen-implementation-in-c-plus-plusQueue is a linear data structure in which elements can be inserted only from one side of the list called rear, and the elements can be deleted only from the other side called the front. The queue data structure follows the FIFO (First In First Out) principle, i.e. the element inserted at first in the list, is the first element to be removed from the list. The insertion of an element in a queue is called an enqueue operation and the deletion of an element is called a dequeue operation. Circular Queue is just a variation of the linear queue in which front and rear-end are connected to each other to optimize the space wastage of the Linear queue and make it efficient.

Algorithm:
Step 1: Initialization

Define a constant SIZE as the maximum capacity of the queue.

Create a class Queue with:

An integer array arr[SIZE] to store queue elements.

Two integer variables front and rear initialized to -1.

Step 2: Enqueue Operation (Insert Element)

Check for Overflow:

If rear == SIZE - 1, print "Queue Overflow!" and exit.

Insert First Element:

If front == -1, set front = 0.

Insert Element:

Increment rear and assign arr[rear] = value.

Print that the value has been inserted.

Step 3: Dequeue Operation (Remove Element)

Check for Underflow:

If front == -1 or front > rear, print "Queue Underflow!" and exit.

Remove Element:

Print the element at arr[front] as removed.

Increment front.

Step 4: Display Queue Elements

Check if Queue is Empty:

If front == -1 or front > rear, print "Queue is empty." and exit.

Print Elements:

Loop from front to rear and print each element in arr.

Step 5: Main Function Execution

Create a Queue object q.

Perform the following operations:

enqueue(10)

enqueue(20)

enqueue(30)

display()

dequeue()

display()

enqueue(40)

display()

Step 6: End

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Contributors
1
@TarushiV26
TarushiV26 Tarushi Verma
Languages
C++
100.0%
Footer
© 2026 Git
