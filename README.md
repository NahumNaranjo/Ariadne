# Ariadne
A simple CLearning crossover. This repository is part of CLearning's ecosystem and was made to help other tool's development. If you find it useful, use it. In summary, Ariadne is a simple header-only string managment library.  
By the way, it's called Ariadne because she has a thread (similar to a string, right?) which i think is her labyrinth, to be honest, I just named it 

## Functions
- **cleanBackSlash(char source)**: Will replace all backslashes with normal ones to imrpove your project's compatibility.
- **trimWhitespace(char str)**: Will trim all whitespaces your string has.
- **vote**: This function calls every string checker and returns an int with the result.
- **SimpleHeuristic**: Returns 1 if the string ***looks*** like a string and 0 if it doesn't.
- **EntropyAnalysis**: Returns the entropy value of the variable. Normal entropy for a string is 3.0 to 6.0.
- **SafeString**: Tries to break a non string variable, if it survives, then it returns 1. Be careful with this one, it purposefully tries to crash the program so it might generate some problems with mallocs.
- **getXChars**: Has 2 modes, `f` takes `x` chars from the beginning to the end of the string, `l` does the same but from the end to the beginning.

## Install instructions
Download it from this repository and add the header to your project or use `cl -i ariadne` in your console if you have CLearning installed

### Version
1.1.0 - Ariadne, String Manager
Author: Nahum Naranjo