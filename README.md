# popQuizAnswers
Answers to some Python pop quiz questions

## Return the sum of all the multiples of 3 or 7 below the numbers passed in.
```python
def multiple_of_int(ourInt: int):
    get_multiple = [i for i in range(ourInt + 1) if i % 7 == 0 ]
    return sum(pt)
```

## Given a string, remove all numbers from string and return the string without numbers.
```python
import string

string_var = "eosk2q9w7e"
string_only_list = [i for i in string_var if i in string.ascii_letters]
join_string = ''.join(string_only_list)
print(join_string)
```

## Given an array of numbers, multiply each number in the array by the number of elements in the array in descending order
```python
my_list = [3, 12, 34, 10, 6]

def fiddleList(array: list):
    array.sort(reverse=True)
    multiply_by_len = [i * len(array) for i in array]
    
    return multiply_by_len

print(fiddleList(my_list))
```

## Given a string, remove all numbers from string and return  the removed numbers.
```python
import string

stro = "eosk2q9w7e"
get_numbers = [i for i in stro if i in string.digits]
print(get_numbers)
```
