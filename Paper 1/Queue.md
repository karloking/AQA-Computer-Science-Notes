#Queue

Queue is a First-in-First-Out Data Type where element at the front end of the queue is deleted first and items being added is inserted into the rear end

> Be able to describe and apply the following
> to linear queues, circular queues and priority
> queues:
> * add an item
> * remove an item
> * test for an empty queue
> * test for a full queue

## Operations of Queue
| Operation | Description |
| :-------: | :---------- |
| Add (Enqueue) // Insert | Adds a new item to the *rear* of the queue |
| Remove (Dequeue) // Delete | Removes an item from the *front* of the queue |

## Uses
| Uses | Description |
| :-------: | :---------- |
| Keyboard Buffer | As you press different letters from the keyboard, the order you press the different letters will output the letters in the same order.  |
| Printer Queue | When printing a document, you want to print from page 1 to N. // People sharing one printer – the first document to be sent should be printed first.|

## Linear Queue
In this queue form, elements are able to join from the rear end and exit at the front end (FIFO).

###Add an Item
```scala
IF Rear == MaxSize – 1
  PRINT “QUEUE OVERFLOW”
ELSE 
  Rear == Rear + 1
  Queue(Rear) = Item
ENDIF
```

###Remove an Item
```scala
IF front = rear
  PRINT “QUEUE EMPTY”
ELSE Front = Front + 1
  Item = Queue(Front)
  Return Item
EndIf
```

###Test If Queue is Empty
```scala
IF Front = Rear
  PRINT "QUEUE EMPTY"
ENDIF
```

###Test If Queue is Full
```scala
IF Rear = N
PRINT "QUEUE IS FULL"
```

## Circular Queue
Unlike linear queues Circular queues allow for memory to be re-used

### Add an Item
```scala 
Queue(Tail) = x
IF Queue(Tail) == Queue.length
Queue(Tail) = 1
Else Queue(Tail) = Queue(Tail) + 1
ENDIF
```

### Remove an Item
```scala
X = Front
IF Front == Queue.Length
Front= 1
ELSE 
Front = Front + 1
RETURN X
```
##Priority Queues
This is based on the order of priority of the elements in the queue. In other words, each element of this type of queue has different level of priority attached to it; e.g., high priority or low priority.

### How can it be implemented?
Using a linked list is similar to using an array; again, we can keep the list sorted or unsorted. Note that if the list is sorted we must use linear search to find the place to insert the new value, but there is no need to move old values over. Also, unless we maintain a "tail" pointer, we should keep the list in order from high to low, since removing from the front of the list can be done. Note that for a linked list we don't need the numItems field; the empty operation returns true if the list is empty.
