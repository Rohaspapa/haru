# 하루

폰에 귀속되는 개인 자기관리 앱. 모든 데이터는 브라우저(localStorage)에만 저장됩니다.

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소를 만든다 (예: `haru`).
2. 이 폴더의 파일 전부(`index.html`, `manifest.json`, `icon-*.png`)를 업로드한다.
3. 저장소 **Settings → Pages** 로 간다.
4. **Source**를 `Deploy from a branch`, 브랜치를 `main`, 폴더를 `/ (root)`로 설정하고 저장.
5. 1~2분 뒤 `https://<아이디>.github.io/haru/` 로 접속된다.

## 폰 홈 화면에 추가 (iPhone)

1. Safari로 위 주소를 연다.
2. 공유 버튼 → **홈 화면에 추가**.
3. 💪 아이콘으로 추가된다. 전체화면 앱처럼 실행됨.

## 설정 바꾸기 (index.html 상단 script)

- `DAILY_ROUTINES` : 매일 쌓기 루틴 / 운동 주 목표 횟수
- `DEEP_SCHEDULE` : 요일별 집중 과제
- `AOKC_URL` : 운동 카드의 AOKC 앱 링크
- `LEVELS` : 누적일수 레벨 단계
- `MONTHLY_FREE` : 한 달 자유 용돈 한도

## 주의

- 데이터는 이 사이트 주소의 브라우저 저장소에만 있습니다. 주소가 바뀌면 기록이 안 보입니다.
- 사파리 방문기록/캐시를 완전 삭제하면 기록도 지워집니다.
