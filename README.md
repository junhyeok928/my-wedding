# 💍 전준혁 & 공연주 웨딩 초대장

> 2026년 6월 27일 토요일 오후 4시 · CA웨딩컨벤션 루체홀 (KTX천안아산역 2층)

## 미리보기

GitHub Pages를 통해 배포된 웹 청첩장입니다.  
👉 [https://junhyeok928.github.io/my-wedding](https://junhyeok928.github.io/my-wedding)

## 기술 스택

- 순수 HTML / CSS / JavaScript (빌드 도구 없음)
- 카카오 지도 API
- 카카오 공유 SDK

## 주요 기능

- 히어로 사진 풀스크린 디스플레이
- 갤러리 3열 그리드 + 이미지 풀스크린 뷰어 (스와이프 지원)
- 실시간 D-Day 카운트다운 + 캘린더
- 카카오 지도 API 임베드 (CA웨딩컨벤션)
- 교통편 안내 (KTX·SRT·버스·자가용·주차)
- 계좌번호 아코디언 + 클립보드 복사
- 카카오톡 공유 / 링크 복사
- 다크 모드 디자인

## 로컬 실행

```bash
python -m http.server 8080
# http://localhost:8080/
```

## 카카오 API 설정

[Kakao Developers](https://developers.kakao.com) → 앱 설정 → 플랫폼 → Web에 배포 도메인 등록 필요

- **지도 API 키** : `index.html` 하단 스크립트 태그의 `appkey` 값
- **공유 SDK 키** : `shareKakao()` 함수 내 `Kakao.init()` 호출 시 사용

## 이미지 교체

| 파일 | 용도 |
|------|------|
| `img/hero.png` | 히어로 메인 사진 |
| `img/02.jpg ~ img/10.jpg` | 갤러리 사진 (9장 · 3×3) |
| `img/thumb.jpg` | 카카오 공유 썸네일 |
