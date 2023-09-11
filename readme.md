# :1234: Guess the number game :1234:

My first contact with [Zig](https://ziglang.org/) programming languge is this Guess the Number console game.

## Play it :computer:

    $ git clone https://github.com/AxelBrinck/GuessTheNumber.git
    $ zig build-exe ./game.zig
    $ ./game.exe

### Making a very small executable :floppy_disk:

    $ git clone https://github.com/AxelBrinck/GuessTheNumber.git
    $ zig build-exe ,/game.zig -dead_strip -O ReleaseSmall
    $ ./game.exe