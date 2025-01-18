# Quake II for MSVC 2022
Vanilla Quake 2 Source Code for MSVC 2022 with targets for `x86` and `x64`.


## Why?
This is the original Quake 2 source code from ID Software (quake2, ref_gl, game) fixed to compile with Visual Studio 2022.
A few little bugs were fixed, but nothing more than was needed to get this code to compile on both `x86` and `x64`. The CD Audio playback is disabled on `x64` and enabling it will cause the game to crash (won't fix).


## How to Build
1. Clone this repo and navigate to `code` directory, then open `quake2.sln` in VS2022.
2. Select your target arch and hit `Build All` to compile quake2 exe, ref_gl and game DLLs.
3. Copy your `baseq2` folder from Quake 2 instalation and have fun.

