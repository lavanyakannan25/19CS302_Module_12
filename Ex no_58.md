# EX 58 C Function to display queue elements using Linked List.(use integer data in the queue)
## DATE:
## AIM:
To write a C Function to display queue elements using Linked List.

## Algorithm
1. Start
2. Define a structure Node with two fields:
   data (integer type)
   next (pointer to the next node)
3. Initialize front and rear pointers:
  front points to the first node in the queue
  rear points to the last node in the queue
4. Check if front is NULL:
  If NULL, print "Queue is empty" and exit.
5. Otherwise, create a temporary pointer temp pointing to front.
6. Loop through the queue:
  Print temp->data.
  Move temp to temp->next.
7. Continue until temp becomes NULL.
8. End   

## Program:
```
struct Node
{
   float data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void display()
{
    struct Node *ptr;
    ptr=front;
    if(front==NULL)
    {
        printf("queue is empty");
        
    }
    else
    {printf("Queue elements:\n");
    while(ptr!=0)
    {
        printf("%.3f\n",ptr->data);
        ptr=ptr->next;
    }}
}
```

## Output:

<img width="888" height="541" alt="image" src="https://github.com/user-attachments/assets/b39fae97-b099-47f2-a62a-c5a0b9f2af50" />


## Result:
Thus the program was executed and the output was verified successfully.
