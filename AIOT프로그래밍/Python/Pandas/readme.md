# 🐼 Pandas란?

**Pandas**는 데이터 분석을 위한 파이썬 라이브러리로, **표 형식의 데이터(데이터프레임)**를 다루는 데 매우 강력한 도구입니다.

---

## ✅ 핵심 객체

| 객체 | 설명 |
|------|------|
| **Series** | 1차원 배열 (인덱스를 가진 리스트) |
| **DataFrame** | 2차원 표 (엑셀 표와 유사) |

---

## 🔧 주요 기능

- 데이터 불러오기/저장 (CSV, Excel 등)
- 결측치 처리, 필터링, 정렬
- 그룹별 연산 (groupby)
- 통계 함수 및 집계 (mean, sum 등)
- 시계열 데이터 처리

---

## 🧪 예시 코드

```python
import pandas as pd

# 데이터프레임 생성
data = {'name': ['Alice', 'Bob'], 'age': [25, 30]}
df = pd.DataFrame(data)

# 데이터 보기
print(df.head())

# 필터링
print(df[df['age'] > 26])

# 그룹별 평균
print(df.groupby('name').mean())

