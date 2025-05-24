
# Ex.No 12.b Stack Using Linked List – Push and Index Display

## Aim

To write a Python program to insert 3 elements into a stack and display the index value of each element stored in the stack.

## Algorithm

1. Start  
2. Create a stack  
3. Append elements to the stack  
4. Use a loop to print the index and value of each element in the stack  
5. Print the result  
6. Stop

## Program

```python
stack = []

# Push elements into the stack
stack.append('a')
stack.append('b')
stack.append('c')

# Display the initial stack
print('Initial stack:', stack)

# Print index and element
for i in range(len(stack)):
    print(i, stack[i])
```

## Output
![image](https://github.com/gokulkrishnan2005/19CS301-Module12/blob/main/module%2012-2.png?raw=true)


## Result
Thus, program to insert 3 elements into a stack and display the index value of each element stored in the stack was implemented and executed successfully.

