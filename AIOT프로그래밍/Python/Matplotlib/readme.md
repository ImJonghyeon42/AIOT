
---

## 📈 Matplotlib 소개 (마크다운)

```markdown
# 📈 Matplotlib란?

**Matplotlib**는 파이썬에서 데이터를 시각화할 수 있도록 도와주는 라이브러리로, 가장 기본적인 플롯 도구입니다.

---

## ✅ 주요 기능

- 선 그래프, 막대 그래프, 산점도 등 생성
- 제목, 축 이름, 범례 설정
- 다중 그래프 그리기 (subplot)
- 저장 기능 (PNG, PDF 등)

---

## 🔧 대표 함수

| 함수 | 설명 |
|------|------|
| `plt.plot()` | 선 그래프 |
| `plt.bar()` | 막대 그래프 |
| `plt.scatter()` | 산점도 |
| `plt.hist()` | 히스토그램 |
| `plt.show()` | 그래프 출력 |
| `plt.savefig()` | 그래프 저장 |

---

## 🧪 예시 코드

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4]
y = [10, 20, 25, 30]

plt.plot(x, y, label='선 그래프')
plt.xlabel('X축')
plt.ylabel('Y축')
plt.title('간단한 그래프')
plt.legend()
plt.grid(True)
plt.show()

