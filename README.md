# Project LT
ProjectLT is a game engine written in C++ that aims to be simple to use, clearly structured and a good place to start when studying how games or game engines work. It uses OpenGL as its rendering API but feature abstractions so other implementations can be easily added in the future.

# How it works
The solution is divided into two separate projects: [engine](engine) and [game](game). The first one compiled to a .lib that contains all of the logic required for the game to function, including rendering, input handling, windowing and physics whereas the latter is the final executable that contains the game logic itself, including its featured items, NPCs, levels, assets and more.
