# Q-Sys Finite State Machine

This Q-Sys Lua plugin implements a finite state machine.

It accepts trigger inputs and will change state if the transition is permitted.

The permitted transitions may be defined in one of four modes:

 - Sequential (with optional loop around)
 - Allow from states
 - Allow to states
 - Allow all transitions

Tested on Q-Sys v8.0
