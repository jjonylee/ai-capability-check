# AI 역량 진단 · 올인원 (정적 사이트)

이 폴더에는 `index.html`(원본), `index_fixed.html`(URL 개행 버그 패치본), 그리고 히어로 이미지 자리표시자(`Image_fx.jpg`)가 들어있습니다.

## 빠른 배포 (3가지 택1)

### 1) Netlify Drop
- https://app.netlify.com/drop 접속 → 폴더 전체를 드래그&드롭 → 즉시 `*.netlify.app` URL 발급
- SPA 라우팅이 필요 없다면 추가 설정 불필요

### 2) GitHub Pages
- GitHub에 새 저장소 생성 → 이 폴더 내용 업로드(또는 푸시) → **Settings → Pages**에서 배포 브랜치 선택
- 잠시 후 `https://<계정>.github.io/<저장소>` 로 접속

### 3) Vercel
- https://vercel.com → New Project → GitHub 저장소 Import → Deploy → `*.vercel.app` URL

## 참고
- `index.html`은 원본이며, 일부 과정 링크에 개행이 섞여 클릭이 안 될 수 있어 `index_fixed.html`도 함께 제공됩니다.
- 히어로 이미지는 `Image_fx.jpg`로 루트에서 참조합니다. 실제 이미지를 같은 이름으로 교체하면 됩니다.
