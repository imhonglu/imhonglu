# 브레인크루

- 2018-12-10 ~ 2020-07-01 (1년 6개월)
- 초기 개발자로 합류해 두 개의 서비스를 출시하고 인프라를 관리했습니다.

## 사용 기술
- React, MobX, Styled-Components, react-beautiful-dnd, React-Helmet, Webpack, AWS S3, AWS Cloudfront, JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk, AWS SES, AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit

## 주요 프로젝트

### [런어데이](https://learnaday.kr/) 출시 및 운영(운영 중단)
- 목적: 온/오프라인 교육 플랫폼 출시 및 운영
- 기간: 10개월
- 인원: 2명
- 역할 및 기여: 개발 80%
- 환경:
  - React, MobX, Styled-Components, React-Helmet, Webpack, AWS S3, AWS Cloudfront
  - JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk
  - AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit
- 내용:
  - ERD 설계
  - JWT 기반 RESTful API 설계 및 구현
    - 디렉토리 기반 동적 라우팅 구현
  - AWS 기반 CI/CD 파이프라인 구축
  - Google, Naver OAuth2.0 기반 소셜 로그인 구현
  - MobX를 활용한 상태 관리
    - 서버 데이터 정규화 및 캐시 로직 구현
    - 컴포넌트 리렌더링 최적화
  - 강사 대시보드 구현
    - 커리큘럼 구성 및 피드백 시스템 개발
  - 학습자 대시보드 구현
    - PG사 결제 시스템 연동 및 구현
    - 실시간 학습 진도 관리 시스템 개발
    - 과제 제출/피드백 워크플로우 구현
  - Quilljs 기반 커스텀 에디터 개발
    - 보안을 고려한 클립보드 제어 및 마크업 필터링 구현
    - 이미지 업로드 최적화 (base64 임시 저장 → S3 업로드 → URL 변환)
  - 사용자 이니셜 기반 동적 아바타 생성 시스템 구현
  - React-Helmet를 활용한 SEO 최적화
- 주요 성과:
  - 온/오프라인 교육 플랫폼 출시 및 운영

## [레터플러스](https://letter.plus) 출시 및 운영(운영 중단)
- 목적: 학원교육소식 큐레이팅 및 모바일 뉴스레터 제작 플랫폼 출시 및 운영
- 기간: 6개월
- 인원: 2명
- 역할 및 기여: 개발 80%
- 환경:
  - React, MobX, Styled-Components, react-beautiful-dnd, Webpack, AWS S3, AWS Cloudfront
  - JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk, AWS SES
  - AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit
- 내용:
  - ERD 설계
  - JWT 기반 RESTful API 설계 및 구현
    - 디렉토리 기반 동적 라우팅 구현
  - AWS 기반 CI/CD 파이프라인 구축
  - 뉴스레터 발송 워크플로우 구현
    - react-beautiful-dnd 기반 D&D 방식의 템플릿 편집 인터페이스 구현
    - 외부 서비스 기반 SMS / 이메일 발송 기능 구현
  - 수신자 관리 기능 구현
    - 엑셀 / CSV 기반 import/export 기능 구현
  - 이메일 클라이언트 호환성 확보를 위한 HTML/CSS 최적화 작업 수행
- 주요 성과:
  - 레터플러스 출시 및 운영