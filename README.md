# Philo — 오늘의 철학

철학책 문구를 감정별로 매일 읽는 앱.

## 구성

- `index.html` — 단일 파일 앱 (의존성 없음)

## 카테고리

| 카테고리 | 설명 |
|---|---|
| 🌧 우울할 땐 | 무기력·슬픔·공허함 |
| 🌀 불안할 땐 | 두려움·걱정·막막함 |
| 🧭 길을 잃었을 땐 | 방향·정체성·선택 |
| 🔥 분노할 땐 | 부당함·좌절·억울함 |
| 💫 사랑할 땐 | 관계·그리움·연결 |
| ✨ 의미를 찾을 땐 | 삶의 목적·성장·깨달음 |

## 배포

### Vercel

```bash
npx vercel
```

또는 [vercel.com](https://vercel.com) 에서 GitHub 레포 연결 후 자동 배포.

### GitHub Pages

1. 레포 Settings → Pages
2. Source: `main` 브랜치, `/ (root)` 선택
3. Save → 자동 배포

### 로컬 실행

```bash
# 그냥 브라우저로 열기
open index.html

# 또는 간단한 서버
npx serve .
python3 -m http.server 3000
```

## 기술 스택

- Vanilla HTML / CSS / JS
- 외부 의존성 없음 (Google Fonts CDN 제외)
- 단일 파일 (`index.html`)
