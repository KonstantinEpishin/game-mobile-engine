# game-mobile-engine
In this repository my engine for mobile devices is being developed
Development is carried out in C ++ using 2D technology.
The main concept of this engine is to abstract from a specific API not to do native, but to create engine logic, which is a layer between the API of a specific platform and the API that provides the engine for creating games. Thus, it is possible to achieve platform independence (all that remains is to connect the correct API for each device separately).
To implement this concept, first of all, you need to create a convenient interface for connecting the hardware API, and then create a convenient API for the engine - after that you can start directly implementing the logic of the engine itself.
