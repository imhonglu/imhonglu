[Resume](../README.md) &gt; [BrainCrew](./3_braincrew.md)

# BrainCrew

- 2018-12-10 ~ 2020-07-01 (1 year 6 months)
- Joined as an early developer, successfully launched two services, and managed overall infrastructure design and operations.

## Main Tech Stack

- React, MobX, Styled-Components, react-beautiful-dnd, React-Helmet, Webpack, AWS S3, AWS Cloudfront, JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk, AWS SES, AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit

## Key Projects

### [LearnADay](https://learnaday.kr/) Launch and Operation (Service Discontinued)

- Purpose: Development and operation of an education platform supporting online/offline lectures, learning progress management, and real-time feedback between instructors and learners
- Duration: 10 months
- Team Size: 2 members
- Role & Contribution: FE development (≥80%, state management & rendering optimization), API development (100%), CI/CD implementation and operation automation (100%)
- Environment: React, MobX, Styled-Components, React-Helmet, Webpack, AWS S3, AWS Cloudfront, JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk, AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit
- Details:
  - Designed ERD and defined data models
  - Designed and implemented JWT-based RESTful APIs (directory-based dynamic routing, middleware-based authentication and authorization)
  - Built and operated AWS-based CI/CD pipeline (utilizing CodePipeline, CodeDeploy, CodeBuild)
  - Implemented Google and Naver OAuth2.0 social login integration with JWT-based user authentication
  - Implemented MobX-based state management and rendering optimization
    - Applied nested store structure to minimize data dependencies and optimize caching
  - Developed instructor and learner dashboards
    - Integrated PG payment system and developed payment status management
    - Developed user learning progress tracking and event-based notification system
  - Developed custom editor based on Quill.js and improved clipboard control
    - Applied sanitization for markup and attributes
    - Improved image handling by converting sources to Base64 for preview and triggering uploads during API requests
- Key Achievements:
  - Successfully launched and operated online/offline education platform
  - Operated instructor and learner dashboards with payment system and learning progress management
  - Service discontinued due to business decision

### [LetterPlus](https://letter.plus/) Launch and Operation (Service Discontinued)

- Purpose: Launch and operation of mobile newsletter platform for curating and creating educational institution news
- Duration: 6 months
- Team Size: 2 members
- Role & Contribution: FE development (≥80%), API development (100%), CI/CD implementation and operation automation (100%)
- Environment: React, MobX, Styled-Components, react-beautiful-dnd, Webpack, AWS S3, AWS Cloudfront, JS Express, Sequelize, MariaDB, AWS ElasticBeanstalk, AWS SES, AWS CodePipeline, AWS CodeDeploy, AWS CodeBuild, AWS CodeCommit
- Details:
  - Designed ERD and data modeling
  - Designed and implemented JWT-based RESTful APIs (directory-based dynamic routing, middleware-based authentication and authorization)
  - Built and operated AWS-based CI/CD pipeline (utilizing CodePipeline, CodeDeploy, CodeBuild)
  - Built newsletter delivery system
    - Developed drag-and-drop newsletter template editing feature using react-beautiful-dnd
    - Implemented SMS and email delivery using AWS SES and external APIs
  - Implemented recipient management with Excel/CSV import/export functionality
  - Optimized layout and style compatibility across email clients
- Key Achievements:
  - Successfully launched and operated newsletter platform
  - Service discontinued due to business decision

