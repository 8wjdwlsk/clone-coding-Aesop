# Aesop 메인페이지 클론코딩

> 실제 서비스 중인 Aesop 메인페이지를 분석하고 동일하게 구현한 클론코딩 프로젝트입니다.

<br>

## 프로젝트 개요

| 항목 | 내용 |
|------|------|
| 작업 기간 | 2025.05 (2주) |
| 역할 | 마크업 · CSS 설계 · JS 인터랙션 전담 |
| 목표 | 원본 레이아웃 재현 및 JS 인터랙션 구현 |
| 사용 기술 | HTML / CSS / Vanilla JS |

<br>

## 사용 기술

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

<br>

## 구현 기능

### 레이아웃
- Flex / Grid 기반 레이아웃 설계
- 2단 헤더 구조 (초기 2줄 / 스크롤 1줄)
- 미디어 섹션 좌우 분할 레이아웃

### 인터랙션
- 공지 배너 X 버튼 닫기
- 헤더 투명 → 스크롤 올릴 때 배경색 전환 + 로고 이미지 교체
- 헤더 호버 시 배경색 전환 + 로고 이미지 교체
- 스크롤 내릴 때 헤더 숨김 / 올릴 때 헤더 노출
- 메가 드롭다운 메뉴 (10개 카테고리별 서브메뉴 + 이미지)
- 제품 슬라이더 (5개 제품, 하나씩 이동)
- 제품 이미지 호버 시 이미지 교체 (opacity 트랜지션)
- 사이즈 버튼 클릭 시 가격 실시간 변경
- 스크롤 Fade-up 애니메이션 (IntersectionObserver)

### 반응형
- PC 기준 구현

<br>

## 파일 구조

```
aesop-clone/
├── index.html
├── css/
│   └── index.css
├── img/
│   └── ...
└── video/
    └── ...
```

<br>

## 핵심 학습

- 2단 헤더 구조 설계 및 JS 기반 상태 전환
- `mouseenter` / `mouseleave` 를 활용한 로고 이미지 교체
- `position: fixed` 메가 드롭다운 구현
- `flex` 기반 슬라이더 + `transform: translateX` 로 슬라이드 구현
- `data-prices` 속성으로 사이즈별 가격 데이터 관리
- `opacity` 트랜지션을 활용한 이미지 호버 효과
- `IntersectionObserver` 스크롤 애니메이션

<br>

## 참고

- 원본 사이트: [aesop.com](https://www.aesop.com/kr/)
- 본 프로젝트는 학습 목적으로 제작되었습니다.
