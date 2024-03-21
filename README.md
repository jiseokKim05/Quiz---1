# Quiz 1

```python
numbers = [111,26,37,48]
result = []
for num in numbers:
    if num % 2 == 0:
        result.append(num)
print(result)

numbers = [111,26,37,48]
result = list(filter(lambda x: x % 2 == 0, numbers))
print(result)
```
