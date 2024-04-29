# **Assignment Operators**

## 1. Assignment (=):

Simply assigns the value of the right operand to the left operand.

```javascript
let x = 10;
```

## 2. Addition assignment (+=):

Adds the value of the right operand to the left operand and assigns the result to the left operand.

```javascript
let x = 5;
x += 3;
// x becomes 8 (5 + 3)
```

## 3. Subtraction assignment (-=):

Subtracts the value of the right operand from the left operand and assigns the result to the left operand.

```javascript
let x = 10;
x -= 4; // x becomes 6 (10 - 4)
```

## 4. Multiplication assignment (\*=):

Multiplies the value of the right operand by the left operand and assigns the result to the left operand.

```javascript
let x = 3;
x *= 2; // x becomes 6 (3 * 2)
```

## 5. Division assignment (/=):

Divides the left operand by the value of the right operand and assigns the result to the left operand.

```javascript
let x = 10;
x /= 2; // x becomes 5 (10 / 2)
```

## 6. Modulus assignment (%=):

Assigns the remainder of dividing the left operand by the value of the right operand to the left operand.

```javascript
let x = 10;
x %= 3; // x becomes 1 (10 % 3)
```

# **Increment and Decrement**

In JavaScript, increment and decrement operators are used to increase or decrease the value of a variable by one.

## **Increment (++):**

_Adds one to the current value of the variable._

The ++ operator can be placed before (++x) or after (x++) the variable name. When used before the variable name (++x), the value is incremented before the current expression is evaluated. When used after the variable name (x++), the value is incremented after the current expression is evaluated.

```javascript
let x = 5;
x++; // x becomes 6
```

```javascript
let x = 5;
let y = ++x; // y becomes 6, x becomes 6
```

## **Decrement (--):**

_Subtracts one from the current value of the variable._

```javascript
let x = 5;
x--; // x becomes 4
```

Similar to the increment operator, the decrement operator -- can also be placed before or after the variable name, with the same pre-increment and post-increment behaviors.

```javascript
let x = 5;
let y = --x; // y becomes 4, x becomes 4
```
