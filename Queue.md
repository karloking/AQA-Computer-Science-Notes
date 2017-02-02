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

