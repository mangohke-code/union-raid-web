# union-raid-web

NIKKE 유니온 레이드 결산 시트의 화면 코드 배포용 저장소입니다.
각 유니온 시트의 Apps Script 가 여기의 `app.html` 을 받아 화면을 띄웁니다.

- `app.html` — 모든 유니온에 적용되는 화면
- `dev/app.html` — 시험용 (사이트 주소 뒤 `?ch=dev`)

이 저장소의 파일은 직접 고치지 말고, 원본 폴더에서 `python 배포.py dev|live` 로 올립니다.
