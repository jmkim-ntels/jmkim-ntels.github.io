# Section Publishing Guide

사이트 섹션 구조:

- /tech-report/
- /finance-stock-report/
- /medical-health-report/
- /weather-report/

공통 규칙:

1. 실제 문서는 각 섹션의 `source/` 폴더에 저장
2. 파일명에는 가능하면 날짜(`YYYY-MM-DD`) 포함
3. 섹션 `index.html`은 날짜별 링크 목록 유지
4. 홈(`/index.html`)에는 섹션 진입 링크만 유지
5. HTML은 바로 보기, MD/DOCX는 원본/다운로드용으로 허용

예시:
- /tech-report/source/2026-04-16-daily-tech-briefing.html
- /finance-stock-report/source/2026-04-16-us-market-briefing.md
- /medical-health-report/source/2026-04-16-health-summary.html
- /weather-report/source/2026-04-16-morning-weather.html
