# Quiz 1

```python
result = (lambda x: x ** 2)(10)
print(result)  # 출력 결과는 100입니다.
```

# Quiz 2

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
