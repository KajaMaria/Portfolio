
# Algorithm

Algorithm - A sequence of instruction to solve the problem

- It has to be repeatable :
  Solves the problem. Accepts initial state .
  If you give it the same input i will aways give it the same output.
-

Example:

Cooking instructions:
Inputs:
- Ingredients
- Cooking supplies
- (Time)

Instructions:
- Put water in the pan
- boil it
- add pasta
- cook for 8 minutes
- take pasta out

Sequence that produces an output for a given input.

- Look for edge cases
- Look for inputs
- What is the output
- Wrong inputs?

This should become out acceptance criteria

Names example:
- How many people and how many groups?

Starting with:
- Test
- Function signature:
          - signature is a name
          - name of the parameters
          - types of outputs
          - types of each argument

With the pure function return is very important
With the second one it is changing something in the world

``` def add(a,b)
      a+b
    end

    ```
```
    a = 6
    def add(b)
      a = a +b
    end
    ```

signature :
equal_groups (names, groups)
string[][] string[] int

First checks:
- Can i do it on paper - Yes or no?
- talk to other people about it
- How to translate to code? :
    - Write in plain english
Example:
1. make four columns
  ``` x = [[][][][]]
  ```
2. go through a list of names?
```
each block
```
3. Write name in each column at the time
  
