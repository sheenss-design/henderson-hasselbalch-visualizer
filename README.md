# Henderson-Hasselbalch 방정식 시각화

pH, HCO₃⁻, pCO₂ 세 변수가 Henderson-Hasselbalch 방정식으로 어떻게 연동되는지 슬라이더로 직접 확인할 수 있는 인터랙티브 도구입니다.

## 방정식

\[
\mathrm{pH} = 6.1 + \log_{10}\left( \frac{[\mathrm{HCO}_3^-]}{0.03 \times p\mathrm{CO}_2} \right)
\]

- pKa = 6.1
- 용해도 계수 = 0.03 (mmol/L per mmHg)

## 사용 방법

1. 저장소를 클론하거나 GitHub에서 `index.html`을 열어보세요.
2. **GitHub Pages**를 활성화하면 웹에서 바로 사용할 수 있습니다.
   - Settings → Pages → Source: Deploy from a branch → main / (root)
   - 주소: `https://sheenss-design.github.io/henderson-hasselbalch-visualizer/`

## 기능

- 세 가지 계산 모드: pH / HCO₃ / pCO₂ 중 하나를 자동 계산
- 실시간 슬라이더 연동
- 산-염기 상태 표시 (정상/산증/알칼리증)
- HCO₃ : 용존 CO₂ 비율 표시
- 전형적인 산-염기 장애 프리셋

## 정상 범위 (동맥혈 기준)

| 항목 | 정상 범위 |
|------|-----------|
| pH | 7.35 – 7.45 |
| HCO₃⁻ | 22 – 26 mmol/L |
| pCO₂ | 35 – 45 mmHg |

> 교육 목적의 도구입니다. 실제 임상 판단에 사용하지 마세요.

## 로컬에서 실행

```bash
# 저장소 클론 후
open index.html   # macOS
# 또는 브라우저에서 파일 직접 열기
```