The `min` attribute of a goal means the number of agents that must satisfy the goal such that it is considered globally achieved.  
The default value for `min` is _all_, meaning that all agents committed to this goal must set is as achieved to state is as globally achieved.

Goals without committed agents, pass from the state waiting to the state enabled/satisfied/impossible based on the satisfaction state of its sub-goals.

The agent architecture also generates goal achievement events when an agent’s organisational goal becomes possible (enabled) in the current state of the scheme execution.  
The programmer can thus write plans to deal with these events to enable an agent to achieve its organisational goals.