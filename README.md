# Bashlog
Bashlog is a small project in BASH scripting to keep track of logs - small lists of things to do that are intended to be completed in index order.

## Why?
I wanted to strengthen my bash scripting skills. It was a lot of fun!

## Style
I used this style guide from google. Was good!
https://google.github.io/styleguide/shellguide.html

## Functions
- -n: Takes one positional arg, the name of a new log. 
    Creates a new log in your home directory in /bashlog/
- -r: Takes one positional arg, a log that exists to read.
    Prints it prettily.
- -u: Takes one positional arg, a log that exists to update. Asks if you
    would like to complete the 0th index entry.
- -a: Takes two positional args. A log to add to, and a new entry.
    Appends the new entry to the end of the log.
- -d: Takes one positional arg. A log to delete.
    rms the log if it exists.
- -s: Takes three positional args. A log to swap entries in, a entry index, and another entry index. 
    Swaps two entries in a log. 
- -l: Takes no positional args.
    Lists all the logs that exist.
- h: Takes no positional args.
    gives help.

## Usage
    add to your PATH so you can use anywhere! Otherwise, 
    ./bashlog [flag] [pos_arg_1] [pos_arg_2] ... 