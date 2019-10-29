##Python Notes

INPUT AND OUTPUT

| FUNCTION | PSEUDO     | EXAMPLE                        | OUTPUT      |
| -------- | ---------- | ------------------------------ | ----------- |
| PRINT    | 'x' or "x" | print('cake') OR print("cake") | cake        |
| INPUT    | input('x') | input("enter here: ")          | enter here: |





OPERATORS

| FUNCTION                                             | PSEUDO                                                  | EXAMPLE                       | OUTPUT                     |
| ---------------------------------------------------- | ------------------------------------------------------- | ----------------------------- | -------------------------- |
| PLUS, MINUS, MULTIPLY                                | + - *                                                   | 2+2, 2 - 2, 2 * 2,            | 4, 0 ,4,                   |
| DIVIDE (becomes automatically float), DIVIDE BY ZERO | /, /0                                                   | 2/2, 2/0                      | 1.0, ERROR                 |
| EXPONENTIATION (to the power of)                     | **                                                      | 2**3                          | 8                          |
| QUOTIENT (times a number goes into another)          | //                                                      | 20//6                         | 3                          |
| REMAINDER (remaining number left over from division) | %                                                       | 20%6                          | 2                          |
| IN-PLACE (combining operators)                       | New_Value_of_VAR = Old_Value_VAR + 3 ----> Old_VAR += 3 | x += 3<br />"ello" += "world" | Old_Var + 3<br />elloworld |
|                                                      |                                                         |                               |                            |
|                                                      |                                                         |                               |                            |
|                                                      |                                                         |                               |                            |

STRING

|                                       |                               |                                                   |                                       |
| ------------------------------------- | ----------------------------- | ------------------------------------------------- | ------------------------------------- |
| BACKSLASH (to allow quotes, etc)      | \                             | 'Brian\\'s mother: He\\'s not the Messiah.'       | Brian's mother: He's not the Messiah. |
| QUOTATIONS (to allow quotes)          | "" vs. ''                     | "Brian's mother: He's not the Messiah."           | Brian's mother: He's not the Messiah. |
| BACKSLASH WITH N (to make a new line) | \n                            | 'Hello\\n World'                                  |                                       |
| TRIPLE QUOTE (to avoid writing \n)    | """                           | """What<br />A Wonderful<br />World"""            | What<br />A Wonderful<br />World      |
| CONCATENATION                         | 'x' + 'y'                     | "What" + 'are' + "you" + 'doing' + '?', "2" + "2" | Whatareyoudoing?<br />22              |
| MULTIPLY                              | 3 * x<br />3.0 * x<br />0 * x | "hello" * 3<br />"hello" * 3.0<br />"hello" * 0   | hellohellohello<br />ERROR            |

TYPE CONVERSION

|         |          |                     |      |
| ------- | -------- | ------------------- | ---- |
| INTEGER | int(x)   | int("2") + int("3") | 5    |
| FLOAT   | float(x) | float(9)            | 9.0  |
|         |          |                     |      |
|         |          |                     |      |



VARIABLES

* name of variables can only be:
  * LETTERS
  * NUMBERS(can not start with number)
  * UNDERSCORES
  * e.g. h_1 = 78

|                                                              |                |                              |                              |
| ------------------------------------------------------------ | -------------- | ---------------------------- | ---------------------------- |
| ASSIGNING A VARIABLE(can be overwritten or reassigned countless times) | =              | x = 7                        | print(x) ---> 7              |
| DELETING A VARIABLE                                          | del            | del x                        | print(x) ----> ERROR         |
| VARIABLE WITH INPUT                                          | x = input("y") | x =input("How old are you?") | print(x) ----> value inputed |



* BOOLEANs

  |           |      |                    |                 |
  | --------- | ---- | ------------------ | --------------- |
  | EQUAL     | ==   | 3 == 3<br />3 == 5 | True<br />False |
  | NOT EQUAL | !=   | 3 != 3<br />3 != 5 | False<br />True |
  |           |      |                    |                 |

  