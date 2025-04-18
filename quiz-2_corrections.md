# Quiz 2 Corrections
1. Write the following mathematical expressions in Java. Assume variables `a`, `b`, and `c` have been declared and initialized.

$$\frac{-b + \sqrt{b^2-4ac}}{2a}$$

**ANSWER**: 

`(-b + Math.sqrt(b * b - 4*a *c)) / (2 * a)`

**CORRECTION**:

_Replace this text with your correction._


2. Complete the truth table.

**ANSWER**:

| `a`     | `b`     | `a && b`  | `a \|\| b`  |
|---------|---------|-----------|-------------|
| `true`  | `true`  | `true`    | `true`      |
| `true`  | `false` | `false`   | `true`      |
| `false` | `true`  | `false`   | `true`      |
| `false` | `false` | `false`   | `false`     |

**CORRECTION**:

_Replace this text with your correction._

3. Select the true expressions.

**ANSWER**:

`1 >= 2 || !false` is `true`

`true != false` is `true`

`!(3 % 2 == 1) && true` is `false`

`true && !true` is `false`

**CORRECTION**:

_Replace this text with your correction._

4. Which of the following statements is correct about an if statement?

**ANSWER**:

You can omit an else statement if there is no task defined in the else

**CORRECTION**:

_Replace this text with your correction._

5. Complete the trace table for each variable in the following code segment

**ANSWER**:

| `m` | `n` |
|-----|-----|
| 2   | 5   |
| 24  | 6   |

**CORRECTION**:

_Replace this text with your correction._

6. Find the output generated by the following code segment.

**ANSWER**:

```
B
C
```

**CORRECTION**:

_Replace this text with your correction._

7. Find the output generated by the following code segment.

**ANSWER**:

```
B
X
Z
```

**CORRECTION**:

_Replace this text with your correction._

8. Find the output generated by the following code segment.

**ANSWER**:

```
where?
here
why?
```

**CORRECTION**:

_Replace this text with your correction._

9. Find the output generated by the following code segment.

**ANSWER**:

```
not equal
equal
```

**CORRECTION**:

_Replace this text with your correction._

10. Find the output generated by the following code segment.

**ANSWER**:

```
three
done!
```
11. Find the output generated by the following code segment.

**ANSWER**:

```
Incorrect
Incorrect
Invalid choice!
```

**CORRECTION**:

_Replace this text with your correction._

12. Write a boolean expression that is true if the first character in the string variable str is a upper-case alphabetic character. Assume str has been declared and initialized. Hint:  Use the charAt method.

**ANSWER**:

`'A' <= str.charAt(0) && str.charAt(0) <= 'Z'`

**CORRECTION**:

_Replace this text with your correction._

13. Write an if-else statement that displays "___ is even" if the value of the `int` variable `num` is even, otherwise display "___ is odd" (the blank must be the value of `num`). Assume num has been declared and initialized.

**ANSWER**:

```java
if(num % 2 == 0) {
    System.out.println(num + " is even");
} else {
    System.out.println(num + " is odd");
}
```

**CORRECTION**:

_Replace this text with your correction._
