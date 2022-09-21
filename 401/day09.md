# Stack and Queues

### What's the difference between Stack and Queue?

| Stack | Queue |
| ----------- | ----------- |
| Its based on **LIFO** (Last In First Out) | Its based on **FIFO** (First In First Out) |
| Insertion Operation is called **Push Operation** | Insertion Operation is called **Enqueue Operation** |
| Deletion Operation is called **Pop Operation** | Deletion Operation is called **Dequeue Operation** |
| Push and Pop Operation takes place from **one end** of the stack | Enqueue and Dequeue Operation takes place from a **different end** of the queue |
| The most accessible element is called **Top** and the least accessible is called the **Bottom** of the stack | The insertion end is called **Rear End** and the deletion end is called the **Front End**  |
| Only **one pointer** is used for performing operations  | **Two pointers** are used to perform operations |
| Empty condition is checked using `Top==-1` | Empty condition is checked using `Front==-1 OR Front==Rear+1` |
| Full condition is checked using `Top==Max-1` | Full condition is checked using `Rear==Max-1` |

### What is Stacks and how to use it?
- Stack is a **linear data structure**, there is only one sequence to access the element.
- Stack **insert** the element from one end with push operation and delete the element from the same end using pop operation.
- Stack follows the **LIFO (Last In First Out)** principle
- Stack stores the elements of the same **data type** only

Condition to Check if Stack is Empty:
```
int Empty() 
{ 
if(top==-1) 
return 1; 
else return 0; 
}
```

Condition to Check if Stack is Full
```
int Full()
{
    if(top==MAX-1)
        return 1;
    else
        return 0;
}
```


### What is Queue?
- Queue is a **linear data structure**
- Queue **insert** the element from one side of the list and delete the element from the other side of the list.
- Queue data structure follows the **FIFO(First In First Out)** principle
- Queue stores the elements of the same **data type** only
----

### Which 3 things had you heard about previously and now have better clarity on? 
I heard about Stack and Queue

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
Stack, Queue and how to write it in code

### What are you most excited about trying to implement or see how it works? Preparation Materials
How to use Stack and Queue in a  real problem

