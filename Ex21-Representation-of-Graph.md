# Ex21 Representation of Graph
## DATE: 26-03-2025
## AIM:
To write a C program to display the adjacency matrix of the given graph by supplying the edges and the number of vertices.

## Algorithm
1. Start
2. Read the value of V (number of vertices).
3. Declare an adjacency matrix adjMatrix[V][V].
4. Initialize the matrix to 0 using the init function.
5. Calculate the maximum number of edges me as n * (n - 1) / 2.
6. For each edge, read e1 and e2, add the edge to the adjacency matrix, and stop if e1 == -1 && e2 == -1.
7. Print the adjacency matrix.
8. End

## Program:
```c
/*
Program to display the adjacency matrix of the given graph
Developed by: MUKESH KUMAR S
Register Number: 212223240099  
*/

/*
#include <stdio.h>
int V;
// Initialize the matrix to zero
void init(int arr[][V]) 
{
  int i, j;
  for (i = 0; i < V; i++)
    for (j = 0; j < V; j++)
      arr[i][j] = 0;
}
*/

void printAdjMatrix(int arr[][V])
{
    //type your code here...
    for(int i=0; i<V; i++) {
        for(int j=0; j<V; j++) {
            printf("%d ", arr[i][j]);
        }
        printf("\n");
    }
}
```

## Output:
<img width="362" height="454" alt="image" src="https://github.com/user-attachments/assets/c440bb02-f602-43a9-8190-de01eedfbbe3" />



## Result:
Thus, the C program to print the adjacency matrix of the given graph is implemented successfully.
