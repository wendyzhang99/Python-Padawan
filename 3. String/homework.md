## [Mutations](https://www.hackerrank.com/challenges/python-mutations/problem)

```python
def mutate_string(string, position, character):
    string = string[:position] + character + string[position+1:]
    return string
```
## [Capitalize!](https://www.hackerrank.com/challenges/capitalize/problem)

```python
def solve(s):
    return ' '.join([a.capitalize() for a in s.split(' ')])
```
## [sWAP cASE](https://www.hackerrank.com/challenges/swap-case/problem)
```python
def swap_case(s):
   return s.swapcase()
```
## [What's Your Name?](https://www.hackerrank.com/challenges/whats-your-name/problem)

```python
def print_full_name(first, last):
    # Write your code here
    print(f'Hello {first} {last}! You just delved into python.')
```
## [String Formatting](https://www.hackerrank.com/challenges/python-string-formatting/problem)
```python
def print_formatted(number):
    # your code goes here
    width=len(f'{number:b}')
    for i in range(1, number+1):
        print(f'{i:{width}d}', f'{i:{width}o}', f'{i:{width}X}', f'{i:{width}b}')
```
## [Time Conversion](https://www.hackerrank.com/challenges/time-conversion/problem)

```python
def timeConversion(s):
    # Write your code here
    if s[-2:] == "AM" and s[:2] == "12":
        time = '00' + s[2:len(s) - 2]
    if s[-2:] == "PM" and s[:2] != "12":
        time = str(int(s[:2])+ 12) + s[2:len(s) - 2]        
    else:
        time = s[0:len(s) - 2]
    return time
```