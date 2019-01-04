# python-summary

# 1)lambda
lambda operator or lambda function is used for creating small, one-time and anonymous function objects

Usual method:
def add(x, y): 
    return x + y
  
#Call the function
add(2, 3)  # Output: 5

Lambda method:
dd = lambda x, y : x + y 
print add(2, 3) # Output: 5

# 2) map
map functions expects a function object and any number of iterables like list, dictionary, etc. It executes the function_object for each element in the sequence and returns a list of the elements modified by the function object.

#e.g.
def multiply2(x):
  return x * 2
    
map(multiply2, [1, 2, 3, 4])  # Output [2, 4, 6, 8]

# 3) map + lambda
MAPOUTPUT = map(lambda x : x*2, [1, 2, 3, 4]) #Output [2, 4, 6, 8]

--> convert list = list(MAPOUTPUT) before you can call index etc.
