# Portfolio Final QA

## 기준일

2026-04-23

## 배포 상태

- Portfolio: https://lyh6763.github.io/portfolio-2026/
- DUOBACK React: https://lyh6763.github.io/duoback-react/
- GitHub Pages workflow: portfolio-2026, duoback-react 모두 성공 확인

## Projects 링크 확인

- MARSHALL: 정상 응답 확인
- DUOBACK: 정상 응답 확인
- DUOBACK React: 정상 응답 확인
- LEVI'S: 미배포 상태이므로 카드 CTA를 `준비 중`으로 비활성 처리

## 시각 QA

- 모바일 390px: 히어로, 요약 카드, About 초입 텍스트 overflow 수정 및 캡처 확인
- 데스크톱 1440px: 히어로 레이아웃 유지 확인
- Projects 섹션: 카드 노출 및 링크 상태 확인

## 메타/공유 정보

- canonical, og:url, twitter:url을 portfolio-2026 배포 URL로 정리
- og:image, twitter:image를 실제 존재하는 `images/projects/marshall-16x9.jpg`로 연결

## 남은 참고 항목

- `.claude/` 폴더는 로컬 미추적 항목으로 유지
- LEVI'S 프로젝트가 배포되면 CTA를 실제 링크로 복구
