# NR2003
This is an attempt at making NR2003 open source for the purposes of (a) recompiling to 64-bit to extend lifetime, (b) make it eaiser to use modern hardware features such as AVX, DX11, etc., and (c) increasing its modability.  The non-source files are [ghidra](https://ghidra-sre.org/) project files.

## Project Goals
Here are the following goals for this project.  All pull requests must work to advance one of these goals or the request will be rejected.  No pull request shall be made which attempts to fundamentally alter what the game is.
* Decompile the game into readable source code, such that recompiling will produce the exact same results as the original game.
* Make 64-bit versions of the game and tools.
* Make the game and tools cross-platform.
* Try optimizing the physcis engine using the SSE and AVX instruction sets (or CPU-specific vector instruction sets).
* Remove the arbitrary lap, series, and track limits from the game.
* Make the FoV setting work in widescreen aspect ratios.
* Give the FoV setting a much lower minimum value.
* Update the graphics API to Direct3D 11, and modern OpenGL versions.
* Allow for series to use custom physics sets using INI files in addition to being able to select from one of the hardcoded physics sets.
* Remove the CD check and the check to see if the game has been "properly installed".
* Make the PAS exporter work with modern versions of 3DS Max.
