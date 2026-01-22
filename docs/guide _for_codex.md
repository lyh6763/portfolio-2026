# Codex 작업 지침서

> 이 문서는 my-portfolio 프로젝트에서 Codex가 참고해야 할 지침입니다.
> 항상 작업 결과물 vs 사용자 요구 혹은 지침이 충돌할 경우, 반드시 사용자의 지침 혹은 요구를 준수합니다.
> 모든 작업은 실행에 옮기기 전 사용자에게 허가를 받습니다.
> 폴더 내 파일은 사용자의 허가가 없는 한, 함부로 접근하고 변경하거나 삭제하지 않습니다.
> 모든 작업은 반드시 한국어로 진행합니다.
> 작업 전 반드시 읽고, 모든 규칙을 준수해주세요.

---

# 포트폴리오 & 자기소개 페이지 기획서

## 1. 프로젝트 개요

### 1.1 프로젝트명
**My-Portfolio** - Web Publisher

### 1.2 목적
- 웹 퍼블리셔 직무 지원을 위한 온라인 포트폴리오
- 기술 역량과 프로젝트 경험을 효과적으로 전달
- 채용 담당자에게 강한 첫인상 제공

### 1.3 핵심 가치
- **사용자 중심 설계**: 웹 퍼블리셔로서의 철학 반영
- **인터랙티브 경험**: 웹 퍼블리싱 기술력 시연
- **전문성과 개성의 균형**: 차별화된 개인 브랜딩

---

## 2. 타겟 사용자

### 주요 타겟
- IT 기업 채용 담당자 및 실무진
- UX/UI 디자인 팀 리더
- 프론트엔드 개발팀 매니저

### 사용자 니즈
- 빠른 시간 내 지원자 역량 파악
- 실무 투입 가능성 판단
- 포트폴리오 작품의 질적 수준 확인
- 협업 가능성 및 커뮤니케이션 능력 평가

---

## 3. 페이지 구조

### 3.1 사이트맵
```
Home (One-Page Scroll)
├── Hero Section
├── About Me
├── Skills
├── Projects
│   ├── Project 1: MARHSALL
│   ├── Project 2: DUOBACK
│   └── Project 3: [추가 프로젝트]
├── Experience & Education
├── Contact
└── Footer
```

### 3.2 네비게이션
- **Fixed Header**: 스크롤 시 자동 숨김/표시
- **Smooth Scroll**: 섹션 간 부드러운 이동
- **Progress Indicator**: 현재 위치 시각화

---

## 4. 섹션별 상세 기획

### 4.1 Hero Section
**목표**: 3초 안에 강렬한 인상 전달

**구성 요소**:
- **주요 카피**: (임시로 작성)
- **서브 카피**: Web Publisher
- **비주얼**: 인터랙티브 배경 (Canvas/WebGL) 또는 미니멀 애니메이션
- **CTA 버튼**: "프로젝트 보기" / "이력서 다운로드"

**인터랙션**:
- 마우스 움직임에 반응하는 패럴랙스 효과
- 타이핑 애니메이션 또는 페이드인 효과

---

### 4.2 About Me
**목표**: 전문성과 인간적 매력 동시 전달

**구성 요소**:
- **프로필 이미지**: 전문적이면서 친근한 느낌
- **자기소개 텍스트**:
  - SBS Academy 웹 퍼블리셔 과정 수료 (2026.01)
  - 사용자 경험과 개발의 교차점에서 가치를 만드는 웹 퍼블리셔
  - 사용자 경험을 최우선으로 고려하는 개발 철학
- **핵심 가치**:
  - 사용자 중심 설계
  - 디테일에 대한 집착
  - 지속적인 학습과 성장

**레이아웃**:
- 2-column 레이아웃 (이미지 + 텍스트)
- 모바일: 1-column으로 전환

---

### 4.3 Skills
**목표**: 기술 스택을 명확하고 시각적으로 표현

**카테고리별 분류**:

#### Front-end Development
- **Core**: HTML5, CSS3, JavaScript (ES6+)
- **Framework/Library**: React, Vue.js (선택적)
- **Styling**: Sass/SCSS, Tailwind CSS, Styled-components

#### UX/UI Implementation
- **반응형 디자인**: Mobile-first approach
- **접근성**: WAI-ARIA, 시맨틱 마크업
- **성능 최적화**: 이미지 최적화, 코드 스플리팅

#### Tools & Workflow
- **디자인 툴**: Figma, Adobe Photoshop, Adobe Illustrator
- **버전 관리**: Git/GitHub
- **협업**: Notion

#### Additional Skills
- **언어**: 한국어 (Native), 영어, 중국어 (HSK 5급)

**시각화 방식**:
- 스킬 카드 또는 아이콘 그리드
- Hover 시 상세 설명 표시
- 숙련도를 표현하는 인터랙티브 요소 (선택적)

---

### 4.4 Projects
**목표**: 실무 역량을 구체적으로 증명

**프로젝트 카드 구성**:
- **썸네일 이미지**: 프로젝트 대표 이미지
- **프로젝트명**: 명확하고 임팩트 있는 제목
- **한 줄 소개**: 프로젝트 핵심 가치
- **사용 기술**: 기술 스택 태그
- **CTA**: "자세히 보기" 버튼 → 상세 페이지 또는 모달

**프로젝트 1: MARSHALL 리디자인**
- **개요**: 사용자 경험 개선을 위한 웹페이지 리디자인
- **역할**: UX 기획, UI 디자인, 프론트엔드 개발
- **핵심 성과**:
  - 사용자 여정 분석을 통한 정보 구조 재설계
  - 인터랙티브 제품 소개 섹션 구현
  - 반응형 디자인 및 접근성 준수
- **기술 스택**: HTML5, CSS3, JavaScript, Figma
- **링크**: Live Demo

**프로젝트 2: DUOBACK 리디자인**
- **개요**: 사용자 경험 개선을 위한 웹페이지 리디자인
- **역할**: UX 기획, UI 디자인, 프론트엔드 개발
- **핵심 성과**:
  - 사용자 여정 분석을 통한 정보 구조 재설계
  - 인터랙티브 제품 소개 섹션 구현
  - 반응형 디자인 및 접근성 준수
- **기술 스택**: HTML5, CSS3, JavaScript, Figma
- **링크**: Live Demo

**레이아웃**:
- Grid 레이아웃 (Desktop: 2-3열, Mobile: 1열)
- Hover 시 확대 또는 정보 오버레이 효과

---

### 4.5 Experience & Education
**목표**: 학습 경로와 성장 과정 제시

**Education**
- **SBS Academy Computer Art School**
  - 웹 퍼블리셔 과정 수료함
  - 기간: 2024.10 ~ 2026.01
  - 주요 학습: HTML/CSS/JS, 반응형 웹, UI/UX

**Certificates & Activities**
- TOEIC 준비 중
- HSK 5급

**Timeline 시각화** (선택적)
- 수평 타임라인으로 학습 여정 표현

---

### 4.6 Contact
**목표**: 연락 장벽 최소화

**구성 요소**:
- **이메일**: 클릭 시 메일 클라이언트 실행
- **GitHub**: 프로필 링크
- **LinkedIn**: 프로필 링크 (있다면)
- **Resume**: PDF 다운로드 버튼

**Contact Form** (선택적):
- 이름, 이메일, 메시지 입력
- EmailJS 또는 Formspree 활용

**디자인**:
- 미니멀하고 직관적인 레이아웃
- 큰 클릭 영역으로 모바일 친화적

---

## 5. 디자인 방향성

### 5.1 비주얼 컨셉
**키워드**: Modern, Dynamic, Professional, Approachable

### 5.2 컬러 팔레트
**Option 1: Professional Blue**
- Primary: #2563EB (Blue)
- Secondary: #7C3AED (Purple)
- Accent: #F59E0B (Amber)
- Background: #FFFFFF / #F9FAFB
- Text: #111827 / #6B7280

**Option 2: Contemporary Mono**
- Primary: #18181B (Zinc)
- Secondary: #3B82F6 (Blue)
- Accent: #10B981 (Emerald)
- Background: #FFFFFF / #FAFAFA
- Text: #09090B / #71717A

**Option 3: Others**
- 5.1 비주얼 컨셉에서 제시한 키워드에 맞게 알맞은 컬러 팔레트 선정

### 5.3 타이포그래피
컬러 팔레트 Option 3 선택 시, 타이포그래피 또한 그에 맞게 선정할 것

- **한글**: Pretendard, SUIT, Noto Sans KR
- **영문**: Inter, Poppins, SF Pro
- **계층 구조**:
  - H1: 48px~64px (Hero)
  - H2: 36px~48px (Section Title)
  - H3: 24px~32px (Sub Title)
  - Body: 16px~18px
  - Caption: 14px

### 5.4 레이아웃 시스템
- **Grid**: 12-column grid
- **Spacing**: 8px 기반 스페이싱 시스템
- **Container**: Max-width 1280px
- **Breakpoints**:
  - Mobile: < 640px
  - Tablet: 640px ~ 1024px
  - Desktop: > 1024px

### 5.5 인터랙션 & 애니메이션
- **원칙**: 사용성을 해치지 않는 선에서 적용
- **적용 영역**:
  - 스크롤 기반 애니메이션 (Intersection Observer)
  - Hover 상태 트랜지션
  - 페이지 로드 애니메이션
- **성능 고려**: GPU 가속 속성 우선 (transform, opacity)

---

## 6. 기술 스택

### 6.1 개발 환경
**Option A: Static Site (권장 - 빠른 구현)**
- HTML5, CSS3, Vanilla JavaScript
- Parcel 또는 Vite (번들러)
- GitHub Pages 배포

**Option B: React (확장성)**
- React 18+
- Vite
- Styled-components 또는 Tailwind CSS
- Framer Motion (애니메이션)
- Vercel 배포

### 6.2 추가 라이브러리 (필요시)
- **애니메이션**: GSAP, Framer Motion, AOS
- **스크롤**: Locomotive Scroll, Lenis
- **폼**: EmailJS, Formspree
- **아이콘**: Font Awesome, React Icons

### 6.3 성능 최적화
- 이미지 최적화: WebP 포맷, Lazy Loading
- 코드 스플리팅
- Lighthouse 점수 90+ 목표

### 6.4 접근성
- Semantic HTML
- ARIA 레이블
- 키보드 네비게이션 지원
- 적절한 색상 대비

---

## 7. 개발 일정

### Phase 1: 기획 & 디자인 (1주)
- [x] 기획서 작성
- [ ] 와이어프레임 제작
- [ ] 시안 디자인 (Figma)
- [ ] 콘텐츠 준비 (텍스트, 이미지)

### Phase 2: 개발 (2주)
- [ ] 개발 환경 셋업
- [ ] 레이아웃 구조 구현
- [ ] 각 섹션 개발
  - [ ] Hero
  - [ ] About
  - [ ] Skills
  - [ ] Projects
  - [ ] Experience
  - [ ] Contact
- [ ] 반응형 구현
- [ ] 인터랙션 & 애니메이션 추가

### Phase 3: 테스트 & 최적화 (3~5일)
- [ ] 크로스 브라우징 테스트
- [ ] 성능 최적화
- [ ] 접근성 점검
- [ ] 모바일 디바이스 테스트

### Phase 4: 배포 & 런칭 (1~2일)
- [ ] 도메인 연결 (선택)
- [ ] GitHub Pages / Vercel 배포
- [ ] SEO 최적화 (메타 태그, OG 이미지)
- [ ] Analytics 설정

---

## 8. 성공 지표

### 정량적 지표
- Lighthouse 성능 점수 90+
- 페이지 로딩 시간 < 3초
- 모바일 친화성 100%

### 정성적 지표
- 채용 담당자 피드백
- 포트폴리오를 통한 인터뷰 연결률
- 전문성과 개성의 균형

---

## 9. 향후 확장 계획

### 단기 (1~3개월)
- 블로그 섹션 추가 (기술 학습 기록)
- 다크 모드 지원
- 다국어 지원 (한/영)

### 장기 (3~6개월)
- 인터랙티브 코드 데모
- 케이스 스터디 상세 페이지
- 이력서 빌더 기능

---

## 10. 참고 자료

### 포트폴리오 레퍼런스
- Awwwards 수상작
- 국내외 UX 엔지니어 포트폴리오
- Dribbble, Behance 우수 사례

### 기술 문서
- MDN Web Docs
- React 공식 문서
- Web.dev (성능 최적화)

---

## Appendix

### A. 콘텐츠 체크리스트
- [ ] 프로필 사진
- [ ] 자기소개 텍스트
- [ ] 프로젝트 스크린샷
- [ ] 이력서 PDF
- [ ] 연락처 정보

### B. 브랜딩 요소
- [ ] 로고 디자인 (선택)
- [ ] 파비콘
- [ ] OG 이미지

---

**작성일**: 2025-01-22  
**최종 수정일**: 2025-01-22  
**버전**: 1.0