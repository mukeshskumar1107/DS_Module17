# Ex23 Depth First Graph
## DATE: 26-03-2025
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. **Allocate Memory**: Use `malloc` to allocate memory for a new node of type `struct node`.<br/>
2. **Initialize Vertex**: Set the `vertex` field of the new node to the value `v`.<br/>
3. **Initialize Next Pointer**: Set the `next` pointer of the new node to `NULL`.<br/>
4. **Return Node**: Return the pointer to the newly created node.<br/>
5. **End Function**: Complete the function execution.  <br/>    

## Program:
```c
/*
Program to traverse the graph below in the depth first fashion
Developed by: MUKESH KUMAR S
Register Number: 212223240099 
*/

/*
#include <stdio.h>
#include <stdlib.h>

struct node {
  int vertex;
  struct node* next;
};

struct node* createNode(int v);

struct Graph {
  int numVertices;
  int* visited;

  // We need int** to store a two dimensional array.
  // Similary, we need struct node** to store an array of Linked lists
  struct node** adjLists;
};
*/

struct node *createNode(int v)
{
  // type your code here....
  struct node *newNode = malloc(sizeof(struct node *));
  newNode->vertex = v;
  newNode->next = 0;
  return newNode;
}
```

## Output:
<img width="534" height="814" alt="image" src="https://github.com/user-attachments/assets/c3293db8-c167-491e-95ea-9207aea0f705" />



## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
