# CATALOG-HACKATHON

The case scenario is about finding the secret:
Let a data - D be considered and it is easily reconsructable from any K pieces but k-1 pieces cant reveal any kind of information.
(k,n) threshold scheme is being imolemented in this particular scnario by dividing d into D1,D2 .... Dn pieces

We need to implement or kind the value of c by considering the variable unkown variable c as a secreat.In the particular quadratic equation p(x)=ax2+bx+c we consider 5 points and the eqation with 2 points and 3 unknowns.

/////Python program for the implementation of finding the secret.
The dictionary named keys is implemented by taking n and k values as variable inputs.
The code is to be implemented by finding the base and value using test cases.

WE implement it by finding the value of keys in quadratic equation by using the defkeys function:

def find_c(keys):

a=keys['a']
b=keys['b']
c=keys['c']
return c
keys={'a':2, 'b':3, 'c':5}                        -------------------------------->Dictionary named keys
value_of_c=find_c(keys)
print(f"The value of c is: {value_of_c}")
###THE OUTPUT IS C=5 IN THIS PARTICULAR CASE SCENARIO.

------>The code is implemented after finding the c value by implementing the test cases in the keys dictionary:
# Function to calculate the result of base raised to the power of value
def calculate_power(keys):
    base = keys['base']
    value = keys['value']
    result = base**value
    return result

test_cases = [
    {'base': 2, 'value': 3}, 
    {'base': 5, 'value': 2},
    {'base': 7, 'value': 0},
    {'base': 10, 'value': 1},
    {'base': 3, 'value': 4}
]
for i,keys in enumerate(test_cases):
    result=calculate_power(keys)
    print(f"Test Case {i+1}: Base={keys['base']},Value = {keys['value']} => Result = {result}")

The output for this particular test case includes the values of base and values.



























