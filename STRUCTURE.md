# STRUCTURE · kirakira-sample (v0.1 · 홀로그램 스파클 · 배포 예정 kirakira-sample.lgt3232.workers.dev)

```
kirakira-sample/
├─ index.html                     단일 파일 (CSS · JS 인라인)
├─ wrangler.toml                  name = kirakira-sample
├─ .assetsignore                  img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ kk-playfair.woff2 · kk-playfair-i.woff2   영문 제목 · 라벨 (Playfair Display 400–600 정체 · 이탤릭, 영문만)
├─ kk-pretendard.woff2            본문 · 한글 (Pretendard 300–700, 페이지 글자 전부)
├─ kk-logo.webp                   홀로그램 별 로고 (히어로 · 푸터, multiply)
├─ kk-hero.webp                   히어로 네일
├─ kk-n1 ~ kk-n10 .webp           네일 갤러리 9장 + 가격 카드 1장(n10)
├─ kk-chart.webp                  아트 차트판
├─ kk-lash.webp · kk-brow.webp    가격 카드(속눈썹 · 눈썹)
├─ favicon.png · og-kk.jpg
├─ img/                           다올 제공 원본 84장 + _원문.md (배포 제외 · 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ 900px 미만 `.snav`) → 히어로(#FFFFFF) → `#promise`(#F8F6FB) → `#nail` 갤러리 + 차트판(#FFFFFF) → `#price` 가격 카드 6(#F8F6FB) → `#notice`(#FFFFFF) → `#visit`(#F8F6FB · 지도) → 푸터 + 모바일 `.quick`.

## 버튼 · 링크
- 네이버 예약 `https://m.place.naver.com/place/2097671533/ticket`(메인): 헤더 · 히어로 · 오시는 길 · 하단 바
- 전화 `tel:050714387565`: 히어로 · 오시는 길 · 푸터 · 하단 바
- 인스타 `https://www.instagram.com/kirakira._official/`: 히어로 · 오시는 길 · 푸터 · 하단 바
- 네이버 길찾기 `map.naver.com/p/entry/place/2097671533` · 네이버 플레이스(푸터)

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 Pretendard만, Playfair는 영문만.
