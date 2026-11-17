# 입실 마감 08:10

수능 시험장 입구 검색대에서 AI 부정행위자를 가려내는 판별 게임입니다.
설치나 빌드 없이 이 폴더를 그대로 웹에 올리면 됩니다 (정적 사이트).

## 폴더 구성

| 경로 | 내용 |
|---|---|
| `index.html` | 게임 본체 |
| `lib/` | three.js 0.160.0, three-vrm 3.1.0 (인터넷 CDN 없이 동작하도록 포함) |
| `models/` | 캐릭터 VRM 모델 4개 (약 30MB) |
| `CREDITS.md` | 사용한 모델과 라이브러리의 출처·라이선스 |

글꼴만 Google Fonts에서 받아옵니다. 인터넷이 없으면 기본 글꼴로 표시됩니다.

## 배포 방법

### itch.io (게임 배포에 추천)
1. 이 폴더를 통째로 zip으로 압축합니다. zip을 열었을 때 바로 `index.html`이 보여야 합니다.
2. itch.io → Upload new project → Kind of project: **HTML**.
3. zip 업로드 후 **This file will be played in the browser** 체크.
4. Embed options: 뷰포트 1280 × 900, **Fullscreen button** 켜기, Mobile friendly 켜기.

### Netlify Drop (가장 빠름)
https://app.netlify.com/drop 에 이 폴더를 끌어다 놓으면 바로 주소가 생깁니다.

### GitHub Pages
1. 이 폴더 내용을 저장소에 올립니다 (예: `docs/` 폴더 또는 별도 저장소의 루트).
2. 저장소 Settings → Pages → Branch와 폴더를 선택하고 저장합니다.

## 내 컴퓨터에서 실행
`index.html`을 더블클릭하면 브라우저 보안 정책 때문에 동작하지 않습니다. 이 폴더에서 웹 서버를 켜세요.

```
python -m http.server 8000
```

그다음 브라우저에서 http://localhost:8000 을 엽니다.

## 조작
- 몸의 부위를 클릭: 확대 / 드래그: 돌리기 / 휠·핀치: 줌
- 빈 곳 클릭, 우클릭, Space, Esc, "← 전체 보기": 전체 보기로 돌아가기
- 단축키 1~7: 육안 확인, 금속탐지기, 정밀수색, 필통 검사, 명단 조회, 전파탐지기, 생년월일 질문
