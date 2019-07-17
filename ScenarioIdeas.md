# Idea table:

Generated at: https://www.tablesgenerator.com/markdown_tables

|  | Possible Actions | Rewards per Outcome | Properties of other entities | Nash Equilibrium | Other Notes |
|----|-----------------------|--------------------------------------------------------------------------------------------------------------------------|-------------------------------------|------------------|-------------|
| #1 | Expand, attack, trade | Expanding + attacking spends resources for greater resource bonuses later. Trading gives bonus resources for both agents | No other entities other than agents | Attack |  |
| #2 |  |  |  |  |  |
| #3 |  |  |  |  |  |
| #4 |  |  |  |  |  |
| #5 |  |  |  |  |  |

# Details:
## Idea 1. (Risk but on a grid)
Grid based cell game, each agent starts with 1 cell on some part of the grid. Agents use resources to expand, attack, or trade with neighboring cells. Every turn agents gain a set amount of resources based on area of agent's cells. For every neighboring cell, if it is not occupied, the agent can choose to spend resources to expand into the area, or not. If the cell is occupied, the agent can choose to attack, or trade. Attacking allows for the takeover of the cell and requires the agent to spend resources. Trading requires the agent to give resources to the other agent, but if both agents decide to trade, they can recieve some bonus based on who gave more resources. If one agent attacks, and the other trades, the attacker automatically wins. If both attack, the agent that spent more resources to attack wins. Resource costs and bonuses can be tweaked to ensure fairness and balance.
### Examples: 
Agent A and Agent B are neighbors: if A trades 2 resources, and B trades 4 resources, A could gain 4(from B) + 2(bonus includes how much given) + 1(some multiplier of how much was given in this case 0.5 for giving less) resulting in net +5, B would gain 2(from A) + 4(given) + 4(multiplier bonus of 1 for giving more) resulting in +6 \
If A attacks B, spending 5 resources; B attempts to trade 4 resources, A takes over some area of B and gains 4 resources from B's trade with net gain of -1 resource and + some area; B has a net gain of -4 resources and -some area. \
If A attacks B, spending 5 resources; B attacks A spending 6 resources, B takes some area of A. A has a net gain of -5 resources and -some area; B has a net gain of -5 resources and -some area.

### Possible expansion:
Add defend action, which blocks attack, but opponent agent gains bigger bonus resource if they try to trade. 

