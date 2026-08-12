# Roadmap estricto: Senior React / Full-Stack Engineer

**Duración:** 52 semanas  
**Inicio sugerido:** 17 de agosto de 2026  
**Fin:** 15 de agosto de 2027  
**Carga mínima:** 16–20 horas por semana  
**Objetivo:** convertirte en un Senior React Engineer capaz de explicar, diseñar, implementar, medir, probar, desplegar y defender técnicamente sistemas frontend/full-stack en producción.

> Regla principal: **no avanzas por haber “visto” un tema. Avanzas cuando puedes construirlo, probarlo, explicarlo y defender decisiones sin depender de IA.**

---

## 0. Reglas del programa

### Regla 1 — IA en modo mentor, no piloto automático

Puedes usar ChatGPT/Codex/Claude para:

- revisar tu razonamiento;
- hacer code review después de que tú implementes;
- generar preguntas de entrevista;
- detectar edge cases;
- comparar alternativas arquitectónicas;
- explicarte un concepto después de que tú hayas intentado entenderlo.

No puedes usar IA para:

- escribir por completo la solución inicial;
- resolver el challenge semanal antes de que lo intentes;
- generar los tests sin que tú hayas definido primero los casos;
- contestar el examen semanal por ti.

### Regla 2 — TDD + SDD

Para cada feature importante:

1. escribe una especificación corta;
2. define criterios de aceptación;
3. define API/contracts;
4. escribe tests;
5. implementa;
6. mide;
7. documenta decisiones.

### Regla 3 — Definition of Done semanal

Una semana se considera aprobada solamente si puedes:

- [ ] explicar el tema sin leer notas;
- [ ] implementar un ejemplo desde cero;
- [ ] escribir tests relevantes;
- [ ] detectar al menos 3 errores comunes del tema;
- [ ] justificar trade-offs;
- [ ] resolver el challenge de la semana;
- [ ] escribir un `WEEK-XX-RETROSPECTIVE.md` de máximo 500 palabras.

### Regla 4 — Score mínimo

Cada domingo te calificas:

| Área | Peso |
|---|---:|
| Conceptos | 25% |
| Implementación | 25% |
| Testing | 15% |
| Debugging | 15% |
| Arquitectura / trade-offs | 15% |
| Comunicación técnica | 5% |

**Mínimo para avanzar: 80/100.**  
Si obtienes menos de 80, repites los puntos débiles antes de iniciar la siguiente semana.

---

# Horario semanal obligatorio

## Lunes — Fundamentos profundos — 2.5 h

- 60 min teoría/documentación.
- 60 min implementación sin copiar.
- 30 min notas/Feynman.

## Martes — Coding — 3 h

- implementar el concepto de la semana;
- cero tutorial-copying;
- escribir pequeños benchmarks cuando aplique.

## Miércoles — Testing + debugging — 2.5 h

- unit tests;
- integration tests;
- debugging con DevTools;
- reproducir errores deliberadamente.

## Jueves — Arquitectura — 2.5 h

- patterns;
- trade-offs;
- ADR de una decisión;
- refactor.

## Viernes — Interview mode — 2 h

- 30 min JavaScript/TypeScript;
- 30 min React;
- 30 min frontend/system design;
- 30 min explicar código en voz alta.

## Sábado — Proyecto — 4–6 h

Construcción del proyecto acumulativo.

## Domingo — Examen — 1.5–2 h

- examen sin IA;
- retrospective;
- actualizar knowledge gaps.

---

# Recursos base que usarás durante todo el año

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

# Proyecto anual obligatorio

Construirás una aplicación llamada **Atlas**.

No será un TODO app.

Debe terminar siendo un SaaS multi-tenant con:

- React + TypeScript;
- React Router o Next.js;
- design system;
- autenticación;
- RBAC;
- formularios complejos;
- optimistic updates;
- realtime;
- PostgreSQL;
- backend Express 5 como backend principal;
- una parte secundaria implementada con FastAPI para comparar ecosistemas;
- Redis;
- background jobs;
- WebSockets/SSE;
- observabilidad;
- Docker;
- CI/CD;
- tests unitarios/integración/E2E;
- rate limiting;
- caching;
- auditoría;
- métricas;
- feature flags;
- manejo de errores;
- accesibilidad;
- performance budgets.

Cada fase del calendario agrega capacidades a Atlas.

---

# FASE 1 — JavaScript de verdad

## Semana 1 — 17–23 ago 2026

### Tema
Execution model de JavaScript.

### Debes dominar

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

### Video obligatorio
https://www.youtube.com/watch?v=8aGhZQkoFbQ

### Challenge
Implementar desde cero:

- `once()`;
- `memoize()`;
- `debounce()`;
- `throttle()`;
- event emitter.

### Examen
Explica por qué una closure puede mantener memoria viva después de terminar la función exterior.

---

## Semana 2 — 24–30 ago

### Tema
Async JavaScript.

### Debes dominar

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
Construye un task scheduler con:

- máximo N tareas concurrentes;
- cancellation;
- retry;
- exponential backoff;
- timeout.

---

## Semana 3 — 31 ago–6 sep

### Tema
Data structures + immutability.

### Dominar

- Map/Set/WeakMap/WeakSet;
- structural sharing;
- shallow/deep equality;
- reference identity;
- cloning;
- persistent-state mental model;
- complexity Big-O.

### Challenge
Implementar un pequeño immutable state store sin Zustand/Redux.

---

## Semana 4 — 7–13 sep

### Tema
TypeScript avanzado I.

### Dominar

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
Diseñar una API client completamente type-safe sin `any`.

### Gate 1
Crear una librería TS con tests y public API documentada.

---

# FASE 2 — Browser engineer

## Semana 5 — 14–20 sep

### Tema
Rendering pipeline.

### Dominar

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
Crear una página deliberadamente lenta, perfilarla y corregirla.

---

## Semana 6 — 21–27 sep

### Tema
Networking para frontend.

### Dominar

- DNS;
- TCP;
- TLS;
- HTTP/1.1;
- HTTP/2;
- HTTP/3 conceptualmente;
- caching headers;
- ETag;
- cookies;
- CORS;
- preflight;
- CDN.

### Challenge
Explicar desde que escribes una URL hasta que React pinta la primera pantalla.

---

## Semana 7 — 28 sep–4 oct

### Tema
Web performance.

### Dominar

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
Lograr Lighthouse >= 95 en performance y accessibility en Atlas landing.

---

## Semana 8 — 5–11 oct

### Tema
Accessibility.

### Dominar

- semantic HTML;
- keyboard navigation;
- focus management;
- ARIA;
- forms accesibles;
- screen-reader mental model;
- WCAG basics.

### Challenge
Navegar Atlas completamente sin mouse.

### Gate 2
Performance + accessibility audit escrito.

---

# FASE 3 — React internals

## Semana 9 — 12–18 oct

### Tema
React mental model.

### Dominar

- render vs commit;
- reconciliation;
- identity;
- state preservation;
- keys;
- purity;
- snapshots.

### Recurso
https://react.dev/learn

### Challenge
Explicar 10 bugs relacionados con keys/state preservation.

---

## Semana 10 — 19–25 oct

### Tema
Hooks internals.

### Dominar

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
Implementar:

- `usePrevious`;
- `useDebounce`;
- `useEventListener`;
- `useAsync`;
- `useLocalStorage`;
- `useIntersectionObserver`.

---

## Semana 11 — 26 oct–1 nov

### Tema
`useEffect` sin supersticiones.

### Dominar

- cuándo NO usar effects;
- synchronization;
- derived state;
- external systems;
- race conditions;
- cancellation.

### Challenge
Tomar 5 effects reales y eliminar al menos 2 mediante mejor modelado.

---

## Semana 12 — 2–8 nov

### Tema
React Fiber / scheduling conceptual.

### Dominar

- Fiber mental model;
- cooperative scheduling;
- priority;
- interruption;
- concurrent rendering;
- transitions.

### Challenge
Explicar por qué concurrent rendering no significa multithreading.

---

## Semana 13 — 9–15 nov

### Tema
React 19 Actions.

### Dominar

- Actions;
- `useTransition`;
- `useOptimistic`;
- `useActionState`;
- pending/error flows;
- optimistic UI.

### Recurso
https://react.dev/blog/2024/12/05/react-19

### Challenge
Formulario completo con optimistic update y rollback.

---

## Semana 14 — 16–22 nov

### Tema
React Compiler y memoization.

### Dominar

- React Compiler;
- referential equality;
- memoization costs;
- `memo`;
- `useMemo`;
- `useCallback`;
- cuándo eliminarlos.

### Recursos

- https://react.dev/learn/react-compiler
- https://www.youtube.com/watch?v=Qwb-Za6cBws

### Gate 3
Debes perfilar una pantalla compleja antes y después y justificar cada optimización.

---

# FASE 4 — Arquitectura React

## Semana 15 — 23–29 nov

### Tema
Component API design.

### Dominar

- composition;
- inversion of control;
- compound components;
- controlled/uncontrolled;
- render props;
- headless components.

### Video
https://www.youtube.com/watch?v=N_WgBU3S9W8

---

## Semana 16 — 30 nov–6 dic

### Tema
Feature architecture.

### Dominar

- feature-first;
- boundaries;
- public APIs;
- dependency direction;
- adapters;
- domain vs UI;
- coupling/cohesion.

### Challenge
Refactor Atlas para que ningún feature importe internals de otro.

---

## Semana 17 — 7–13 dic

### Tema
State management.

### Comparar

- local state;
- Context;
- reducer;
- Zustand;
- Redux Toolkit;
- server state.

### Challenge
Escribir un ADR justificando por qué cada tipo de estado vive donde vive.

---

## Semana 18 — 14–20 dic

### Tema
TanStack Query / server state.

### Dominar

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

## Semana 19 — 21–27 dic

### Tema
Forms.

### Dominar

- React Hook Form;
- schema validation;
- Zod;
- async validation;
- field arrays;
- multi-step forms;
- accessibility;
- server errors.

### Challenge
Crear onboarding multi-step complejo con rollback y draft persistence.

---

## Semana 20 — 28 dic–3 ene 2027

### Tema
Design systems.

### Dominar

- tokens;
- primitives;
- component contracts;
- variants;
- accessibility;
- Storybook mental model;
- visual regression.

### Gate 4
Publicar un mini design system usado por Atlas.

---

# FASE 5 — Testing como Senior

## Semana 21 — 4–10 ene

### Tema
Testing philosophy.

### Dominar

- test pyramid;
- testing trophy;
- behavior vs implementation;
- deterministic tests;
- mocks/stubs/fakes.

---

## Semana 22 — 11–17 ene

### Tema
Unit + component testing.

### Dominar

- Vitest/Jest;
- RTL;
- user-event;
- hooks;
- fake timers;
- MSW.

### Challenge
80%+ cobertura útil en un feature crítico, sin perseguir cobertura artificial.

---

## Semana 23 — 18–24 ene

### Tema
Integration testing.

### Challenge
Frontend + mocked HTTP realisticamente con MSW, errores 4xx/5xx, latency y retries.

---

## Semana 24 — 25–31 ene

### Tema
Playwright.

### Video
https://www.youtube.com/watch?v=tNBvlIXlDFI

### Dominar

- fixtures;
- locators;
- network interception;
- auth state;
- parallelism;
- traces;
- screenshots;
- CI.

---

## Semana 25 — 1–7 feb

### Tema
Flaky test hunting.

### Video
https://www.youtube.com/watch?v=YfRazDhi9Fw

### Challenge
Introducir 5 condiciones de carrera en E2E y corregirlas sin `waitForTimeout`.

### Gate 5
CI debe ejecutar lint + typecheck + unit + integration + E2E.

---

# FASE 6 — Performance de producción

## Semana 26 — 8–14 feb

### Tema
Profiling React.

### Video
https://www.youtube.com/watch?v=5nSsnXZTdDs

### Dominar

- React Profiler;
- flamegraphs;
- commit durations;
- unnecessary renders;
- render waterfalls.

---

## Semana 27 — 15–21 feb

### Tema
Bundle architecture.

### Dominar

- tree shaking;
- ESM;
- dynamic imports;
- chunking;
- dependencies cost;
- bundle analyzer.

### Challenge
Reducir bundle inicial de una pantalla al menos 25% respecto al baseline creado esa semana.

---

## Semana 28 — 22–28 feb

### Tema
Network + data performance.

### Dominar

- waterfalls;
- request dedupe;
- pagination;
- infinite queries;
- virtualization;
- streaming mental model.

---

## Semana 29 — 1–7 mar

### Tema
Memory leaks.

### Dominar

- detached DOM nodes;
- listeners;
- timers;
- closures;
- subscriptions;
- heap snapshots.

### Gate 6
Crear un performance report con métricas antes/después.

---

# FASE 7 — Next.js / React framework knowledge

## Semana 30 — 8–14 mar

### Tema
Next.js App Router.

### Docs
https://nextjs.org/docs/app

### Video
https://www.youtube.com/watch?v=I1V9YWqRIeI

### Dominar

- layouts;
- routing;
- loading/error boundaries;
- server/client components.

---

## Semana 31 — 15–21 mar

### Tema
Rendering strategies.

### Dominar

- CSR;
- SSR;
- SSG;
- ISR;
- streaming;
- hydration;
- partial rendering mental models.

### Challenge
Explicar cuál estrategia escogerías para 6 tipos distintos de páginas.

---

## Semana 32 — 22–28 mar

### Tema
Server Components.

### Dominar

- boundaries;
- serialization;
- data fetching;
- server-only code;
- client islands;
- bundle impact.

---

## Semana 33 — 29 mar–4 abr

### Tema
Production Next.js.

### Dominar

- caching;
- metadata;
- images;
- errors;
- observability;
- deployment.

### Gate 7
Crear una versión de una sección de Atlas usando Next.js y comparar arquitectura con SPA.

---

# FASE 8 — Backend principal: Node.js + Express 5

## Semana 34 — 5–11 abr

### Tema
Node internals.

### Dominar

- event loop Node;
- libuv conceptual;
- streams;
- buffers;
- worker threads;
- process lifecycle;
- backpressure.

### Challenge
Procesar un archivo grande con streams sin cargarlo completo en memoria.

---

## Semana 35 — 12–18 abr

### Tema
Express 5 architecture.

### Docs
https://expressjs.com/en/5x/api/

### Video
https://www.youtube.com/watch?v=fBzm9zja2Y8

### Dominar

- middleware;
- routers;
- error middleware;
- validation;
- DTOs;
- service/repository boundaries.

---

## Semana 36 — 19–25 abr

### Tema
API design.

### Dominar

- REST semantics;
- idempotency;
- pagination;
- filtering;
- versioning;
- error contracts;
- OpenAPI;
- rate limits.

### Challenge
Diseñar API pública documentada de Atlas.

---

## Semana 37 — 26 abr–2 may

### Tema
Authentication / Authorization.

### Video
https://www.youtube.com/watch?v=3I74AIWthIM

### Dominar

- sessions;
- JWT;
- refresh tokens;
- cookies;
- RBAC;
- ABAC conceptualmente;
- OAuth2;
- OIDC.

---

## Semana 38 — 3–9 may

### Tema
Security backend.

### Docs
https://expressjs.com/en/advanced/best-practice-security/

### Dominar

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

## Semana 39 — 10–16 may

### Tema
Background jobs + realtime.

### Dominar

- queues;
- retries;
- dead-letter queues;
- WebSockets;
- SSE;
- event-driven patterns.

### Gate 8
Atlas backend debe tener auth, RBAC, realtime y background processing.

---

# FASE 9 — FastAPI como segundo backend

## Semana 40 — 17–23 may

### Tema
FastAPI architecture.

### Docs
https://fastapi.tiangolo.com/tutorial/

### Video
https://www.youtube.com/watch?v=VirndPTeRaw

### Challenge
Reimplementar un módulo del backend de Atlas en FastAPI.

---

## Semana 41 — 24–30 may

### Tema
Python async + dependency injection.

### Docs
https://fastapi.tiangolo.com/async/

### Dominar

- async/await Python;
- event loop mental model;
- dependency injection;
- Pydantic;
- request validation.

---

## Semana 42 — 31 may–6 jun

### Tema
FastAPI production.

### Video
https://www.youtube.com/watch?v=TO4aQ3ghFOc

### Dominar

- auth;
- async DB;
- Celery/background jobs;
- Redis;
- middleware;
- testing;
- errors.

---

## Semana 43 — 7–13 jun

### Tema
Express vs FastAPI.

### Challenge
Escribir un ADR de mínimo 1500 palabras:

`Why Atlas backend should use Express / FastAPI`

Debes comparar:

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
Defender la decisión oralmente en 15 minutos.

---

# FASE 10 — Datos y sistemas distribuidos

## Semana 44 — 14–20 jun

### Tema
PostgreSQL profundo.

### Video
https://www.youtube.com/watch?v=pPqazMTzNOM

### Dominar

- normalization;
- indexes;
- query plans;
- transactions;
- isolation levels;
- locking;
- N+1;
- connection pools.

---

## Semana 45 — 21–27 jun

### Tema
Caching / Redis.

### Video
https://www.youtube.com/watch?v=fmT5nlEkl3U

### Dominar

- cache-aside;
- TTL;
- invalidation;
- distributed locks conceptual;
- pub/sub;
- rate limiting.

### Challenge
Implementar caching con métricas hit/miss.

---

## Semana 46 — 28 jun–4 jul

### Tema
Queues / event-driven architecture.

### Videos

- https://www.youtube.com/watch?v=4090Y2im_bg
- https://www.youtube.com/watch?v=JFPN-GwON9U

### Dominar

- at-most-once;
- at-least-once;
- exactly-once semantics conceptually;
- idempotent consumers;
- ordering;
- retries;
- DLQ.

### Gate 10
Diseñar un sistema de notifications desacoplado.

---

# FASE 11 — DevOps + Security + Observability

## Semana 47 — 5–11 jul

### Tema
Docker.

### Video
https://www.youtube.com/watch?v=Wf2eSG3owoA

### Dominar

- images;
- layers;
- multi-stage builds;
- networking;
- volumes;
- Compose;
- healthchecks.

---

## Semana 48 — 12–18 jul

### Tema
Kubernetes.

### Video
https://www.youtube.com/watch?v=EV47Oxwet6Y

### Dominar

- pods;
- deployments;
- services;
- ingress;
- configmaps;
- secrets;
- probes;
- autoscaling conceptual.

---

## Semana 49 — 19–25 jul

### Tema
CI/CD + observability.

### Dominar

- GitHub Actions;
- build/test/deploy pipelines;
- rollback;
- structured logging;
- metrics;
- tracing;
- SLI/SLO basics;
- alerting.

### Gate 11
Atlas desplegado automáticamente desde main con rollback strategy documentada.

---

# FASE 12 — Senior / Staff mindset

## Semana 50 — 26 jul–1 ago

### Tema
Frontend System Design.

### Videos

- https://www.youtube.com/watch?v=OWq74_L5vn0
- https://www.youtube.com/watch?v=zQ_wmJV8l44

### Diseños obligatorios

Diseña en 45 minutos cada uno:

1. dashboard analytics;
2. chat en tiempo real;
3. editor tipo Notion;
4. e-commerce catalog;
5. file uploader masivo.

Debes cubrir:

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

## Semana 51 — 2–8 ago

### Tema
Backend/System Design.

### Video
https://www.youtube.com/watch?v=seBhnf9Bpu8

### Diseños obligatorios

- notification service;
- URL shortener;
- appointment booking;
- rate limiter;
- audit log;
- realtime presence.

### Senior skills

- estimar capacidad;
- detectar bottlenecks;
- explicar consistency trade-offs;
- elegir SQL vs NoSQL;
- caching;
- queues;
- failure recovery.

---

## Semana 52 — 9–15 ago 2027

# FINAL BOSS

No estudiarás temas nuevos.

Debes demostrar todo.

## Día 1 — JavaScript

90 minutos:

- closures;
- event loop;
- promises;
- prototypes;
- memory;
- async.

## Día 2 — TypeScript

Construir una pequeña librería type-safe sin `any`.

## Día 3 — React

Construir una pantalla compleja desde cero incluyendo:

- forms;
- query caching;
- optimistic UI;
- accessibility;
- error handling.

## Día 4 — Debugging

Resolver bugs introducidos deliberadamente:

- stale closure;
- unnecessary render;
- race condition;
- memory leak;
- bad cache invalidation.

## Día 5 — System Design

45 minutos de frontend system design.  
45 minutos de backend system design.

## Día 6 — Code Review

Tomar un PR de mínimo 500 líneas y hacer review como tech lead:

- correctness;
- architecture;
- performance;
- security;
- testing;
- maintainability.

## Día 7 — Senior Defense

Graba un video de 30 minutos explicando:

1. arquitectura completa de Atlas;
2. por qué escogiste cada tecnología;
3. cuáles fueron tus errores;
4. qué cambiarías si tuvieras 10x tráfico;
5. cómo investigarías un incidente de producción;
6. cómo guiarías a un mid developer para implementar un feature.

---

# Proyectos secundarios obligatorios

Además de Atlas debes completar estos proyectos sin tutorial paso a paso.

## Proyecto A — UI Library

Construye:

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

Requisitos:

- TypeScript;
- accessible;
- keyboard navigation;
- tests;
- Storybook opcional;
- compound components donde tenga sentido.

## Proyecto B — React Query Dashboard

Debe tener:

- pagination;
- filters;
- optimistic updates;
- cache invalidation;
- offline/error states;
- virtualization.

## Proyecto C — Real-time Chat

Debe incluir:

- WebSockets;
- reconnect;
- optimistic messages;
- deduplication;
- presence;
- message ordering;
- unread count.

## Proyecto D — File uploader

Debe tener:

- drag/drop;
- progress;
- cancel;
- retry;
- parallel uploads;
- chunking conceptual o real;
- server validation.

## Proyecto E — SaaS multi-tenant

Atlas será este proyecto final.

---

# Algoritmos que un Senior Frontend debería poder resolver

No necesitas convertirte en competitivo de LeetCode, pero sí debes dominar:

- arrays;
- hash maps;
- sets;
- stacks;
- queues;
- linked lists conceptualmente;
- trees;
- graphs básicos;
- BFS;
- DFS;
- recursion;
- binary search;
- sorting;
- sliding window;
- two pointers;
- memoization.

## Rutina

Cada viernes:

- 1 Easy en <= 15 min;
- 1 Medium en <= 35 min.

Objetivo anual:

- 80 Easy;
- 60 Medium.

---

# Preguntas que al terminar debes poder responder sin buscar

## JavaScript

- ¿Qué diferencia hay entre microtasks y tasks?
- ¿Cómo funciona una closure internamente?
- ¿Por qué `Promise.then` corre antes que `setTimeout(..., 0)`?
- ¿Qué causa un memory leak en JS?
- ¿Qué hace realmente `async/await`?

## Browser

- ¿Qué ocurre desde URL hasta pixels?
- ¿Qué provoca layout thrashing?
- ¿Qué diferencia paint de composite?
- ¿Qué es CORS realmente?
- ¿Cómo funciona HTTP caching?

## React

- ¿Qué dispara un render?
- ¿Qué diferencia render de commit?
- ¿Por qué una key incorrecta puede destruir state?
- ¿Cuándo `useMemo` empeora una app?
- ¿Por qué ocurre una stale closure?
- ¿Qué problema resuelve React Compiler?
- ¿Qué diferencia server state de client state?
- ¿Qué significa concurrent rendering?

## Architecture

- ¿Cuándo usar Context, Zustand o Redux?
- ¿Cómo defines boundaries de features?
- ¿Qué código debe vivir fuera de React?
- ¿Cómo evitas acoplamiento entre módulos?
- ¿Cómo diseñas una API reusable de componentes?

## Testing

- ¿Qué no deberías mockear?
- ¿Cuándo usar unit, integration o E2E?
- ¿Qué causa flaky tests?
- ¿Por qué probar implementación interna es peligroso?

## Backend

- ¿Qué hace idempotente un endpoint?
- ¿JWT o session cookie?
- ¿Qué diferencia authentication de authorization?
- ¿Cómo evitas race conditions?
- ¿Cómo diseñas retries seguros?
- ¿Qué es backpressure?

## Database

- ¿Qué hace un índice?
- ¿Cuándo un índice puede empeorar una operación?
- ¿Qué es una transacción?
- ¿Qué son isolation levels?
- ¿Qué es N+1?

## Distributed systems

- ¿Cuándo usar Redis?
- ¿Cuándo usar una queue?
- ¿Qué significa at-least-once delivery?
- ¿Por qué un consumer debe ser idempotente?

## DevOps

- ¿Qué diferencia image de container?
- ¿Qué hace Kubernetes que Docker no hace?
- ¿Qué es readiness vs liveness?
- ¿Cómo haces rollback?

---

# Senior communication training

Ser Senior no significa únicamente escribir código.

Cada semana debes hacer al menos una de estas actividades:

- escribir un ADR;
- explicar un concepto a otra persona;
- hacer code review;
- escribir una RFC;
- documentar un incidente hipotético;
- explicar trade-offs de una decisión.

Cada mes escribe:

`ARCHITECTURE_REVIEW_MONTH_XX.md`

con:

1. decisiones tomadas;
2. decisiones equivocadas;
3. deuda técnica;
4. riesgos;
5. performance;
6. seguridad;
7. plan de mejora.

---

# Rutina de Code Review Senior

En cada PR revisa:

## Correctness

- ¿resuelve realmente el requirement?
- ¿qué edge cases faltan?

## Architecture

- ¿está en la capa correcta?
- ¿aumenta acoplamiento?
- ¿rompe boundaries?

## React

- ¿estado innecesario?
- ¿effect innecesario?
- ¿prop drilling justificable?
- ¿render innecesario?

## TypeScript

- ¿hay `any`?
- ¿tipos modelan estados imposibles?
- ¿puede usarse discriminated union?

## Performance

- ¿network waterfall?
- ¿bundle impact?
- ¿render cost?
- ¿N+1 requests?

## Security

- ¿user input validado?
- ¿authorization real?
- ¿secret filtrado?

## Testing

- ¿se prueba comportamiento?
- ¿faltan failure cases?

---

# Métricas del año

Al finalizar debes acumular al menos:

- 52 retrospectives;
- 12 architecture reviews;
- 20+ ADRs;
- 150+ algorithm problems;
- 1 aplicación SaaS seria;
- 4 proyectos secundarios;
- 100+ tests unit/integration;
- 20+ E2E tests;
- 10 performance investigations;
- 10 system design exercises;
- 10 backend design exercises;
- 5 incident postmortems simulados;
- 5 technical presentations grabadas.

---

# Libros recomendados

No son obligatorios de leer completos de una sola vez.

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

# Regla especial: “No sé”

Cada vez que encuentres algo que no puedas explicar, agrégalo a:

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

No borres los gaps. Debes ver cómo evolucionas.

---

# Examen mensual

El último domingo de cada mes:

## Parte 1 — 30 min

JavaScript/TypeScript.

## Parte 2 — 45 min

React/debugging.

## Parte 3 — 45 min

Construcción de feature.

## Parte 4 — 30 min

Architecture/System Design.

## Parte 5 — 30 min

Code Review.

**Score mínimo: 80%.**

---

# Cuándo podrás decir “soy Senior React Developer”

No cuando termines los videos.

Podrás defenderlo cuando consistentemente puedas:

1. entrar a una codebase desconocida y entenderla;
2. encontrar bugs difíciles;
3. explicar por qué sucedieron;
4. diseñar APIs/componentes mantenibles;
5. reducir complejidad en vez de aumentarla;
6. medir performance antes de optimizar;
7. diseñar testing strategy;
8. discutir seguridad;
9. entender backend y base de datos;
10. diseñar un sistema completo;
11. hacer buenos code reviews;
12. enseñar a otros;
13. detectar riesgos antes de producción;
14. decir “no” a una mala solución y explicar una mejor;
15. tomar responsabilidad técnica end-to-end.

---

# Regla final

Cuando algo funcione, no preguntes solamente:

> “¿Funciona?”

Pregunta también:

- ¿por qué funciona?
- ¿qué pasa si falla la red?
- ¿qué pasa con 10x tráfico?
- ¿qué pasa con datos inválidos?
- ¿qué pasa si el componente renderiza 1,000 veces?
- ¿qué pasa si el usuario hace doble click?
- ¿qué pasa si la petición llega dos veces?
- ¿qué pasa si dos usuarios actualizan el mismo dato?
- ¿cómo lo mediría?
- ¿cómo lo probaría?
- ¿cómo lo observaría en producción?
- ¿cómo se lo explicaría a un junior?
- ¿qué trade-off estoy aceptando?

Ese cambio de preguntas es el que te convierte en el ingeniero al que los demás consultan.
