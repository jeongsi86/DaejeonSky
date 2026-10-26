# 하늘에서 본 대전展 — 도슨트 사이트 (최종)

이 폴더 안의 파일과 폴더를 GitHub 저장소 **맨 위(루트)** 에 그대로 올리면 됩니다. 폴더 구조가 그대로 유지되어야 합니다.

```
index.html     도슨트 페이지 (#home #prologue #timeline #station #battle #bombing #targets #airfield #now #epilogue #virtual)
ar.html        대전전투 AR 페이지
virtual/       가상 전시장 (index.html 한 파일)
img/           전시 사진 (웹용)
vendor/        AR 라이브러리
targets/       AR 인식용 데이터
```

접속 주소: https://jeongsi86.github.io/DaejeonSky/

## 올릴 때 주의
압축 파일 안에서 바로 끌어 올리면 파일 이름과 내용이 뒤섞이거나 폴더가 사라질 수 있습니다. 반드시 압축을 먼저 푼 뒤, 터미널(git) 또는 GitHub Desktop으로 올리세요. 웹으로 올린다면 커밋 전에 목록에 `img/poster.jpg` 처럼 폴더 경로가 보이는지 확인하세요.
올린 뒤 `…/DaejeonSky/img/poster.jpg` 와 `…/DaejeonSky/virtual/` 이 열리는지 확인합니다.

## 가상 전시장
홈페이지의 [가상 전시 관람] 버튼은 홈페이지 안(`#virtual`)에서 가상 전시장을 열고, 위쪽의 [← 홈으로] 버튼으로 언제든 돌아올 수 있습니다. [새 창]을 누르면 `virtual/` 만 따로 열립니다. 가상 전시장 파일을 고치면 `virtual/index.html` 만 교체하면 됩니다.

## 나중에 고칠 곳
- **그때와 지금** 설명: `index.html`에서 `DESCRIPTION-SLOT` 주석을 찾아 그 자리에 `<div class="read"><p>설명</p></div>` 를 넣습니다.
- AR 핀 설명: `ar.html`의 `PINS` 항목에 `text:'설명'` 을 추가합니다. 자세한 방법은 `README-AR.md`.
- 링크 미리보기(카카오톡 등) 이미지는 `img/og-thumb.jpg` 입니다. 이미 공유한 주소는 메신저가 이전 이미지를 기억해 한동안 바뀌지 않을 수 있습니다.
