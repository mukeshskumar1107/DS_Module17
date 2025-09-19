# Ex22 Breadth First Graph
## DATE: 26-03-2025
## AIM:
To write a printQueue C function of the given graph that is to be traversed in the breadth first manner.

![image](https://github.com/user-attachments/assets/f483f48c-6af0-4027-a993-01c108a50933)


## Algorithm
1. Start 
2. Check if the queue is empty using isEmpty(q). If true, print "Queue is empty".
3. If not empty, print "Queue contains ".
4. Initialize a loop variable i to q->front.
5. Use a for loop to iterate from q->front to q->rear, printing each item in q->items[i].
6. End the loop and function after printing all items. 
7. End

## Program:
```c
/*
Program to traverse graph using BFS
Developed by: MUKESH KUMAR S
Register Number: 212223240099 
*/

/*
#include <stdio.h>
#include <stdlib.h>
#define SIZE 40

struct queue {
  int items[SIZE];
  int front;
  int rear;
};

struct queue* createQueue();
void enqueue(struct queue* q, int);
int dequeue(struct queue* q);
void display(struct queue* q);
int isEmpty(struct queue* q);
void printQueue(struct queue* q);

struct node {
  int vertex;
  struct node* next;
};

struct node* createNode(int);

struct Graph {
  int numVertices;
  struct node** adjLists;
  int* visited;
};
*/

void printQueue(struct queue *q)
{
  // type your code here
  printf("Queue contains ");
  for (int i = q->front; i <= q->rear; i++)
  {
    printf("%d ", q->items[i]);
  }
}
```

## Output:
<img width="981" height="552" alt="image" src="https://github.com/user-attachments/assets/b8885889-7d49-4266-8478-fc8bdcbb1366" />



## Result:
Thus, the code for the printQueue function of the following graph that is to be traversed in the breadth first manner is implemented successfully.
