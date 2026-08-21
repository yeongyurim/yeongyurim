## Gyurim Yeon · 연규림

Student developer. Currently studying in Kyonggi university.

I like problems where the hard part is deciding what's true — reconciling two data sources, agreeing on a contract before anyone writes code, making a rule impossible to break rather than asking people to remember it.

---

### 🍜 Building now — BudgEats SG

> A restaurant map that shows what students **actually pay** in Singapore.

A S$7 dish costs S$8.39 once service charge and GST land on the bill. Existing maps rank restaurants by rating; we rank them by what people really spent — collected from the students who paid.

**My part** — frontend, plus the CI/CD and security pipeline:

- **Map & pins** — price tiers rendered from a dual data source: measured student spend when we have enough reviews, Google's price level as fallback, and the client is told which one it got
- **Cost control** — debounced map queries with in-flight cancellation, so one drag bills one Places call instead of dozens
- **Security in the pipeline, not the docs** — secret scanning across the full git history, branch protection with required status checks, and lint rules that fail the build on `localStorage` token storage
- **Contract-first parallel work** — froze the API response shapes so four people could build at once; swapping mocks for the real API touched only the network layer

`React 19` · `TypeScript` · `Google Maps JavaScript API` · `GitHub Actions`
Backend by teammates in `Java 21` + `Spring Boot`

→ **[Ctrl-Alt-Defend-KR/budgeats-sg](https://github.com/Ctrl-Alt-Defend-KR/budgeats-sg)**

---

### Selected work

**[finbert-xgboost-predictor](https://github.com/yeongyurim/finbert-xgboost-predictor)** · `Python`
Stock prediction pipeline pairing Korean financial sentiment analysis (KR-FinBERT) with XGBoost — because price history alone misses what the market just read.

**DrillLog** · `React Native` `Expo`
A workout logger built around one constraint: recording a set has to be fast enough to do *between* sets.

**[Node.js-MySQL-RESTful](https://github.com/yeongyurim/Node.js-MySQL-RESTful)** · `Node.js` `MySQL`
A RESTful service written without a framework, to understand the layers instead of inheriting them.

---

### Tech

![TypeScript](https://img.shields.io/badge/TypeScript-16211C?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-16211C?style=flat-square&logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-16211C?style=flat-square&logo=javascript&logoColor=white)
![Python](https://img.shields.io/badge/Python-16211C?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-16211C?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-16211C?style=flat-square&logo=c&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-3D4A44?style=flat-square&logo=nodedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-3D4A44?style=flat-square&logo=vite&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3D4A44?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-3D4A44?style=flat-square&logo=mysql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-3D4A44?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-3D4A44?style=flat-square&logo=git&logoColor=white)

---

### 걸어온 길

| | |
|---|---|
| 2018.03 | 안산대학교 입학 |
| 2022.02 | 안산대학교 졸업 |
| 2025.03 | 경기대학교 편입 |
| 2025.04 – 06 | KT 인턴십 수료 |
| 2026.08 | 싱가포르 해외 연수 · BudgEats SG 개발 |
| 2027.02 | 경기대학교 졸업 예정 |

---

<sub>📍 Seoul / Singapore · <a href="https://github.com/yeongyurim?tab=repositories">repositories</a></sub>
