# EX 56 C function to display stack elements using Linked List.(store integer data in stack) .
## DATE:
## AIM:
To write a C function to display stack elements using Linked List.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to display stack elements using linked list.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End  

## Program:
```
Struct Node 
{ 
float data; 
struct Node *next; 
}*head; 
void display() 
{ 
struct Node *temp= head; 
while(temp!=NULL) 
{ 
printf("%.2f\n",temp->data); 
temp=temp->next; 
} 
 
}
```

## Output:
<img width="769" height="500" alt="image" src="https://github.com/user-attachments/assets/523de64a-b9ef-4c00-877a-e3d7863d0395" />



## Result:
Thus the program was executed and the output was verified successfully.
