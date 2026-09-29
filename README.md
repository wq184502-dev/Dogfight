# Dogfight

브라우저에서 바로 실행되는 정적 HTML 게임이에요. 빌드나 서버가 필요 없어요.

`index.html` — 드래곤 플라이트: 자동 발사 종스크롤 슈팅, 보스전, 스킨 상점

## 배포 (Vercel)

저장소를 Import 하면 설정 없이 그대로 배포돼요. Framework Preset 은 **Other**, Build Command 와 Output Directory 는 비워 두세요.

## 저장 데이터

최고 점수, 포인트, 보유 스킨은 브라우저 `localStorage` 에 저장돼요(기기마다 따로).
