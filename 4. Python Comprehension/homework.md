## [Staircase](https://www.hackerrank.com/challenges/staircase/problem)
```python
def staircase(n):
    # Write your code here
    for i in range(n):
        print((n-i-1)*" "+(i+1)*"#")
```
## [Plus Minus](https://www.hackerrank.com/challenges/plus-minus/problem)
```python
def plusMinus(arr):
    # Write your code here
    print(f'{len([x for x in arr if x > 0]) / len(arr):.6f}', f'{len([x for x in arr if x < 0]) / len(arr):.6f}', f'{len([x for x in arr if x == 0]) / len(arr):.6f}', sep = '\n')
```
## [Compare the Triplets](https://www.hackerrank.com/challenges/compare-the-triplets/problem)
```python
def compareTriplets(a, b):
    # Write your code here
    c = [0,0]
    n = len(a)
    for i in range(n):
        if (a[i]>b[i]):
            c[0]+=1
        if (a[i]<b[i]):
            c[1]+=1
        else:
            continue
    return c
```
## [Sequence Equation](https://www.hackerrank.com/challenges/permutation-equation/problem)

```python



```
## [List Comprehensions](https://www.hackerrank.com/challenges/list-comprehensions/problem)
```python

```
## [Nested Lists](https://www.hackerrank.com/challenges/nested-list/problem)
```python
if __name__ == '__main__':
    print((lambda ls: '\n'.join(sorted([n for n, s in ls if s == sorted(set(list(zip(*ls))[1]))[1]])))([(input(), float(input())) for _ in range(int(input()))]))
```
