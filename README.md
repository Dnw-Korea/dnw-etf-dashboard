# dnw-etf-dashboard
DNW 회비 운용 가즈아ㅏㅏ

## 운영 방식

- `index.html`: 대시보드 레이아웃, 디자인, 차트 렌더링 로직, 기준일/예수금/종목/수량/가격/수익률/메모 데이터를 모두 포함합니다.
- 별도 `data.json` 파일을 사용하지 않는 단일 HTML 파일 구조입니다.

일일 업데이트나 종목 교체는 `index.html` 내부의 `DASHBOARD_DATA` 값을 수정하면 됩니다.
