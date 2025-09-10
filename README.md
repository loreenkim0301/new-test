# My First Repo - 간단한 로그인 페이지

![Login Page Preview](https://img.shields.io/badge/React-18.3.1-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.1-blue?logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-5.4.2-purple?logo=vite)

## 📋 프로젝트 개요

현대적이고 아름다운 로그인 페이지를 구현한 React 프로젝트입니다. 사용자 친화적인 UI/UX와 완전한 반응형 디자인을 제공합니다.

## ✨ 주요 기능

### 🔐 인증 기능
- **이메일 로그인**: 실시간 이메일 형식 유효성 검사
- **비밀번호 보안**: 비밀번호 표시/숨김 토글 기능
- **로그인 유지**: "로그인 상태 유지" 옵션
- **에러 처리**: 명확한 에러 메시지 및 사용자 피드백

### 🎨 디자인 특징
- **현대적 UI**: 깔끔한 카드형 레이아웃
- **그라데이션 배경**: 파란색에서 보라색으로 이어지는 아름다운 배경
- **애니메이션**: 부드러운 호버 효과 및 트랜지션
- **아이콘**: Lucide React를 활용한 직관적인 아이콘
- **반응형**: 모바일, 태블릿, 데스크톱 완벽 지원

### 🚀 사용자 경험
- **실시간 검증**: 입력과 동시에 유효성 검사
- **로딩 상태**: 제출 중 시각적 피드백
- **접근성**: 스크린 리더 및 키보드 네비게이션 지원
- **중복 방지**: 로딩 중 버튼 비활성화

## 🛠️ 기술 스택

### Frontend
- **React 18.3.1**: 최신 React 훅 및 함수형 컴포넌트
- **TypeScript 5.5.3**: 타입 안전성 및 개발 생산성
- **Tailwind CSS 3.4.1**: 유틸리티 우선 CSS 프레임워크
- **Lucide React**: 아름다운 SVG 아이콘 라이브러리

### Development Tools
- **Vite 5.4.2**: 빠른 개발 서버 및 빌드 도구
- **ESLint**: 코드 품질 및 일관성 유지
- **PostCSS**: CSS 후처리 및 최적화

## 📦 설치 및 실행

### 필수 요구사항
- Node.js 18.0.0 이상
- npm 또는 yarn

### 설치 방법

```bash
# 저장소 클론
git clone https://github.com/YOUR_USERNAME/my-first-repo.git
cd my-first-repo

# 의존성 설치
npm install

# 개발 서버 실행
npm run dev
```

### 사용 가능한 스크립트

```bash
# 개발 서버 실행 (http://localhost:5173)
npm run dev

# 프로덕션 빌드
npm run build

# 빌드된 앱 미리보기
npm run preview

# 코드 린팅
npm run lint
```

## 📁 프로젝트 구조

```
my-first-repo/
├── public/                 # 정적 파일
├── src/
│   ├── App.tsx            # 메인 로그인 컴포넌트
│   ├── main.tsx           # React 앱 진입점
│   ├── index.css          # Tailwind CSS 설정
│   └── vite-env.d.ts      # Vite 타입 정의
├── index.html             # HTML 템플릿
├── package.json           # 프로젝트 설정
├── tailwind.config.js     # Tailwind 설정
├── tsconfig.json          # TypeScript 설정
└── vite.config.ts         # Vite 설정
```

## 🎯 사용법

1. **이메일 입력**: 유효한 이메일 주소를 입력하세요
2. **비밀번호 입력**: 최소 6자 이상의 비밀번호를 입력하세요
3. **로그인 유지**: 필요시 "로그인 상태 유지" 체크박스를 선택하세요
4. **로그인**: 로그인 버튼을 클릭하여 인증을 진행하세요

## 🔧 커스터마이징

### 색상 테마 변경
`tailwind.config.js` 파일에서 색상 팔레트를 수정할 수 있습니다.

### 폼 유효성 검사 규칙
`src/App.tsx`의 `validateForm` 함수에서 검증 로직을 수정할 수 있습니다.

### 스타일링
Tailwind CSS 클래스를 수정하여 디자인을 변경할 수 있습니다.

## 🚀 배포

### Vercel 배포
```bash
npm run build
# Vercel CLI 또는 웹 인터페이스를 통해 배포
```

### Netlify 배포
```bash
npm run build
# dist 폴더를 Netlify에 업로드
```

## 🤝 기여하기

1. 이 저장소를 포크하세요
2. 새로운 기능 브랜치를 생성하세요 (`git checkout -b feature/amazing-feature`)
3. 변경사항을 커밋하세요 (`git commit -m 'Add some amazing feature'`)
4. 브랜치에 푸시하세요 (`git push origin feature/amazing-feature`)
5. Pull Request를 생성하세요

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

## 📞 연락처

프로젝트에 대한 질문이나 제안사항이 있으시면 언제든지 연락해주세요!

**제작자**: loreen@selectway.co.kr

---

**LoginPage v1.0.1 (2025.01.27)**

> 💡 **Tip**: 이 프로젝트는 학습 목적으로 제작되었습니다. 실제 프로덕션 환경에서 사용하기 전에 보안 검토를 받으시기 바랍니다.