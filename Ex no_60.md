# EX 60 C function to find the peek element of the queue using linked list.
## DATE:
## AIM:
To write a C function to find the peek element of the queue using linked list.

## Algorithm
1. Start
2. Check if the queue is empty (front == NULL):
  If empty, print "Queue is empty" and exit.
3. Otherwise, return the data of the front node.
4. End 

## Program:
```
struct Node
{
   int data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void peek()
{
    printf("%c",front->data);
}
```

## Output:

<img width="592" height="573" alt="image" src="https://github.com/user-attachments/assets/a449aa6f-f1c0-40db-9135-74eeb6dca62b" />


## Result:
Thus the program was executed and the output was verified successfully.
