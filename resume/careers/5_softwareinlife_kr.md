[이력서](../README_KR.md) &gt; [소프트웨어인라이프](./5_softwareinlife_kr.md)

# 소프트웨어인라이프

- 2021-04-26 ~ 2021-11-12 (6개월)
- FE 개발자로 합류하여 3인 팀을 이끌고, 디자인 시스템을 설계하고 구축했습니다.

## 주요 기술 스택

- TS, React, MobX, Emotion, Storybook, Lerna

## 주요 프로젝트

### 차세대 ERP 프로젝트

- 목적: 클라이언트 요구사항을 반영하여 유지보수성과 확장성이 높은 차세대 ERP 시스템 개발
- 기간: 6개월
- 인원: 3명
- 역할 및 기여: 팀 리드 및 핵심 아키텍처 설계, 개발 60% (타입 시스템 및 상태 관리 설계, 컴포넌트 라이브러리 개발)
- 환경: TS, React, MobX, Emotion, Storybook, Lerna
- 내용:
  - 기존 JavaScript 코드 분석 후 TypeScript 도입 및 점진적 적용
  - Lerna 기반 Monorepo 구조 설계 및 패키지 모듈화
  - Storybook 기반 컴포넌트 라이브러리 개발 및 자동화된 문서화 구축
  - 코드 리뷰 가이드라인을 정의하고 PR 리뷰 프로세스 및 페어 프로그래밍 도입
  - MobX를 기반으로 한 MVC 패턴 적용, 프론트엔드-백엔드 의존성 분리 및 테스트 용이성 확보
  - 타입 안전성을 보장하는 Icon 컴포넌트 라이브러리 개발 (SVG → WebFont → 타입 지원 컴포넌트)
- 주요 성과:
  - TypeScript 도입 및 PR 리뷰 프로세스 개선을 통해 코드 품질 향상 및 코드 리팩토링 비용 감소
  - 디자인 시스템 구축으로 UI 컴포넌트 재사용성을 높이고 개발 속도 30% 향상

### React 기반 Teams Addon 성능 개선

- 목적: 외주 클라이언트의 Teams Addon 성능 최적화 및 로딩 속도 개선
- 기간: 1주일
- 인원: 1명
- 역할 및 기여: 개발 100%
- 환경: JS, React
- 내용:
  - React.lazy 및 Suspense를 활용한 컴포넌트 모듈화 및 코드 스플리팅
  - Intersection Observer를 활용하여 이미지 로딩을 지연 로딩(Lazy Loading) 방식으로 최적화
- 주요 성과:
  - React.lazy 및 이미지 로딩 최적화를 통해 LCP(Largest Contentful Paint) 시간을 5초 이상에서 200ms 이하로 단축
  - 코드 스플리팅 및 지연 로딩을 적용하여 초기 렌더링 속도 및 사용자 체감 성능 개선

