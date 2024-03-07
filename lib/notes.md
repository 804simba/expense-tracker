Widgets size constraints
Widgets get sized based on their size preferences and parent widget size constraints.
In theory, Column widgets prefer to get as much height as possible and as much width as needed by the children.
So therefore it makes sense to use a Column widget inside of a parent widget that constraints the amount of height it can take up
e.g. Scaffold.

Having an unconstrained widget inside of another unconstrained widget will lead to issues.