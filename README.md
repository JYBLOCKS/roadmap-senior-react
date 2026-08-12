# Strict Roadmap: Senior React / Full-Stack Engineer

**Duration:** 52 weeks  
**Suggested start:** August 17, 2026  
**End:** August 15, 2027  
**Minimum workload:** 16–20 hours per week  
**Goal:** become a Senior React Engineer capable of explaining, designing, implementing, measuring, testing, deploying, and technically defending frontend/full-stack systems in production.

> Core rule: **you do not advance because you have “seen” a topic. You advance when you can build it, test it, explain it, and defend your decisions without depending on AI.**

---

## 0. Program Rules

### Rule 1 — AI as a mentor, not autopilot

You may use ChatGPT/Codex/Claude to:

- review your reasoning;
- perform code review after you implement;
- generate interview questions;
- identify edge cases;
- compare architectural alternatives;
- explain a concept after you have first tried to understand it yourself.

You may not use AI to:

- write the entire initial solution;
- solve the weekly challenge before you attempt it;
- generate tests before you have defined the test cases yourself;
- answer the weekly exam for you.

### Rule 2 — TDD + SDD

For every important feature:

1. write a short specification;
2. define acceptance criteria;
3. define APIs/contracts;
4. write tests;
5. implement;
6. measure;
7. document decisions.

### Rule 3 — Weekly Definition of Done

A week is considered passed only if you can:

- [ ] explain the topic without reading notes;
- [ ] implement an example from scratch;
- [ ] write relevant tests;
- [ ] identify at least 3 common mistakes related to the topic;
- [ ] justify trade-offs;
- [ ] solve the weekly challenge;
- [ ] write a `WEEK-XX-RETROSPECTIVE.md` of no more than 500 words.

### Rule 4 — Minimum score

Every Sunday, score yourself:

| Area | Weight |
|---|---:|
| Concepts | 25% |
| Implementation | 25% |
| Testing | 15% |
| Debugging | 15% |
| Architecture / trade-offs | 15% |
| Technical communication | 5% |

**Minimum score to advance: 80/100.**  
If you score below 80, repeat the weak areas before starting the next week.

---

# Mandatory Weekly Schedule

## Monday — Deep Fundamentals — 2.5 h

- 60 min theory/documentation.
- 60 min implementation without copying.
- 30 min notes/Feynman technique.

## Tuesday — Coding — 3 h

- implement the concept of the week;
- zero tutorial copying;
- write small benchmarks when applicable.

## Wednesday — Testing + Debugging — 2.5 h

- unit tests;
- integration tests;
- debug with DevTools;
- reproduce errors deliberately.

## Thursday — Architecture — 2.5 h

- patterns;
- trade-offs;
- write an ADR for one decision;
- refactor.

## Friday — Interview Mode — 2 h

- 30 min JavaScript/TypeScript;
- 30 min React;
- 30 min frontend/system design;
- 30 min explaining code out loud.

## Saturday — Project — 4–6 h

Build the cumulative project.

## Sunday — Exam — 1.5–2 h

- exam without AI;
- retrospective;
- update knowledge gaps.

---

# Core Resources You Will Use Throughout the Year

## React

- React Learn: https://react.dev/learn
- React Reference: https://react.dev/reference/react
- React Compiler: https://react.dev/learn/react-compiler
- React Blog: https://react.dev/blog
- React 19: https://react.dev/blog/2024/12/05/react-19

### Videos

- React Performance Optimization — Full Course: https://www.youtube.com/watch?v=5nSsnXZTdDs
- React Hooks / Async / Performance Masterclass: https://www.youtube.com/watch?v=godEUAAeGTo
- Advanced React Patterns: https://www.youtube.com/watch?v=wwZzADqvt7E
- React architecture/design patterns: https://www.youtube.com/watch?v=oiKO96w59Uc
- Compound Components: https://www.youtube.com/watch?v=N_WgBU3S9W8
- React performance: https://www.youtube.com/watch?v=Qwb-Za6cBws

## JavaScript / Browser

- MDN JavaScript: https://developer.mozilla.org/en-US/docs/Web/JavaScript
- MDN Web APIs: https://developer.mozilla.org/en-US/docs/Web/API

### Videos

- What the heck is the event loop anyway?: https://www.youtube.com/watch?v=8aGhZQkoFbQ
- Jake Archibald — Event Loop: https://www.youtube.com/watch?v=cCOL7MC4Pl0
- Jake Archibald — In The Loop: https://www.youtube.com/watch?v=JjI-3Rxt_5w
- Chrome DevTools Runtime Performance: https://www.youtube.com/watch?v=3_5DKEx72qk
- Web Performance Ultimate Crash Course: https://www.youtube.com/watch?v=qPto6cNPdzU

## TypeScript

- Handbook: https://www.typescriptlang.org/docs/handbook/intro.html

### Videos

- TypeScript Crash Course — Matt Pocock: https://www.youtube.com/watch?v=p6dO9u0M7MQ
- Learn TypeScript Full Course: https://www.youtube.com/watch?v=SpwzRDUQ1GI
- TypeScript + React: https://www.youtube.com/watch?v=TPACABQTHvM

## Testing

- Vitest: https://vitest.dev/
- Testing Library: https://testing-library.com/docs/react-testing-library/intro/
- Playwright: https://playwright.dev/docs/intro

### Videos

- Playwright Crash Course: https://www.youtube.com/watch?v=tNBvlIXlDFI
- Advanced Playwright TypeScript: https://www.youtube.com/watch?v=YfRazDhi9Fw

## Backend

### Express

- Express: https://expressjs.com/
- Express 5 API: https://expressjs.com/en/5x/api/
- Express Security: https://expressjs.com/en/advanced/best-practice-security/

### Videos

- Express.js Full Course: https://www.youtube.com/watch?v=fBzm9zja2Y8
- Node/Express/JWT Backend Course: https://www.youtube.com/watch?v=g09PoiCob4Y

### FastAPI

- FastAPI tutorial: https://fastapi.tiangolo.com/tutorial/
- Async/concurrency: https://fastapi.tiangolo.com/async/
- Security: https://fastapi.tiangolo.com/advanced/security/
- Async tests: https://fastapi.tiangolo.com/advanced/async-tests/

### Videos

- FastAPI Full Course: https://www.youtube.com/watch?v=VirndPTeRaw
- FastAPI Beyond CRUD: https://www.youtube.com/watch?v=TO4aQ3ghFOc
- Event-Driven Architecture React + FastAPI: https://www.youtube.com/watch?v=NVvIpqmf_Xc

## Database / Distributed Systems

### Videos

- Databases In-Depth: https://www.youtube.com/watch?v=pPqazMTzNOM
- PostgreSQL course: https://www.youtube.com/watch?v=6a24yzO1-ZU
- Relational Database Design: https://www.youtube.com/watch?v=26ls5lNiijk
- Redis Deep Dive: https://www.youtube.com/watch?v=fmT5nlEkl3U
- Kafka / System Design: https://www.youtube.com/watch?v=JFPN-GwON9U
- Message Queues/Event Driven Architecture: https://www.youtube.com/watch?v=4090Y2im_bg

## Infrastructure

### Videos

- Docker + Kubernetes Full Course: https://www.youtube.com/watch?v=Wf2eSG3owoA
- Kubernetes 2025: https://www.youtube.com/watch?v=EV47Oxwet6Y
- DevOps Full Course: https://www.youtube.com/watch?v=Tq0vZU7Hp_M

## Security

- OWASP Top 10: https://owasp.org/www-project-top-ten/
- OWASP API Security: https://owasp.org/API-Security/

### Videos

- Authentication & Authorization API Course: https://www.youtube.com/watch?v=3I74AIWthIM
- API Security Fundamentals: https://www.youtube.com/watch?v=Pj3crnYZEKM
- OAuth 2.0 Authorization Code + OIDC: https://www.youtube.com/watch?v=u9dxjB0KgPg

## Frontend System Design

### Videos

- Real Frontend System Design: https://www.youtube.com/watch?v=OWq74_L5vn0
- System Design for Frontend Engineers: https://www.youtube.com/watch?v=zQ_wmJV8l44
- Frontend System Design at Scale: https://www.youtube.com/watch?v=seBhnf9Bpu8
- Frontend System Design Mock Interview: https://www.youtube.com/watch?v=jVMqj8A7Fpk

---

# Mandatory Year-Long Project

You will build an application called **Atlas**.

It will not be a TODO app.

It must end up as a multi-tenant SaaS with:

- React + TypeScript;
- React Router o Next.js;
- design system;
- authentication;
- RBAC;
- complex forms;
- optimistic updates;
- realtime;
- PostgreSQL;
- Express 5 as the primary backend;
- a secondary module implemented with FastAPI to compare ecosystems;
- Redis;
- background jobs;
- WebSockets/SSE;
- observability;
- Docker;
- CI/CD;
- unit/integration/E2E tests;
- rate limiting;
- caching;
- auditing;
- metrics;
- feature flags;
- error handling;
- accessibility;
- performance budgets.

Each phase of the calendar adds capabilities to Atlas.

---

# PHASE 1 — Real JavaScript

## Week 1 — 17–23 Aug 2026

### Topic
Execution model de JavaScript.

### You Must Master

- execution contexts;
- call stack;
- lexical environments;
- scope chain;
- closures;
- hoisting;
- TDZ;
- `this`;
- prototypes;
- property descriptors.

### Required Video
https://www.youtube.com/watch?v=8aGhZQkoFbQ

### Challenge
Implement from scratch:

- `once()`;
- `memoize()`;
- `debounce()`;
- `throttle()`;
- event emitter.

### Exam
Explain why a closure can keep memory alive after the outer function has finished executing.

---

## Week 2 — 24–30 Aug

### Topic
Async JavaScript.

### You Must Master

- event loop;
- macrotasks;
- microtasks;
- Promise jobs;
- async/await;
- timers;
- `queueMicrotask`;
- abort signals;
- race conditions.

### Videos

- https://www.youtube.com/watch?v=cCOL7MC4Pl0
- https://www.youtube.com/watch?v=JjI-3Rxt_5w

### Challenge
Build a task scheduler with:

- at most N concurrent tasks;
- cancellation;
- retry;
- exponential backoff;
- timeout.

---

## Week 3 — 31 Aug–6 Sep

### Topic
Data structures + immutability.

### Master

- Map/Set/WeakMap/WeakSet;
- structural sharing;
- shallow/deep equality;
- reference identity;
- cloning;
- persistent-state mental model;
- complexity Big-O.

### Challenge
Implement a small immutable state store without Zustand/Redux.

---

## Week 4 — 7–13 Sep

### Topic
TypeScript avanzado I.

### Master

- generics;
- constraints;
- conditional types;
- mapped types;
- indexed access;
- discriminated unions;
- `never`;
- `unknown`;
- utility types;
- inference.

### Video
https://www.youtube.com/watch?v=p6dO9u0M7MQ

### Challenge
Design a fully type-safe API client without `any`.

### Gate 1
Create a TypeScript library with tests and a documented public API.

---

# PHASE 2 — Browser Engineering

## Week 5 — 14–20 Sep

### Topic
Rendering pipeline.

### Master

- DOM;
- CSSOM;
- render tree;
- style calculation;
- layout;
- paint;
- composite;
- layout thrashing;
- forced synchronous layouts.

### Video
https://www.youtube.com/watch?v=3_5DKEx72qk

### Challenge
Create a deliberately slow page, profile it, and fix it.

---

## Week 6 — 21–27 Sep

### Topic
Networking for frontend engineers.

### Master

- DNS;
- TCP;
- TLS;
- HTTP/1.1;
- HTTP/2;
- HTTP/3 conceptually;
- caching headers;
- ETag;
- cookies;
- CORS;
- preflight;
- CDN.

### Challenge
Explain everything that happens from typing a URL until React paints the first screen.

---

## Week 7 — 28 Sep–4 Oct

### Topic
Web performance.

### Master

- LCP;
- CLS;
- INP;
- TTFB;
- bundle analysis;
- code splitting;
- lazy loading;
- prefetch/preload;
- image optimization;
- caching.

### Video
https://www.youtube.com/watch?v=qPto6cNPdzU

### Challenge
Achieve Lighthouse >= 95 for performance and accessibility on the Atlas landing page.

---

## Week 8 — 5–11 Oct

### Topic
Accessibility.

### Master

- semantic HTML;
- keyboard navigation;
- focus management;
- ARIA;
- accessible forms;
- screen-reader mental model;
- WCAG basics.

### Challenge
Navigate Atlas completely without a mouse.

### Gate 2
Written performance + accessibility audit.

---

# PHASE 3 — React Internals

## Week 9 — 12–18 Oct

### Topic
React mental model.

### Master

- render vs commit;
- reconciliation;
- identity;
- state preservation;
- keys;
- purity;
- snapshots.

### Resource
https://react.dev/learn

### Challenge
Explain 10 bugs related to keys/state preservation.

---

## Week 10 — 19–25 Oct

### Topic
Hooks internals.

### Master

- hook ordering;
- closures;
- stale closures;
- dependency arrays;
- effect lifecycle;
- cleanup;
- refs;
- reducers.

### Video
https://www.youtube.com/watch?v=godEUAAeGTo

### Challenge
Implement:

- `usePrevious`;
- `useDebounce`;
- `useEventListener`;
- `useAsync`;
- `useLocalStorage`;
- `useIntersectionObserver`.

---

## Week 11 — 26 Oct–1 Nov

### Topic
`useEffect` without superstition.

### Master

- when NOT to use effects;
- synchronization;
- derived state;
- external systems;
- race conditions;
- cancellation.

### Challenge
Take 5 real effects and eliminate at least 2 through better modeling.

---

## Week 12 — 2–8 Nov

### Topic
React Fiber / scheduling conceptual.

### Master

- Fiber mental model;
- cooperative scheduling;
- priority;
- interruption;
- concurrent rendering;
- transitions.

### Challenge
Explain why concurrent rendering does not mean multithreading.

---

## Week 13 — 9–15 Nov

### Topic
React 19 Actions.

### Master

- Actions;
- `useTransition`;
- `useOptimistic`;
- `useActionState`;
- pending/error flows;
- optimistic UI.

### Resource
https://react.dev/blog/2024/12/05/react-19

### Challenge
Build a complete form with optimistic updates and rollback.

---

## Week 14 — 16–22 Nov

### Topic
React Compiler y memoization.

### Master

- React Compiler;
- referential equality;
- memoization costs;
- `memo`;
- `useMemo`;
- `useCallback`;
- when to remove them.

### Resources

- https://react.dev/learn/react-compiler
- https://www.youtube.com/watch?v=Qwb-Za6cBws

### Gate 3
You must profile a complex screen before and after, and justify every optimization.

---

# PHASE 4 — React Architecture

## Week 15 — 23–29 Nov

### Topic
Component API design.

### Master

- composition;
- inversion of control;
- compound components;
- controlled/uncontrolled;
- render props;
- headless components.

### Video
https://www.youtube.com/watch?v=N_WgBU3S9W8

---

## Week 16 — 30 Nov–6 Dec

### Topic
Feature architecture.

### Master

- feature-first;
- boundaries;
- public APIs;
- dependency direction;
- adapters;
- domain vs UI;
- coupling/cohesion.

### Challenge
Refactor Atlas so that no feature imports another feature’s internals.

---

## Week 17 — 7–13 Dec

### Topic
State management.

### Compare

- local state;
- Context;
- reducer;
- Zustand;
- Redux Toolkit;
- server state.

### Challenge
Write an ADR justifying why each type of state lives where it does.

---

## Week 18 — 14–20 Dec

### Topic
TanStack Query / server state.

### Master

- query keys;
- caching;
- invalidation;
- stale time;
- optimistic mutations;
- retries;
- deduplication.

### Video
https://www.youtube.com/watch?v=9Vuz4BbPkXc

---

## Week 19 — 21–27 Dec

### Topic
Forms.

### Master

- React Hook Form;
- schema validation;
- Zod;
- async validation;
- field arrays;
- multi-step forms;
- accessibility;
- server errors.

### Challenge
Create a complex multi-step onboarding flow with rollback and draft persistence.

---

## Week 20 — 28 Dec–3 Jan 2027

### Topic
Design systems.

### Master

- tokens;
- primitives;
- component contracts;
- variants;
- accessibility;
- Storybook mental model;
- visual regression.

### Gate 4
Publish a small design system used by Atlas.

---

# PHASE 5 — Testing Like a Senior

## Week 21 — 4–10 Jan

### Topic
Testing philosophy.

### Master

- test pyramid;
- testing trophy;
- behavior vs implementation;
- deterministic tests;
- mocks/stubs/fakes.

---

## Week 22 — 11–17 Jan

### Topic
Unit + component testing.

### Master

- Vitest/Jest;
- RTL;
- user-event;
- hooks;
- fake timers;
- MSW.

### Challenge
Achieve 80%+ meaningful coverage in a critical feature without chasing artificial coverage.

---

## Week 23 — 18–24 Jan

### Topic
Integration testing.

### Challenge
Build frontend + realistically mocked HTTP with MSW, including 4xx/5xx errors, latency, and retries.

---

## Week 24 — 25–31 Jan

### Topic
Playwright.

### Video
https://www.youtube.com/watch?v=tNBvlIXlDFI

### Master

- fixtures;
- locators;
- network interception;
- auth state;
- parallelism;
- traces;
- screenshots;
- CI.

---

## Week 25 — 1–7 Feb

### Topic
Flaky test hunting.

### Video
https://www.youtube.com/watch?v=YfRazDhi9Fw

### Challenge
Introduce 5 race conditions in E2E tests and fix them without `waitForTimeout`.

### Gate 5
CI must run lint + typecheck + unit + integration + E2E.

---

# PHASE 6 — Production Performance

## Week 26 — 8–14 Feb

### Topic
Profiling React.

### Video
https://www.youtube.com/watch?v=5nSsnXZTdDs

### Master

- React Profiler;
- flamegraphs;
- commit durations;
- unnecessary renders;
- render waterfalls.

---

## Week 27 — 15–21 Feb

### Topic
Bundle architecture.

### Master

- tree shaking;
- ESM;
- dynamic imports;
- chunking;
- dependencies cost;
- bundle analyzer.

### Challenge
Reduce the initial bundle of one screen by at least 25% compared with the baseline created that week.

---

## Week 28 — 22–28 Feb

### Topic
Network + data performance.

### Master

- waterfalls;
- request dedupe;
- pagination;
- infinite queries;
- virtualization;
- streaming mental model.

---

## Week 29 — 1–7 Mar

### Topic
Memory leaks.

### Master

- detached DOM nodes;
- listeners;
- timers;
- closures;
- subscriptions;
- heap snapshots.

### Gate 6
Create a performance report with before/after metrics.

---

# PHASE 7 — Next.js / React Framework Knowledge

## Week 30 — 8–14 Mar

### Topic
Next.js App Router.

### Docs
https://nextjs.org/docs/app

### Video
https://www.youtube.com/watch?v=I1V9YWqRIeI

### Master

- layouts;
- routing;
- loading/error boundaries;
- server/client components.

---

## Week 31 — 15–21 Mar

### Topic
Rendering strategies.

### Master

- CSR;
- SSR;
- SSG;
- ISR;
- streaming;
- hydration;
- partial rendering mental models.

### Challenge
Explain which rendering strategy you would choose for 6 different types of pages.

---

## Week 32 — 22–28 Mar

### Topic
Server Components.

### Master

- boundaries;
- serialization;
- data fetching;
- server-only code;
- client islands;
- bundle impact.

---

## Week 33 — 29 Mar–4 Apr

### Topic
Production Next.js.

### Master

- caching;
- metadata;
- images;
- errors;
- observability;
- deployment.

### Gate 7
Create a version of one Atlas section using Next.js and compare its architecture with the SPA.

---

# PHASE 8 — Primary Backend: Node.js + Express 5

## Week 34 — 5–11 Apr

### Topic
Node internals.

### Master

- event loop Node;
- libuv conceptual;
- streams;
- buffers;
- worker threads;
- process lifecycle;
- backpressure.

### Challenge
Process a large file with streams without loading the entire file into memory.

---

## Week 35 — 12–18 Apr

### Topic
Express 5 architecture.

### Docs
https://expressjs.com/en/5x/api/

### Video
https://www.youtube.com/watch?v=fBzm9zja2Y8

### Master

- middleware;
- routers;
- error middleware;
- validation;
- DTOs;
- service/repository boundaries.

---

## Week 36 — 19–25 Apr

### Topic
API design.

### Master

- REST semantics;
- idempotency;
- pagination;
- filtering;
- versioning;
- error contracts;
- OpenAPI;
- rate limits.

### Challenge
Design a documented public API for Atlas.

---

## Week 37 — 26 Apr–2 May

### Topic
Authentication / Authorization.

### Video
https://www.youtube.com/watch?v=3I74AIWthIM

### Master

- sessions;
- JWT;
- refresh tokens;
- cookies;
- RBAC;
- ABAC conceptually;
- OAuth2;
- OIDC.

---

## Week 38 — 3–9 May

### Topic
Security backend.

### Docs
https://expressjs.com/en/advanced/best-practice-security/

### Master

- validation;
- sanitization;
- CORS;
- CSRF;
- XSS;
- SQL injection;
- secrets;
- secure cookies;
- headers;
- rate limiting.

---

## Week 39 — 10–16 May

### Topic
Background jobs + realtime.

### Master

- queues;
- retries;
- dead-letter queues;
- WebSockets;
- SSE;
- event-driven patterns.

### Gate 8
The Atlas backend must have authentication, RBAC, realtime capabilities, and background processing.

---

# PHASE 9 — FastAPI as a Secondary Backend

## Week 40 — 17–23 May

### Topic
FastAPI architecture.

### Docs
https://fastapi.tiangolo.com/tutorial/

### Video
https://www.youtube.com/watch?v=VirndPTeRaw

### Challenge
Reimplement one Atlas backend module in FastAPI.

---

## Week 41 — 24–30 May

### Topic
Python async + dependency injection.

### Docs
https://fastapi.tiangolo.com/async/

### Master

- async/await Python;
- event loop mental model;
- dependency injection;
- Pydantic;
- request validation.

---

## Week 42 — 31 May–6 Jun

### Topic
FastAPI production.

### Video
https://www.youtube.com/watch?v=TO4aQ3ghFOc

### Master

- auth;
- async DB;
- Celery/background jobs;
- Redis;
- middleware;
- testing;
- errors.

---

## Week 43 — 7–13 Jun

### Topic
Express vs FastAPI.

### Challenge
Write an ADR of at least 1,500 words:

`Why Atlas backend should use Express / FastAPI`

You must compare:

- ecosystem;
- concurrency;
- typing;
- DX;
- performance;
- deployment;
- hiring;
- testing;
- observability;
- maintainability.

### Gate 9
Defend the decision orally in 15 minutes.

---

# PHASE 10 — Data and Distributed Systems

## Week 44 — 14–20 Jun

### Topic
Deep PostgreSQL.

### Video
https://www.youtube.com/watch?v=pPqazMTzNOM

### Master

- normalization;
- indexes;
- query plans;
- transactions;
- isolation levels;
- locking;
- N+1;
- connection pools.

---

## Week 45 — 21–27 Jun

### Topic
Caching / Redis.

### Video
https://www.youtube.com/watch?v=fmT5nlEkl3U

### Master

- cache-aside;
- TTL;
- invalidation;
- distributed locks conceptually;
- pub/sub;
- rate limiting.

### Challenge
Implement caching with hit/miss metrics.

---

## Week 46 — 28 Jun–4 Jul

### Topic
Queues / event-driven architecture.

### Videos

- https://www.youtube.com/watch?v=4090Y2im_bg
- https://www.youtube.com/watch?v=JFPN-GwON9U

### Master

- at-most-once;
- at-least-once;
- exactly-once semantics conceptually;
- idempotent consumers;
- ordering;
- retries;
- DLQ.

### Gate 10
Design a decoupled notification system.

---

# PHASE 11 — DevOps + Security + Observability

## Week 47 — 5–11 Jul

### Topic
Docker.

### Video
https://www.youtube.com/watch?v=Wf2eSG3owoA

### Master

- images;
- layers;
- multi-stage builds;
- networking;
- volumes;
- Compose;
- healthchecks.

---

## Week 48 — 12–18 Jul

### Topic
Kubernetes.

### Video
https://www.youtube.com/watch?v=EV47Oxwet6Y

### Master

- pods;
- deployments;
- services;
- ingress;
- configmaps;
- secrets;
- probes;
- autoscaling conceptually.

---

## Week 49 — 19–25 Jul

### Topic
CI/CD + observability.

### Master

- GitHub Actions;
- build/test/deploy pipelines;
- rollback;
- structured logging;
- metrics;
- tracing;
- SLI/SLO basics;
- alerting.

### Gate 11
Atlas must be automatically deployed from `main` with a documented rollback strategy.

---

# PHASE 12 — Senior / Staff Mindset

## Week 50 — 26 Jul–1 Aug

### Topic
Frontend System Design.

### Videos

- https://www.youtube.com/watch?v=OWq74_L5vn0
- https://www.youtube.com/watch?v=zQ_wmJV8l44

### Required Designs

Design each of the following in 45 minutes:

1. dashboard analytics;
2. real-time chat;
3. Notion-like editor;
4. e-commerce catalog;
5. large-scale file uploader.

You must cover:

- requirements;
- data model;
- component boundaries;
- state;
- APIs;
- caching;
- performance;
- accessibility;
- observability;
- failure modes.

---

## Week 51 — 2–8 Aug

### Topic
Backend/System Design.

### Video
https://www.youtube.com/watch?v=seBhnf9Bpu8

### Required Designs

- notification service;
- URL shortener;
- appointment booking;
- rate limiter;
- audit log;
- realtime presence.

### Senior Skills

- estimate capacity;
- identify bottlenecks;
- explain consistency trade-offs;
- choose SQL vs NoSQL;
- caching;
- queues;
- failure recovery.

---

## Week 52 — 9–15 Aug 2027

# FINAL BOSS

You will not study new topics.

You must demonstrate everything.

## Day 1 — JavaScript

90 minutes:

- closures;
- event loop;
- promises;
- prototypes;
- memory;
- async.

## Day 2 — TypeScript

Build a small type-safe library without `any`.

## Day 3 — React

Build a complex screen from scratch including:

- forms;
- query caching;
- optimistic UI;
- accessibility;
- error handling.

## Day 4 — Debugging

Fix deliberately introduced bugs:

- stale closure;
- unnecessary render;
- race condition;
- memory leak;
- bad cache invalidation.

## Day 5 — System Design

45 minutes of frontend system design.  
45 minutes of backend system design.

## Day 6 — Code Review

Take a PR of at least 500 lines and review it as a tech lead:

- correctness;
- architecture;
- performance;
- security;
- testing;
- maintainability.

## Day 7 — Senior Defense

Record a 30-minute video explaining:

1. the complete Atlas architecture;
2. why you chose each technology;
3. what mistakes you made;
4. what you would change with 10x traffic;
5. how you would investigate a production incident;
6. how you would guide a mid-level developer to implement a feature.

---

# Mandatory Secondary Projects

In addition to Atlas, you must complete these projects without a step-by-step tutorial.

## Project A — UI Library

Build:

- Button;
- Input;
- Select;
- Modal;
- Tooltip;
- Dropdown;
- Tabs;
- DataTable;
- FormField;
- Toast.

Requirements:

- TypeScript;
- accessible;
- keyboard navigation;
- tests;
- Storybook opcional;
- compound components where they make sense.

## Project B — React Query Dashboard

It must have:

- pagination;
- filters;
- optimistic updates;
- cache invalidation;
- offline/error states;
- virtualization.

## Project C — Real-time Chat

It must include:

- WebSockets;
- reconnect;
- optimistic messages;
- deduplication;
- presence;
- message ordering;
- unread count.

## Project D — File Uploader

It must have:

- drag/drop;
- progress;
- cancel;
- retry;
- parallel uploads;
- conceptual or real chunking;
- server validation.

## Project E — Multi-Tenant SaaS

Atlas will be this final project.

---

# Algorithms a Senior Frontend Engineer Should Be Able to Solve

You do not need to become a competitive LeetCode solver, but you must master:

- arrays;
- hash maps;
- sets;
- stacks;
- queues;
- linked lists conceptually;
- trees;
- basic graphs;
- BFS;
- DFS;
- recursion;
- binary search;
- sorting;
- sliding window;
- two pointers;
- memoization.

## Routine

Every Friday:

- 1 Easy in <= 15 min;
- 1 Medium in <= 35 min.

Annual target:

- 80 Easy;
- 60 Medium.

---

# Questions You Must Be Able to Answer Without Looking Them Up

## JavaScript

- What is the difference between microtasks and tasks?
- How does a closure work internally?
- Why does `Promise.then` run before `setTimeout(..., 0)`?
- What causes a memory leak in JavaScript?
- What does `async/await` actually do?

## Browser

- What happens from URL to pixels?
- What causes layout thrashing?
- What is the difference between paint and composite?
- What is CORS really?
- How does HTTP caching work?

## React

- What triggers a render?
- What is the difference between render and commit?
- Why can an incorrect key destroy state?
- When does `useMemo` make an app worse?
- Why does a stale closure happen?
- What problem does React Compiler solve?
- What is the difference between server state and client state?
- What does concurrent rendering mean?

## Architecture

- When should you use Context, Zustand, or Redux?
- How do you define feature boundaries?
- What code should live outside React?
- How do you avoid coupling between modules?
- How do you design a reusable component API?

## Testing

- What should you not mock?
- When should you use unit, integration, or E2E tests?
- What causes flaky tests?
- Why is testing internal implementation details dangerous?

## Backend

- What makes an endpoint idempotent?
- JWT or session cookie?
- What is the difference between authentication and authorization?
- How do you avoid race conditions?
- How do you design safe retries?
- What is backpressure?

## Database

- What does an index do?
- When can an index make an operation worse?
- What is a transaction?
- What are isolation levels?
- What is N+1?

## Distributed systems

- When should you use Redis?
- When should you use a queue?
- What does at-least-once delivery mean?
- Why must a consumer be idempotent?

## DevOps

- What is the difference between an image and a container?
- What does Kubernetes do that Docker does not?
- What is readiness vs liveness?
- How do you perform a rollback?

---

# Senior Communication Training

Being a Senior Engineer is not only about writing code.

Every week, you must do at least one of these activities:

- write an ADR;
- explain a concept to another person;
- perform a code review;
- write an RFC;
- document a hypothetical incident;
- explain the trade-offs of a decision.

Every month, write:

`ARCHITECTURE_REVIEW_MONTH_XX.md`

with:

1. decisions made;
2. incorrect decisions;
3. technical debt;
4. risks;
5. performance;
6. security;
7. improvement plan.

---

# Senior Code Review Routine

For every PR, review:

## Correctness

- does it actually satisfy the requirement?
- what edge cases are missing?

## Architecture

- is it in the correct layer?
- does it increase coupling?
- does it break boundaries?

## React

- unnecessary state?
- unnecessary effect?
- justified prop drilling?
- unnecessary render?

## TypeScript

- is there any `any`?
- do the types model impossible states?
- can a discriminated union be used?

## Performance

- network waterfall?
- bundle impact?
- render cost?
- N+1 requests?

## Security

- is user input validated?
- real authorization?
- leaked secret?

## Testing

- is behavior being tested?
- are failure cases missing?

---

# Yearly Metrics

By the end, you must accumulate at least:

- 52 retrospectives;
- 12 architecture reviews;
- 20+ ADRs;
- 150+ algorithm problems;
- 1 serious SaaS application;
- 4 secondary projects;
- 100+ tests unit/integration;
- 20+ E2E tests;
- 10 performance investigations;
- 10 system design exercises;
- 10 backend design exercises;
- 5 simulated incident postmortems;
- 5 recorded technical presentations.

---

# Recommended Books

You are not required to read them completely in one sitting.

## JavaScript

- *You Don't Know JS Yet* — Kyle Simpson.
- *JavaScript: The Definitive Guide*.

## Architecture

- *Clean Architecture* — Robert C. Martin.
- *A Philosophy of Software Design* — John Ousterhout.
- *Designing Data-Intensive Applications* — Martin Kleppmann.

## Engineering

- *The Pragmatic Programmer*.
- *Release It!*.
- *Site Reliability Engineering* — Google.

---

# Special Rule: “I Don’t Know”

Whenever you encounter something you cannot explain, add it to:

`KNOWLEDGE_GAPS.md`

Formato:

```md
## Topic

### What I thought
...

### What I learned
...

### Can I explain it now?
YES / NO

### Can I implement it without help?
YES / NO
```

Do not delete the gaps. You must be able to see how you evolve.

---

# Monthly Exam

On the last Sunday of every month:

## Part 1 — 30 min

JavaScript/TypeScript.

## Part 2 — 45 min

React/debugging.

## Part 3 — 45 min

Feature implementation.

## Part 4 — 30 min

Architecture/System Design.

## Part 5 — 30 min

Code Review.

**Minimum score: 80%.**

---

# When You Can Say “I Am a Senior React Developer”

Not when you finish the videos.

You can defend that title when you can consistently:

1. enter an unfamiliar codebase and understand it;
2. find difficult bugs;
3. explain why they happened;
4. design maintainable APIs/components;
5. reduce complexity instead of increasing it;
6. measure performance before optimizing;
7. design a testing strategy;
8. discuss security;
9. understand backend systems and databases;
10. design a complete system;
11. perform strong code reviews;
12. teach others;
13. identify risks before production;
14. say “no” to a bad solution and explain a better one;
15. take end-to-end technical ownership.

---

# Final Rule

When something works, do not only ask:

> “Does it work?”

Also ask:

- why does it work?
- what happens if the network fails?
- what happens with 10x traffic?
- what happens with invalid data?
- what happens if the component renders 1,000 times?
- what happens if the user double-clicks?
- what happens if the request arrives twice?
- what happens if two users update the same data?
- how would I measure it?
- how would I test it?
- how would I observe it in production?
- how would I explain it to a junior engineer?
- what trade-off am I accepting?

That shift in the questions you ask is what turns you into the engineer everyone else consults.
