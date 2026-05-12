# [1차 프로젝트] 팀 7(칠)해드림

이 프로젝트는 이스트소프트 교육 모집 웹페이지의 메인페이지를 리뉴얼한 프로젝트입니다.
<br>
<br>

## 👥 팀 정보

- **팀명**: 7(칠)해드림
<br>

## 📅 프로젝트 개요

- **과정명**: 오르미캠프 프론트엔드 13기
- **제작기간**: 2026.05.06 ~ 2026.05.11 (총 6일)
- **개발환경**:
  - **Language**: HTML5, CSS3
  - **Tools**: Visual Studio Code, Git, GitHub
  - **Design**: Figma, FigJam

### 🔗 관련 링크

- **[Figma 디자인 가이드](https://www.figma.com/design/N1MXdC6zbEh08Q9GSEn96V/estbootcamp-design?node-id=69-268&t=FdAB4pE4hIDFy7MC-1)**
- **[Slides 발표 자료](https://www.figma.com/deck/yhQHtPIpOcckhutvmGf1RJ)**
<br>

## 📝 프로젝트 상세

### 1. 목표 및 역할

**목표**: 1단위기간 내의 HTML/CSS 수업 내용을 토대로 협업하여, 1920px 해상도를 기준으로 하되 모바일(767px 이하)까지 완벽하게 대응하는 리뉴얼 페이지 구현

| 이&nbsp;&nbsp;&nbsp;름&nbsp;   | 역&nbsp;&nbsp;&nbsp;할&nbsp; | 세부 담당                                                                                           | GitHub                                    | Email                  |
| :----- | :--- | :-------------------------------------------------------------------------------------------------- | :---------------------------------------- | :--------------------- |
| 주후산 | 팀장 | 기획 / 디자인 / 발표 / FE : HTML-nav,hero,course_list,footer_cta CSS-nav,hero,course_list,footer_cta | [bohem026](https://github.com/bohem026)   | microbin98@gmail.com   |
| 박은수 | 팀원 | 기획 / 디자인 / FE : HTML-nav,hero,footer                                                         | [jond0803](https://github.com/jond0803)   | jond0803@naver.com |
| 최성호 | 팀원 | 기획 / 디자인 / FE : HTML-FAQ & Quick-button CSS-FAQ & Quick-button                     | [RONNIECHOI0324](https://github.com/RONNIECHOI0324) | chltjdgh0001@naver.com |
| 최수민 | 팀원 | 기획 / 디자인 / FE : HTML-Recommendation & Benefits section, footer CSS-Target & Benefits section | [soomln](https://github.com/soomln)       | qnfehr948@gmail.com    |
| 최윤지 | 팀원 | 기획 / 디자인 / 회의록 작성 / FE : HTML-roadmap CSS-roadmap,footer                                 | [yoonji220](https://github.com/yoonji220) | choiyj220220@gmail.com |

### 2. 마일스톤

- **1일차(2026-05-06)**:
  - 디자인 및 HTML/CSS 파트 분배
  - 디자인 시안 작성
- **2일차**:
  - 디자인 시안 작업 마무리
  - 팀 Git/GitHub 설정
  - 공통 HTML/CSS 작성
- **3-4일차**:
  - 피드백 수정
  - 개인 파트 작업
- **5일차**:
  - 개인 파트 작업 마무리
  - 시안과 대조 비교 및 수정
  - 크로스 브라우저 테스트
  - 웹 표준 검사
- **6일차(2026-05-11)**:
  - 최종 배포
  - 발표 슬라이드 제작
 <div align="center">
  <img src="https://github.com/user-attachments/assets/a5abbd98-3d8e-4a58-8515-8d447ab74557" width="100%" alt="7해드림 간트차트" />
</div>

### 3. 주요 목표

- **전환 흐름 설계**: CTA 버튼 확대 배치와 종스크롤 중심의 레이아웃, 그리고 고정 퀵메뉴를 통해 지원 페이지까지 끊김 없는 사용자 동선을 구축
- **UI/레이아웃 구조 개선**: 카드 UI의 확장과 충분한 여백 확보, 그리고 텍스트 중심의 섹션 재정리를 통해 정보 탐색의 편의성과 가독성을 극대화
- **디자인 시스템 방향**: 단색 배경의 미니멀 디자인과 직관적인 인포그래픽을 활용하여 불필요한 요소를 제거하고 핵심 콘텐츠에 시각적 집중도를 부여
- **콘텐츠 및 인터렉션 강화**: 단계별 난이도 시각화와 차별화된 캐치프레이즈, 그리고 동적인 이벤트 효과를 적용하여 비전공자도 신뢰할 수 있는 매력적인 페이지를 완성
<br>

## 🚀 배포

- **[GitHub Pages](https://bohem026.github.io/est_fe_13_1st_project/)**
<br>

## 🛠 개발 컨벤션 가이드

프로젝트의 일관성을 위해 정의한 가이드라인입니다.

- **[HTML 작성 가이드](./docs/guide_html.md)**
- **[CSS 작성 가이드](./docs/guide_css.md)**
<br>

## 📂 프로젝트 구조

```text
📦ROOT
├── 📜index.html
├── 📂css
│   ├── common.css         # 공통 css(layout, container, 변수)
│   ├── flex-utility.css   # 공통 css(layout, container, 변수)
│   ├── font-utility.css   # 폰트 서식 클래스
│   ├── index.css          # 메인 페이지 전용 css
│   ├── normalize.css      # 브라우저 간 일관성 확보
│   └── reset.css          # 기본 css 제거
├── 📂image                # 이미지 폴더
├── 📂docs
│   ├── guide_html.md      # html 컨벤션 가이드
│   └── guide_css.md       # css 컨벤션 가이드
└── README.md
```
<br>

## 💡프로젝트 회고
- **협업을 통한 디자인 시스템 구축**: 각자 다른 섹션을 담당했음에도 불구하고, 디자인 컨셉을 유지하며 통일감 있는 웹페이지를 완성하는 과정에서 협업의 즐거움을 느꼈습니다.
- **실전 FE 업무 역량 강화**: HTML5/CSS3를 활용해 각 섹션의 구조를 직접 설계하며 반응형 레이아웃에 대한 이해도가 깊어짐을 느꼈고, 특히 실무 협업 워크플로우를 실전에서 익힐 수 있는 좋은 기회였습니다.
- **코드 컨벤션 가이드**: 초기 작업 시 코드 컨벤션 가이드를 더 엄격하게 맞췄다면 각자 작업한 CSS를 병합할 때 발생했던 레이아웃 이탈 문제를 손쉽게 해결할 수 있었을 것 같습니다.
- **Git 협업 숙달의 필요성**: Git 코드 복구나 강제 푸시 상황이 발생했을 때 브랜치 전략을 더 명확히 세워 충돌을 최소화하고 안정적인 버전 관리 프로세스를 구축하는 연습이 필요하다고 느꼈습니다.
