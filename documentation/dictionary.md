# Dictionary

Actions 
- choices that can be made in a state.

Agent 
- entity that perceives its environment and acts upon that environment. 

Breadth-First Search (BFS)
- is a search algorithm.
- which always expands the shallowest node in the frontier.

Class
- is a way to generate objects in Python
    ```python
    class StackFrontier():      // Class
        def __init__(self):     // Function 
            self.frontier = []  // empty list
     
        def add(self, node):    // Function 
            self.frontier.append(node)
    ```
- it refers to Object-Oriented Programming, where the idea here is I want to create an object
  that is able to store all my Frontier Data. And I would like to have functions, also known as
  methods, that I can use to manipulate the object.

Depth-First Search (DFS)
- is a search algorithm.
- that always expands the deepest node in the frontier.

Expand the Node
- Look at all the neighbours of that node. 

Frontier 
- represents all the options we could explore next, that we haven't yet explored.
- if the frontier is empty, there are no solutions to explore.

Goal test
- a way to determine whether a given state is a goal states.

Inital stage
- the starting point where the agent begins.

Methods
- Functions which are used to manipulate the object.

Natual language
- understanding actual languages, not programming languages.

Node
- data structure, that keeps track of:
  - a state
  - a parent (node that generated this node)
  - an action (action applied to a parent node to get this node)
  - a path cost (from initial state to node)

Optimal solution
- a solution that has the lowest path cost among all the possible solutions.

Path cost
- numerical cost associated with a given path.

Queue 
- first-in first-out
- the first node added to the frontier, will be the first node we remove and explore

Solution
- a sequence of actions that leads from the inital state to the goal state.

Stack
- last-in first-out data type
- the last thing I add to the frontier, will be the first thing I remove from the frontier.

State 
- a configuration for the agent and its environment. 

State Space
- the set of all states reachable by an initial state by any sequence of actions. 

Transition model 
- a description of what states results from performing any applicable action in any state.
- [RESULTS] returns the state resulting from performing an action in a state. 
- [RESULTS(s, a)] - S some state, A some action
