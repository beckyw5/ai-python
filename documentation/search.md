# Search

## Search use cases
Google Maps, makes use of a search algorithm, it is trying ot generate the best route
from point A to point B, depending on traffic and times of the day.

## Search Problems
- initial state
- actions
- transition model
- goal test
- path cost function

## Approach
- Start with a frontier that contains the initial state.
- Start with an empty explored set.
- Repeat:
  - If frontier is empty, no solution.
  - Remove node from frontier.
  - If node contains goal state, return the solution.
  - Add the node to the explored set.
  - Expand node, add resulting nodes to the frontier if they aren't already within the
  frontier or explored set.
