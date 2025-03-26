What is this?
=============

This is a zig library for reading and writing .wav files' metadata and data for use in my ByteWave
project, it is currently in its initial stage and will only work with PCM or IEEE754 wav formats

Build steps: (Currently everything is self contained in the main function)
--------
> Run the following command
> ```
> zig build-exe main.zig
> ```

This also has a parallel defined c library

C Build steps: (Currently everything is self contained in the main function / file)
---------
> ```
> gcc -o main.exe main.c
> ```
