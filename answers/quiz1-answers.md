## 1) What is an int, and what is is short for?

> `int` is short for `integer`. It is one of the most common data types, and they are used to store **whole numbers**.

## 2) What is a string?

> A `string` in programming is a datatype that stores a sequence of alphanumeric and/or special characters. It is probably the most common data type.

## 3) What happens if you "add" the two strings below together? What is the value of output that will be printed to the screen?

> If you "add" the two strings using the `+`, it will concatenate the strings together! The string that will be printed to the screen will be `sodapop`.

## 4) The next few questions will use the following code:

```python
def f(x, y):
    return (x * y)

z = f(9, 5)
print(z)
```

#### 4a) Is f(x, y) a function or a variable? What are f, x, and y?

> `f(x, y)` is a function. `f` is the name of the function that will be used to call the function. `x` and `y` are the function's **parameters**, which are required variables that need to be provided to execute the function.

#### 4b) What is z a function or a variable?

> `z` is a variable. It is used to store the calculated value of `f(9,5)`.

#### 4c) What is the value of z that will get printed to the screen?

> The function `f` multiplies two numbers together, so `z = f(9,5)` is the same as saying `z = (9 * 5)`. The output that will be printed to the screen will be `45`.

## 5) The next few questions will use the following code:

```python
def add(x, y):
    return (x + y)

a = add(10, 5)
print(a)

b = add('10', '5')
print(b)
```

#### 5a) What will `print(a)` print to the screen?

> `print(a)` will print `15` to the screen.

#### 5b) What will `print(b)` print to the screen?

> `print(b)` will print `105` to the screen.

#### 5c) Explain why the output of `print(a)` and `print(b)` are different.

> The difference is because of the data types of the parameters that are passed to the function. Without quotes, `10` is treated like an integer, with quotes, `'10'` is treated like a string. Depending on the data type, the `+` operator does different things. For integers, `+` adds two integers together. For strings, `+` concatenates the two strings together, even if those two strings only consist of numbers.