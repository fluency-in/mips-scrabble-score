# MIPS Assembly: Scrabble Score

Write a program that, given a word, computes the scrabble score for that word.

## Letter Values

You'll need these:

```plain
Letter                           Value
A, E, I, O, U, L, N, R, S, T       1
D, G                               2
B, C, M, P                         3
F, H, V, W, Y                      4
K                                  5
J, X                               8
Q, Z                               10
```

## Examples
"cabbage" should be scored as worth 14 points:

- 3 points for C
- 1 point for A, twice
- 3 points for B, twice
- 2 points for G
- 1 point for E

And to total:

- `3 + 2*1 + 2*3 + 2 + 1`
- = `3 + 2 + 6 + 3`
- = `5 + 9`
- = 14

## Extensions
- You can play a `:double` or a `:triple` letter.
- You can play a `:double` or a `:triple` word.

For these problems, we use the popular MIPS simulator [MARS](http://courses.missouristate.edu/KenVollmar/mars/). Download the MARS jar archive from the MARS website and place it somewhere easily accessible. Also install the Java SDK if you do not have it already.

To run the tests, assemble and run the test runner file for a given exercise either via the MARS simulator GUI, or on the command line. To run on the command line,
specify first the runner file and then your implementation, like so:

    java -jar /path/to/mars.jar nc runner.mips impl.mips

To run in the GUI, `include` your implementation at the bottom of "runner.mips"
by uncommenting the final line.

The test runner will either complete with a “success” message or terminate on a failing test with a message specifying the input for which that test failed.

## Source

Inspired by the Extreme Startup game [https://github.com/rchatley/extreme_startup](https://github.com/rchatley/extreme_startup)

This exercise is from the [MIPS Assembly][mips] track on [Exercism][exercism]

[exercism]: http://exercism.io
[mips]: http://exercism.io/languages/mips



