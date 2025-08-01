# Daper 홈페이지

Daper 소프트웨어 솔루션 회사의 공식 홈페이지입니다.

## 포트폴리오 이미지 추가 방법

### 1. 이미지 파일 준비
- `assets/portfolio/` 폴더에 다음 이미지 파일들이 있습니다:
  - `foodbank_1.jpg` - 서울잇다푸드뱅크 마켓 앱 프로젝트 개요
  - `foodbank_2.jpg` - 개발 과정 및 팀 협업
  - `foodbank_3.jpg` - 완성된 마켓 앱 인터페이스
  - `foodbank_4.jpg` - 사회적 가치 실현 및 재능기부

### 2. 이미지 권장 사양
- **크기**: 800x600 픽셀 이상 (16:9 비율 권장)
- **형식**: JPG, PNG, WebP
- **파일 크기**: 각 이미지당 500KB 이하
- **품질**: 고해상도, 선명한 이미지

### 3. 이미지가 없는 경우
이미지 파일이 없어도 웹페이지가 정상적으로 작동합니다. 이미지 로드에 실패하면 자동으로 그라데이션 배경이 표시됩니다.

### 4. 현재 프로젝트
현재 포트폴리오에는 서울잇다푸드뱅크 마켓 어플리케이션 재능기부 프로젝트가 포함되어 있습니다. 이 프로젝트는 하나의 통합된 프로젝트로, 메인 카드와 3개의 갤러리 이미지로 구성되어 있습니다.

### 5. 추가 포트폴리오 아이템
새로운 프로젝트를 추가하려면:
1. `assets/portfolio/` 폴더에 이미지 파일 추가
2. `index.html`의 포트폴리오 섹션에 새로운 카드 추가
3. 이미지 경로와 프로젝트 정보 수정

## 파일 구조
```
01_codeFile/
├── index.html          # 메인 홈페이지
├── privacy.html        # 개인정보처리방침
├── CNAME              # 도메인 설정
├── assets/
│   ├── daper-logo.png  # 회사 로고
│   └── portfolio/      # 포트폴리오 이미지들
│       ├── foodbank_1.jpg
│       ├── foodbank_2.jpg
│       ├── foodbank_3.jpg
│       └── foodbank_4.jpg
└── README.md          # 이 파일
```

## 기술 스택
- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- 반응형 디자인

## 배포
이 웹사이트는 GitHub Pages를 통해 배포됩니다. 