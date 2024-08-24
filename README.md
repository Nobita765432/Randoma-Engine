# Randoma-Engine
Randoma Engine
Randoma Engine is a free, open source 2D online RPG engine in C#

Project Detials
Randoma Engine is provided as a software package, the binaries of which consist of a client, server, and game editor. There are a number of important core components which make up this software package which are described in detail below.

Randoma.Client
Randoma.Client contains the game-client portion of the software package. This consists of the systems handling the game rendering, client-side networking, asset management, game-world caching, and user-interface.

The dependencies for this portion of the project include MonoGame (OpenGL), Lidgren, Penumbra, and QuakeConsole.

Randoma.Server
Randoma.Server contains the game-server portion of the software package. This consists of the systems responsible for handling the underlying gameplay, world updating, state saving and loading, and client-to-client communication.

The dependencies for this portion of the project include Lidgren.

Randoma.Editor
Randoma.Editor contains the game-editor portion of the software package. This consists of the systems responsible for visualized content creation (maps, items, npcs, animations, etc.) as well as for editing existing data.

The dependencies for this portion of the project include MonoGame and DarkUI.

Randoma.Core
Randoma.Core contains code which is shared throughout the rest of the project. This includes game data definition classes, loading and saving managers, utility functions, and more. Anything which might otherwise be duplicated throughout the Randoma engine package if independently implemented in each portion should exist here.

Randoma.Graphics
Randoma.Graphics contains shared graphics and graphics processing related code, mainly shared between the game-editor and game-client.

License
Licensed under the Apache License, Version 2.0 (the "License").

Website & Community
