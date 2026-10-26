# 하늘에서 본 대전展 — 도슨트 사이트 (최종)

이 폴더 안의 파일을 GitHub 저장소 **맨 위(루트)** 에 그대로 올리면 됩니다.

```
index.html     도슨트 페이지 (구역은 #home #prologue #timeline #station #battle #bombing #targets #airfield #now #epilogue)
ar.html        대전전투 AR 페이지
img/           전시 사진 (웹용)
vendor/        AR 라이브러리
targets/       AR 인식용 데이터
```

접속 주소: https://jeongsi86.github.io/DaejeonSky/

## 나중에 고칠 곳
- **그때와 지금** 설명: `index.html`에서 `DESCRIPTION-SLOT` 주석을 찾아 그 자리에 `<div class="read"><p>설명</p></div>` 를 넣으면 됩니다.
- AR 핀 문구: `ar.html`의 `PINS` 항목 (현재 초안 문구, 확인 후 교체 필요). 자세한 방법은 `README-AR.md`.
