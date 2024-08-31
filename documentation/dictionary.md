# Dictionary

Actions 
- choices that can be made in a state.

Agent 
- entity that perceives its environment and acts upon that environment. 

Expand the Node
- Look at all the neighbours of that node

Frontier 
- represents all the options we could explore next, that we haven't yet explored.
- if the frontier is empty, there are no solutions to explore.

Goal test
- a way to determine whether a given state is a goal states.

Inital stage
- the starting point where the agent begins.

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

Solution
- a sequence of actions that leads from the inital state to the goal state.

State 
- a configuration for the agent and its environment. 

State Space
- the set of all states reachable by an initial state by any sequence of actions. 

Transition model 
- a description of what states results from performing any applicable action in any state.
- [RESULTS] returns the state resulting from performing an action in a state. 
- [RESULTS(s, a)] - S some state, A some action
