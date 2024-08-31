# Navigating Data

There are a few ways to get the data from the frontier.

## Search Algorithms
Breadth-First Search (BFS)
- which always expands the shallowest node in the frontier.

Depth-First Search (DFS)
- which always expands the deepest node in the frontier.

## Retrieving data
Stack
- last-in first-out data type
- meaning the last node added to the frontier, will be the first thing removed from the frontier
- below is an example of an implementation of a Frontier as a Stack
```python
class StackFrontier():      // Class
    def __init__(self):     // Function 
        self.frontier = []  // empty list
 
    def add(self, node):    // Function 
        self.frontier.append(node)  // Appended to the end of the list
    
    def remove(self):
        node = self.frontier[-1]           // Get the last node from the frontier
        self.frontier = self.frontier[:1]  // Updates the frontier, to remove the last item from the frontier
        return node
```

Queue
- first-in first-out data type
- meaning the first node added to the frontier, will be the first node we explore
- the nodes affectively form a line or a queue

```python
class QueueFrontier(StackFrontier):  // Class, inheriting from the StackFrontier, which means it can do everything within the StackFrontier Class.
     def remove(self): // Redefining how we remove a node from the frontier
        node = self.frontier[0]            // Get the first node in the frontier
        self.frontier = self.frontier[1:]  // Updates the frontier, to remove the first item from the frontier
        return node
```

### Retrieving Data Techniques
First item
- To get the first item `[0]`

Last item
- To get the last item in a list in Python you use `[-1]`
