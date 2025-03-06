[이력서](../README_KR.md) &gt; [브레인크루](./3_braincrew_kr.md)

# 브레인크루

- 2018-12-10 ~ 2020-07-01 (1년 6개월)
- 초기 개발자로 합류해 2개의 서비스를 성공적으로 출시하고, 인프라 설계와 관리 전반을 맡았습니다.

## 주요 기술 스택

- React, MobX, Styled-Components, react-beautiful-dnd, React-Helmet, Webpack, AWS S3, AWS Cloudfront, JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk, AWS SES, AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit

## 주요 프로젝트

### [런어데이](https://learnaday.kr/) 출시 및 운영 (서비스 종료)

- 목적: 온/오프라인 강의 제공, 학습 진도 관리, 강사-학습자 간 실시간 피드백을 지원하는 교육 플랫폼 개발 및 운영
- 기간: 10개월
- 인원: 2명
- 역할 및 기여: FE 개발(≥80%, 상태 관리·렌더링 최적화), API 개발(100%), CI/CD 구축 및 운영 자동화 (100%)
- 환경: React, MobX, Styled-Components, React-Helmet, Webpack, AWS S3, AWS Cloudfront, JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk, AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit
- 내용:
  - ERD 설계 및 데이터 모델링
  - JWT 기반 RESTful API 설계 및 구현 (디렉토리 기반 동적 라우팅, 미들웨어 기반 인증 및 권한 관리)
  - AWS 기반 CI/CD 파이프라인 구축 및 운영 (CodePipeline, CodeDeploy, CodeBuild 활용)
  - Google, Naver OAuth2.0 소셜 로그인 연동 및 JWT 기반 사용자 인증 구현
  - MobX 기반 상태 관리 및 렌더링 최적화
    - Nested Store 구조를 적용하여 데이터 간 종속성을 최소화하고 캐싱
  - 강사 대시보드 및 학습자 대시보드 구현
    - PG사 결제 시스템 연동 및 결제 상태 관리 기능 개발
    - 사용자별 학습 진도 관리 기능 개발 및 이벤트 기반 알림 기능 구현
  - Quill.js 기반 커스텀 에디터 개발
    - Markup 및 Attribute Sanitize 적용
    - 이미지 붙여넣기 시 base64 변환 후 임시 저장하고, 서버 저장 시 동적 업로드 처리
- 주요 성과:
  - 온/오프라인 교육 플랫폼 출시 및 운영
  - 결제 시스템 및 학습 진도 관리 기능을 포함한 강사·학습자 대시보드 운영
  - 사업적 결정으로 인해 서비스 종료

### [레터플러스](https://letter.plus/) 출시 및 운영 (서비스 종료)

- 목적: 학원 교육 소식 큐레이팅 및 모바일 뉴스레터 제작 플랫폼 출시 및 운영
- 기간: 6개월
- 인원: 2명
- 역할 및 기여: FE 개발(≥80%), API 개발(100%), CI/CD 구축 및 운영 자동화 (100%)
- 환경: React, MobX, Styled-Components, react-beautiful-dnd, Webpack, AWS S3, AWS Cloudfront, JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk, AWS SES, AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit
- 내용:
  - ERD 설계 및 데이터 모델링
  - JWT 기반 RESTful API 설계 및 구현 (디렉토리 기반 동적 라우팅, 미들웨어 기반 인증 및 권한 관리)
  - AWS 기반 CI/CD 파이프라인 구축 및 운영 (CodePipeline, CodeDeploy, CodeBuild 활용)
  - 뉴스레터 발송 시스템 구축
    - 드래그 앤 드롭 기반 뉴스레터 템플릿 편집 기능 개발 (react-beautiful-dnd 활용)
    - AWS SES 및 외부 API를 활용한 SMS 및 이메일 발송 기능 구현
  - 수신자 관리 및 엑셀/CSV 기반 import/export 기능 구현
  - 이메일 클라이언트별 레이아웃 및 스타일 호환성 최적화
- 주요 성과:
  - 뉴스레터 플랫폼 출시 및 안정적인 운영
