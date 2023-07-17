# **Intro to functions: a simple example**

The `add_three()` function below accepts any number, adds three to it, and then returns the result.

```python
*# Define the function*
def add_three(input_var):
    output_var = input_var + 3
    return output_var
```

Every function is composed of two pieces: a **header** and **body**.

<img src=https://storage.googleapis.com/kaggle-media/learn/images/gu0AWhK.png />

# **How to run (or "call") a function**

When we run a function, it can also be referred to as "calling" the function.

In the code cell below, we run the function with `10` as the input value. We define a new variable `new_number` which is set to the output of the function.

```python
*# Run the function with 10 as input*
new_number = add_three(10)

*# Check that the value is 13, as expected*
print(new_number)
```

> 13
> 

<img src=https://storage.googleapis.com/kaggle-media/learn/images/hlUbxQE.png />

# **A more complex example**

Now that you understand the basics, we can move on to an example with a longer calculation.

Say you are helping a friend to calculate their weekly paycheck after taxes.

- They're in a 12% tax bracket (in other words, 12% of their salary is taken for taxes, and they only take home 88%), and
- They're paid hourly, at a rate of $15/hour.

The function below calculates the paycheck based on the number of hours worked. The function is more complicated than with the first example, because the function has more lines of code and comments. Similar to the example above, the function has a single argument (`num hours`). In the function body, we:

- Use the value for `num_hours` to specify the value for a new variable `pay_pretax`.
- Use the value of `pay_pretax` to specify the value for a new variable `pay_aftertax`.
- Return the value of the `pay_aftertax` variable.

```python
def get_pay(num_hours):

    *# Pre-tax pay, based on receiving $15/hour*
		pay_pretax = num_hours * 15

    *# After-tax pay, based on being in 12% tax bracket*
		pay_aftertax = pay_pretax * (1 - .12)
    return pay_aftertax
```
