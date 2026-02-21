# Planning
## Iteration 001
- We will use constant-valued functions to store the values of the unit conversions. The functions will be named using the formula <PLURALUNIT>_PER_<SINGULARUNIT>(), for example INCHES_PER_FOOT().
## Iteration 002
- We should probably create separate classes for each of the different quantities and store the constant valued functions as methods of the class.
## Iteration 003
- I don't think we need to use functions. Variables (properties of the class) will probably suffice and they will make the code clearer.
## Iteration 004
- It would be nice if there was a way to introduce a new unit to the system by specifying a single conversion to a known unit and then the system would automatically create conversions to all other known units. Not sure how to pull that off.
- Should I make a matrix of unit conversions that has all the units as rows and all the units as columns and all the conversion factors as elements?
- Should I make a class for each unit? With properties for the singular name, the plural name, and the symbol? The properties could be lists that can hold multiple values to handle cases like meter/metre. There could be a property for index in the matrix rows/columns.
- Would it help to instantiate the unit objects as static properties in a class?
