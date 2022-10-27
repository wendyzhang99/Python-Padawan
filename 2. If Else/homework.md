## [Finding the percentage](https://www.hackerrank.com/challenges/finding-the-percentage/problem)

```python
if __name__ == '__main__':
    n = int(input())
    student_marks = {}
    for _ in range(n):
        name, *line = input().split()
        scores = list(map(float, line))
        student_marks[name] = scores
    query_name = input()
    print("{0:.2f}".format(sum(student_marks[query_name])/3))
```


## [Find the Runner-Up Score!](https://www.hackerrank.com/challenges/find-second-maximum-number-in-a-list/problem)

```python
if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split())
    arr_set = set(arr)
    arr_sort = sorted(arr_set)
    arr = list(arr_sort)
    print(arr[len(arr) -2: len(arr) -1][0])
```

