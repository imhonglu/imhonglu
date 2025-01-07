# 소프트웨어인라이프

- 2021-04-26 ~ 2021-11-12 (6개월)
- FE 개발자 포지션으로 합류하여 3인 팀의 리드를 담당했습니다. Typescript를 도입하고 디자인 시스템을 구축하는 업무를 주도했습니다.

## 사용 기술
- Typescript, React, Storybook, Lerna, Emotion, Mobx

## 주요 프로젝트

### 서울대병원 ERP 프로젝트 참여
- 목적: 서울대병원 차세대 ERP 개발
- 기간: 6개월
- 인원: 3명
- 역할 및 기여: 개발, 60%
- 환경: Typescript, React, Storybook, Lerna, Emotion, Mobx
- 주요 성과:
  - Javascript 레거시 코드베이스를 Typescript로 마이그레이션하여 타입 안정성 확보 및 개발 생산성 향상
  - Storybook을 활용한 컴포넌트 기반 디자인 시스템을 구축하여 UI 개발 주기 단축
  - PR 기반 코드 리뷰 프로세스와 페어 프로그래밍 문화를 정착시켜 코드 품질 개선
  - MVC 아키텍처 패턴을 도입하여 프론트엔드-백엔드 의존성 분리 및 테스트 용이성 확보
  - SVG 에셋을 WebFont로 변환하고 타입이 지원되는 Icon 컴포넌트로 래핑하는 자동화된 빌드 파이프라인 구축

### React 기반 Teams Addon 성능 개선
- 목적: React 기반 Teams Addon 성능 개선
- 기간: 1주일
- 인원: 1명
- 역할 및 기여: 개발, 100%
- 환경: Javascript, React
- 문제 분석:
  - 전체 조직도 구성원을 한 번에 로딩하고, 개별 이미지를 순차적으로 받아오는 방식이 성능 저하의 주요 원인임을 파악
- 해결 방안:
  - React.lazy와 Intersection Observer를 활용한 컴포넌트 모듈화
- 주요 성과:
  - LCP(Largest Contentful Paint) 시간을 5초 이상에서 200ms 이하로 단축