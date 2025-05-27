# EX 60 C function to find the peek element of the queue using linked list.
## DATE:20/5/25
## AIM:
To write a C function to find the peek element of the queue using linked list.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a functions to perform enqueue, dequeue,peek,display, in Queue using linked 
list. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End 

## Program:
```
struct Node
{
   char data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void peek()
{
    if(front!=0)
    {
        printf("%c",front->data);
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/825d5bb8-f40d-48ef-9da1-430329c0fef2)

## Result:
Thus the program was executed and the output was verified successfully.
