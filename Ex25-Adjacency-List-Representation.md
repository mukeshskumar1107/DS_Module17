# Ex25 Adjacency List Representation
## DATE: 26-03-2025
## AIM:
To write a C program to represent the given graph using the adjacency list.

## Algorithm
1. Initialize variables: 
   - Declare `n` and `i` as integers.<br>
   
2. Read the number of vertices: 
   - Use `scanf` to read the value of `N` (number of vertices).<br>
   - Use `scanf` to read the value of `n` (number of edges).<br>
   
3. Input edges of the graph: 
   - Declare an array `edges` of type `struct Edge` with size `n`.<br>
   - For each edge `i` from `0` to `n-1`:<br>
     - Use `scanf` to read the source vertex `edges[i].src`.<br>
     - Use `scanf` to read the destination vertex `edges[i].dest`.<br>
   
4. Construct the graph: 
   - Call `createGraph(edges, n)` to create a graph from the given edges and store the result in `graph`.<br>
   
5. Print the graph: 
   - Call `printGraph(graph)` to print the adjacency list representation of the graph.<br>
   
6. End the program: 
   - Return `0` to indicate successful completion.<br>  

## Program:
```c
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: MUKESH KUMAR S
RegisterNumber: 212223240099
*/

/*#include <stdio.h>
#include <stdlib.h>

// Define the maximum number of vertices in the graph
int N;

// Data structure to store a graph object
struct Graph
{
    // An array of pointers to Node to represent an adjacency list
    struct Node* head[10];
};

// Data structure to store adjacency list nodes of the graph
struct Node
{
    int dest;
    struct Node* next;
};

// Data structure to store a graph edge
struct Edge {
    int src, dest;

} *edges[50];
*/

int main(void)
{
  // type your code here....
  int n, i;
  scanf("%d", &N);
  scanf("%d", &n);

  struct Edge edges[n];

  for (i = 0; i < n; i++)
  {
    scanf("%d", &edges[i].src);
    scanf("%d", &edges[i].dest);
  }

  struct Graph *graph = createGraph(edges, n);
  printGraph(graph);

  return 0;
}
```

## Output:
<img width="417" height="524" alt="image" src="https://github.com/user-attachments/assets/df3e2e23-5504-4e0c-8478-f923f037ec0b" />


## Result:
Thus, the C program to represent the given graph using the adjacency list is implemented successfully
