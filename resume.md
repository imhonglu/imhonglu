# 정범구

- Github: https://github.com/imhonglu
- E-Mail: anonymouser.unknown@gmail.com

---

## 경력

|회사명|기간|역할|업무|
|---|---|---|---|
|[뉴스젤리](#1.-뉴스젤리)|2016. 09 ~ 2017. 07|FE, BE, 설치 엔지니어|- 데이터 시각화 시스템의 추가 개발 및 설치|
|[세이브택스](#2.-세이브택스)|2017. 08 ~ 2018. 11|FE, BE, Infra|- 세무기장용 앱 개발(중도 중단)|
| | | |- 홈페이지 개발(https://www.save-tax.co.kr/) |
|[브레인크루](#3.-브레인크루)|2018. 11 ~ 2020. 05|FE, BE, Infra|- 학원가용 문자 템플릿 발송 서비스 개발|
| | | |- 1:1 케어를 위한 온라인 교육 서비스 개발(https://learnaday.kr/) |
|[주피타카](#4.-주피타카)|2020. 06 ~ 2021. 04|FE(lead)|- 소상공인을 위한 가계부 차세대 앱 개발(중도 이탈)|
|[소프트웨어인라이프](#5.-소프트웨어인라이프)|2021. 04 ~|FE(lead)|- 그룹웨어 개발중|
| | | |- 조직도에 사용되는 트리구조 출력속도 개선|

### 1. 뉴스젤리

- 개발환경
  - azure
  - angularjs
  - python django
  - shell script(bash)
- 경험
  - on-premise 방식의 솔루션 설치/제거 자동화용 쉘 스크립트 작성
    - 리눅스 배포판, 최소설치 버전, 네트워크가 없을 때에 대응하여 솔루션에서 사용되는 기반 서버를 설치 혹은 제거할 수 있도록 자동화
  - admin 기능 개선
    - on-premise 방식의 솔루션의 커스터마이징 요소를 admin page 에서 처리할 수 있도록 기능 추가
    - 데이터 소스(csv, dbms, api)에 따라 쿼리 혹은 데이터 형태를 명시하여 파싱을 자동화 할 수 있는 기능 추가
  - 크로스 브라우징 이슈 처리, 추가 기능 개발 등 유지보수

### 2. 세이브택스

- 개발환경
  - gcp
  - react / react-native
    - mobx
    - styled-component
  - node express
    - rest api
      - jwt
    - sequelize
    - nodemailer
  - sendbird
  - batch script
- 경험
  - sendbird 기반의 채팅 기능과 파일 업/다운로드를 제공하는 세무기장용 앱 개발 및 스토어 배포(중도 중단)
  - 윈도우 기반 pc에 원격 관리 프로그램의 설치를 자동화하는 배치 스크립트 작성
  - 회사 홈페이지 개발

### 3. 브레인크루

- 개발환경
  - aws 
    - elastic beanstalk
    - s3
    - cloud front
    - code pipeline
    - rds(mysql 5.5)
  - react
    - mobx
    - styled-component
    - quilljs
  - node express
    - rest api
      - jwt
    - sequelize
- 경험
  - aws 기반 인프라 세팅 및 CI/CD 자동화
  - quilljs 기반 커스텀 편집기 개발
  - 학원가용 문자 템플릿 발송 서비스의 프로젝트 구조 설계 및 개발(서비스 종료)
  - 1:1 케어를 위한 온라인 교육 서비스의 프로젝트 구조 설계 및 개발

### 4. 주피타카

- 개발환경
  - monorepo(lerna)
  - typescript
  - react
    - mobx
    - emotion
  - storybook
- 경험
  - typescript 도입
  - monorepo(lerna) 도입
  - FE 개발문화, 환경 개선 
    - git 컨벤션, 코드 컨벤션 도입
    - PR 을 기반으로 코드 리뷰를 도입하여 코드 퀄리티 향상
  - storybook 도입
  - font subset script 작성
    - 필요에 따라 subset 을 자동화하는 script 개발
  - mobx factory pattern + 익명 class 를 적용하여 특정 데이터 타입에 종속되는 store 생성 함수 제공 
  - 차세대 소상공인용 가계부 앱 구조 설계 및 개발(중도 이탈)

### 5. 소프트웨어인라이프

- 개발환경
    - monorepo(lerna)
    - typescript
    - react
        - mobx
        - emotion
    - web-component(hybrids)
      - tailwindcss
    - storybook
- 경험
    - typescript 도입
    - monorepo(lerna) 도입
    - FE 개발문화, 환경 개선
        - git 컨벤션, 코드 컨벤션 도입
        - PR 을 기반으로 코드 리뷰를 도입하여 코드 퀄리티 향상
    - storybook 도입
    - 차세대 병원 그룹웨어 구조 설계 및 개발
      - react 기반 시스템 개발
      - mobx 기반의 데이터 처리 방식을 패턴화 => 함수로 제공하여 생산성 향상
      - 프로젝트 중간 구조 변경으로 web-component 기반 시스템 개발
        - tailwindcss 도입
    - 조직도 서비스의 로딩 성능 향상
      - intersection observer 기반 lazy-load 처리
      - queue process 도입
