# Terra Consulting Group

테라컨설팅그룹 공식 웹사이트.

## 로컬에서 실행

### 방법 1 — 파일 직접 열기 (가장 간단)
```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### 방법 2 — 로컬 서버 (지도 iframe 등 일부 기능 안정성 향상)
```bash
python3 -m http.server 8080
# 브라우저에서 http://localhost:8080 접속
```

또는 Node.js:
```bash
npx serve .
```

## 구조
```
index.html       # 메인 페이지 (CSS/JS 인라인)
assets/
  └── logo.png   # 회사 로고 (투명 배경)
project/         # 원본 디자인 번들 (참고용)
```

## 배포
GitHub Pages: https://lhasan.github.io/terracg/

수정 후 push하면 1-2분 내 자동 반영됩니다.
```bash
git add . && git commit -m "메시지" && git push
```
