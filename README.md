# compilers-assignment
In a subset of natural language, the names of points in space are defined as the string of a single symbol, line names are defined as two symbols, triangle names are defined as three symbols, etc. up to the case of octagons. Repeating a symbol isn't allowed. Design and build Flex program that will only accept the correct definitions.

Examples of correct definitions:

- triangle BCD
- square BCDA

Examples of incorrect definitions:

- square ABBB
- triangle AD
- corner BCD
Accepted programming languages: FLEX (combined with C/C++).

# Run
- i) lex exercise_3.l
- ii) gcc lex.yy.c
- iii) a.out
