[파이썬_기본문법.md](https://github.com/user-attachments/files/20076733/_.md)
# 🐍 파이썬 기본 문법 정리

파이썬은 문법이 간결하고 직관적이어서 초보자에게도 매우 적합한 프로그래밍 언어입니다. 아래는 주요 문법 요소입니다.

---

## 1. 변수와 자료형
```python
# 변수 선언
x = 10       # 정수형
pi = 3.14    # 실수형
name = "Alice"  # 문자열
is_active = True  # 불린형
```

## 2. 자료구조
```python
# 리스트 (List)
fruits = ["apple", "banana", "cherry"]

# 튜플 (Tuple)
point = (10, 20)

# 딕셔너리 (Dictionary)
person = {"name": "Alice", "age": 25}

# 집합 (Set)
unique_numbers = {1, 2, 3}
```

## 3. 조건문
```python
if x > 0:
    print("양수입니다")
elif x == 0:
    print("0입니다")
else:
    print("음수입니다")
```

## 4. 반복문
```python
# for 반복문
for fruit in fruits:
    print(fruit)

# while 반복문
count = 0
while count < 3:
    print(count)
    count += 1
```

## 5. 함수 정의
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))
```

## 6. 예외 처리
```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("0으로 나눌 수 없습니다.")
finally:
    print("예외 처리 완료")
```

## 7. 클래스
```python
class Person:
    def __init__(self, name):
        self.name = name

    def say_hello(self):
        print(f"안녕하세요, 제 이름은 {self.name}입니다.")

p = Person("Alice")
p.say_hello()
```

## 8. 파일 입출력
```python
# 파일 쓰기
with open("hello.txt", "w") as f:
    f.write("Hello, Python!")

# 파일 읽기
with open("hello.txt", "r") as f:
    content = f.read()
    print(content)
```


