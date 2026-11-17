# seungjinchoi-05.github.io

최승진 포트폴리오 — GitHub Pages(`main` 브랜치 루트)로 배포되는 정적 사이트입니다. 빌드 단계가 없습니다.

| 경로 | 내용 | 피그마 |
|---|---|---|
| `/` | 포트폴리오 홈 (표지·About Me·Projects·Contact) | 웹 메인 `75:1410` › 웹 표지 `75:2395` |
| `/starbucks/` | Starbucks UI/UX Renewal 웹 쇼잉 | 콘텐츠 `66:1381` |
| `/annyeong-weg/` | Annyeong Weg 웹 쇼잉 | 콘텐츠 `74:929` |

외부 웹 쇼잉: 말모이 → https://leeyoujoungg.github.io/Malmoi/ · nexTree → https://nextree.framer.website/

## 프로젝트 웹 쇼잉 추가하기
1. `프로젝트명/` 폴더를 만들고 `starbucks/index.html`을 복사해 제목·설명·이미지 목록을 바꿉니다.
   좌측 상단 `SEUNGJIN` 링크(`https://seungjinchoi-05.github.io/`)는 그대로 둡니다.
2. 홈 `index.html`의 해당 카드에서 `<span class="card__go" … aria-disabled="true">`를
   `<a class="card__go" href="프로젝트명/" target="_blank" rel="noopener">↗</a>`로 바꿉니다.

## 구조
- `assets/site.css` — 공통 토큰과 GNB (홈·웹 쇼잉 공용)
- `assets/showcase.css` — 웹 쇼잉 페이지 레이아웃
- `assets/home/` — 표지 조리개 SVG(피그마에서 내보낸 원본), 프로필 사진, 카드 커버 원
