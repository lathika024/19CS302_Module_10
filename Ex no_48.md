# EX 48 C functions to perform all basic operations in Doubly Linked List.
## DATE:
## AIM:
To write a C functions to perform all basic operations in Doubly Linked List.

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to insert a node in a linked list.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```
/*
C functions to perform all basic operations in Doubly Linked List.

struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void insert(char data) 
{ 
struct Node *n=(struct Node*)malloc(sizeof(struct Node)); 
struct Node*temp; 
if(head==NULL) 
{ 
head=n; 
n->data=data; 
n->next=NULL; 
temp=head; 
return; 
} 
 
}  
else 
{ 
while(temp->next!=NULL) 
{ 
temp=temp->next; 
} 
n->next=NULL; 
n->data=data; 
temp->next=n; 
} 
}
*/
```

## Output:

<img width="582" height="347" alt="440313963-ebb7409c-fa81-4913-beb2-f65aec1a30e7" src="https://github.com/user-attachments/assets/5b691fc5-c42a-4e10-920c-5fc74841cb3d" />


## Result:
Thus the program was executed and the output was verified successfully.
