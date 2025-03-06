[Resume](../README.md) &gt; [Aha&Company](./6_ahancompany.md)

# Aha&Company

- 2021-11-15 ~ 2024-08-20 (2 years 7 months)
- Designed backend systems and developed API services and core common features.

## Main Tech Stack

- TS, NestJS, TypeORM, BullJS, PgSQL, Nx, OpenAPI, AWS ECS, AWS RDS, AWS ElastiCache

## Key Projects

### Nx-based Monorepo Implementation and Codebase Enhancement

- Purpose: Introduction of monorepo for codebase unification and service modularization
- Duration: 10 months
- Team Size: 4 members
- Role & Contribution: Monorepo architecture design, common module development, API development (≥70%)
- Environment: TS, NestJS, TypeORM, BullJS, PgSQL, Nx, OpenAPI, AWS ECS, AWS RDS, AWS ElastiCache
- Details:
  - Designed and implemented Nx-based monorepo architecture
  - Implemented common features and designed ERD
  - Enhanced caching strategy with `xFetch` and implemented cache-DBMS mapping layer
  - Developed API SDK auto-generation transpiler based on OpenAPI specs
  - Introduced E2E testing with third-party service mocking
  - Enhanced type system for core business logic
- Key Achievements:
  - Achieved over 95% coverage through E2E test implementation, minimizing runtime errors
  - Improved API response time and data processing efficiency through cache strategy optimization
  - Enhanced backend-frontend collaboration through API SDK automation
  - Increased code safety and development productivity through type system enhancement

### Offerwall Advertising Project

- Purpose: Backend design and implementation for offerwall advertising system
- Duration: 2 months
- Team Size: 1 member
- Role & Contribution: Ad data processing design, API and reward system development (100%)
- Environment: TS, NestJS, TypeORM, BullJS, PgSQL, AWS ECS, AWS RDS, AWS ElastiCache
- Details:
  - Designed ERD and developed RESTful APIs for ad transactions and reward data
  - Built Redis-based buffer layer and implemented ad event synchronization
  - Applied composite indexes and implemented transaction data validation
  - Implemented token price integration and ad reward confirmation logic
- Key Achievements:
  - Reduced API response time through Redis-based buffer layer for ad transaction data sync
  - Increased concurrent request handling capacity and reduced system load
  - Improved reward accuracy through token price-based reward confirmation logic

### Expert Homepage / Consultation Project

- Purpose: System development for expert online profiles and consultation services
- Duration: 6 months
- Team Size: 2 members
- Role & Contribution: ERD design, API development (≥90%), OpenAPI-based third-party API SDK development (100%)
- Environment: TS, NestJS, TypeORM, BullJS, PgSQL, AWS ECS, AWS RDS, AWS ElastiCache
- Details:
  - Participated in ERD design for expert profiles and consultation data
  - Designed and implemented RESTful APIs for expert homepage and consultation management
  - Developed internal SDK for third-party consultation API integration based on OpenAPI specs
  - Implemented type-safe wrapper modules for API request/response models
- Key Achievements:
  - Standardized third-party API integration through OpenAPI-based internal SDK
  - Built expert homepage and consultation management system with data storage/retrieval APIs

### Membership Project

- Purpose: Subscription-based membership system implementation and recurring payment feature development
- Duration: 4 months
- Team Size: 3 members
- Role & Contribution: ERD design, recurring payment system development (100%), Redis-based seat allocation and concurrency control logic development (100%)
- Environment: TS, NestJS, TypeORM, BullJS, PgSQL, AWS ECS, AWS RDS, AWS ElastiCache
- Details:
  - Participated in ERD design and implemented RESTful APIs for membership and payment data
  - Implemented card recurring payment registration/cancellation and payment failure handling through PG integration
  - Developed payment cycle, retry logic, and renewal date adjustment features
  - Implemented seat quantity control using Redis INCR/DECR commands to prevent Race Conditions between concurrent payment requests
- Key Achievements:
  - Built recurring payment system with automatic renewal and payment retry mechanism
  - Implemented stable concurrent payment processing with Redis-based seat allocation control

### In-service Advertising Project

- Purpose: In-service ad system implementation and third-party ad platform integration
- Duration: 2 months
- Team Size: 2 members
- Role & Contribution: ERD design, ad API development (≥70%), third-party ad platform integration (100%)
- Environment: TS, NestJS, TypeORM, BullJS, PgSQL, AWS ECS, AWS RDS, AWS ElastiCache
- Details:
  - Participated in ERD design including ad data models
  - Developed APIs for placement ad exposure and operation
  - Developed APIs for expert profile ad execution
  - Integrated third-party ad platforms for ad exposure and click data collection
- Key Achievements:
  - Enabled in-service ad operation through placement and expert profile ad features
  - Enabled ad performance data collection and utilization through third-party platform integration

### TypeScript Introduction and NestJS Migration

- Purpose: Legacy system migration to TS-based NestJS for improved maintainability, scalability, and type safety
- Duration: 6 months
- Team Size: 2 members
- Role & Contribution: ERD design, API development (≥70%), data migration script development (≥50%)
- Environment: TS, NestJS, TypeORM, BullJS, PgSQL, AWS ECS, AWS RDS, AWS ElastiCache
- Details:
  - Analyzed legacy system and improved service module structure with type definitions
  - Developed TypeORM Query Builder Wrapper for strong typing and query optimization
  - Developed data migration scripts
  - Introduced Redis-based cache layer for improved query performance and load balancing
  - Optimized messaging system with async queue-based bulk sending
  - Developed SDK for inter-service messaging with common interfaces
  - Built Private NPM Registry for common module sharing
  - Prototyped admin dashboard for system operation and monitoring
- Key Achievements:
  - Reduced API response time to under 100ms and increased concurrent users by 3x through Redis caching and API structure optimization
  - Reduced runtime errors by 90% through enhanced type system
  - Improved message processing performance through async queue-based bulk sending system
