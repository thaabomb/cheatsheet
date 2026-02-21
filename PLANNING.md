# Planning
## Iteration 001
We will use constant-valued functions to store the values of the unit conversions. The functions will be named using the formula <PLURALUNIT>_PER_<SINGULARUNIT>(), for example INCHES_PER_FOOT().
## Iteration 002
We should probably separate classes for each of the different quantities and store the constant valued functions as methods of the class.
## Iteration 003
I don't think we need to use functions. Variables will probably suffice and they will make the code clearer.
## Iteration 004
It would be nice if there was a way to introduce a new unit to the system by specifying a single conversion to a known unit and then the system would automatically create conversions to all other known units. Not sure how to pull that off.
