# 📊 NumPy란?

**NumPy(Numerical Python)**는 파이썬에서 과학적 계산을 위한 핵심 라이브러리입니다. 특히 **다차원 배열**을 효과적으로 다룰 수 있게 해주며, 수치 해석과 데이터 분석, 머신러닝 등에서 필수적으로 사용됩니다.

---

## ✅ NumPy의 핵심 기능

| 기능 | 설명 |
|------|------|
| **n차원 배열 객체** (`ndarray`) | 파이썬 리스트보다 빠르고 메모리 효율적인 다차원 배열 자료구조 |
| **벡터화 연산** | 반복문 없이 빠른 연산 가능 (브로드캐스팅 지원) |
| **선형대수** | 행렬곱, 역행렬, 특이값 분해(SVD) 등 |
| **통계 및 수학 함수** | 평균, 분산, 표준편차, 삼각함수, 로그 등 |
| **랜덤 숫자 생성** | 다양한 분포 기반의 난수 생성 |
| **파일 입출력** | CSV, 텍스트 파일, 바이너리 파일 등을 손쉽게 읽고 쓸 수 있음 |

---

## 🔢 NumPy 배열 vs 파이썬 리스트

| 특징 | 파이썬 리스트 | NumPy 배열 (`ndarray`) |
|------|----------------|------------------------|
| 구조 | 이질적 데이터 가능 | 동질적 데이터 (속도 ↑) |
| 연산 | for문 사용 필요 | 벡터화 연산 가능 |
| 성능 | 느림 | 빠름 (C 기반 구현) |
| 용도 | 일반 프로그래밍 | 수학/과학/AI 연산에 최적 |

---

## 🧪 예시 코드

```python
import numpy as np

# 배열 생성
a = np.array([[1, 2], [3, 4]])

# 배열 연산
print(a * 2)       # [[2 4], [6 8]]
print(a + a)       # [[2 4], [6 8]]
print(np.mean(a))  # 2.5

