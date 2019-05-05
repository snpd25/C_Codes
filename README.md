# C_Codes

As we know a string in NFA is acceptable when while traversing through every element of the string, starting from the initial state, the final state is attained at the end. 
Here, a structure is defined named state which will store the next state of the given state for the binary inputs 0 and 1 as illustrated. As in NFA, we have more than one next state, thus, if we reach the final state at the end of the string even through following any one of the paths then the string is acceptable.
