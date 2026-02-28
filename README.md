# Software-Engineering-Examinable-Terms-for-the-NSW-HSC
This is an unofficial guidance map showing all examinable terms for the NSW Stage 6 Software Engineering examination.

---

## 1. Outcomes

```mermaid
graph TD
O1[SE11 1 Software Engineering Principles]
O2[SE11 2 Algorithms and Data Structures]
O3[SE11 3 Web and PWA Development]
O4[SE12 1 Project Management and Documentation]
O5[SE12 2 Evaluation Testing and Deployment]
```
---
## 2. Principles
```mermaid
graph TD
A1[Abstraction]
A2[Encapsulation]
A3[Cohesion]
A4[Coupling]
A5[Modularity]
A6[Concurrency]
A7[State Management]
A8[Design Patterns]
A9[Architecture Styles MVC Layered Microservices]
A10[Scalability]
A11[Reliability]
A12[Maintainability]
```

---

## 3. Algorithms & Data Structures

```mermaid
graph TD
B1[Algorithm]
B2[Time Complexity]
B3[Space Complexity]
B4[Big O Notation]
B5[Recursion]
B6[Iteration]
B7[Backtracking]
B8[Sorting Algorithms]
B9[Searching Algorithms]
B10[Graphs]
B11[Trees]
B12[Hash Tables]
B13[Stacks]
B14[Queues]
B15[Linked Lists]
```

---

## 4. Web & PWA Development

```mermaid
graph TD
C1[HTML Semantics]
C2[CSS Layout]
C3[JavaScript]
C4[DOM]
C5[Fetch API]
C6[Async Await]
C7[Event Loop]
C8[Service Worker]
C9[Manifest JSON]
C10[Caching Strategies]
C11[Offline Support]
C12[Responsive Design]
C13[Accessibility]
C14[Routing]
C15[API Endpoints]
C16[JSON]
C17[HTTP Methods]
C18[Status Codes]
C19[Security Headers]
C20[CORS]
```

---

## 5. Data & Storage

```mermaid
graph TD
D1[Relational Databases]
D2[SQL]
D3[NoSQL]
D4[ER Diagrams]
D5[Entities and Attributes]
D6[Relationships]
D7[Normalisation]
D8[LocalStorage]
D9[IndexDB]
D10[Session Storage]
```

---

## 6. Security

```mermaid
graph TD
S1[Authentication]
S2[Authorisation]
S3[Hashing]
S4[Encryption]
S5[Input Validation]
S6[Sanitisation]
S7[OWASP Top 10]
S8[HTTPS]
S9[Tokens and Sessions]
```

---

## 7. Project Management

```mermaid
graph TD
P1[Requirements]
P2[User Stories]
P3[Acceptance Criteria]
P4[Personas]
P5[Use Cases]
P6[Feasibility Study]
P7[Risk Management]
P8[Agile]
P9[Scrum]
P10[Sprints]
P11[Backlog]
P12[Burndown Chart]
P13[Version Control]
P14[Branching Strategies]
P15[Merge Requests]
```

---

## 8. Documentation

```mermaid
graph TD
DOC1[UML Class Diagram]
DOC2[UML Sequence Diagram]
DOC3[UML Activity Diagram]
DOC4[Flowcharts]
DOC5[Wireframes]
DOC6[Prototypes]
DOC7[Technical Documentation]
DOC8[API Documentation]
```

---

## 9. Testing & Deployment

```mermaid
graph TD
T1[Unit Testing]
T2[Integration Testing]
T3[System Testing]
T4[User Acceptance Testing]
T5[Test Cases]
T6[Test Plans]
T7[CI CD]
T8[Build Pipeline]
T9[Deployment]
T10[Monitoring]
T11[Logging]
```

---

## 10. NESA Glossary Verbs

```mermaid
graph TD
V1[Analyse]
V2[Evaluate]
V3[Justify]
V4[Assess]
V5[Explain]
V6[Propose]
V7[Outline]
V8[Describe]
V9[Discuss]
```

---

## 11. Links to Outcomes (broken into readable chunks)

### O1 → Principles
```mermaid
graph TD
O1[SE11 1] --> A1
O1 --> A2
O1 --> A3
O1 --> A4
O1 --> A5
O1 --> A6
O1 --> A7
O1 --> A8
O1 --> A9
O1 --> A10
O1 --> A11
O1 --> A12
```


### O2 → Algorithms

```mermaid
graph TD
O2[SE11 2] --> B1
O2 --> B2
O2 --> B3
O2 --> B4
O2 --> B5
O2 --> B6
O2 --> B7
O2 --> B8
O2 --> B9
O2 --> B10
O2 --> B11
O2 --> B12
O2 --> B13
O2 --> B14
O2 --> B15
```

---

### O3 → Web/PWA + Storage

```mermaid
graph TD
O3[SE11 3] --> C1
O3 --> C2
O3 --> C3
O3 --> C4
O3 --> C5
O3 --> C6
O3 --> C7
O3 --> C8
O3 --> C9
O3 --> C10
O3 --> C11
O3 --> C12
O3 --> C13
O3 --> C14
O3 --> C15
O3 --> C16
O3 --> C17
O3 --> C18
O3 --> C19
O3 --> C20

O3 --> D8
O3 --> D9
O3 --> D10
```

---

### O4 → Project Management + Documentation

```mermaid
graph TD
O4[SE12 1] --> P1
O4 --> P2
O4 --> P3
O4 --> P4
O4 --> P5
O4 --> P6
O4 --> P7
O4 --> P8
O4 --> P9
O4 --> P10
O4 --> P11
O4 --> P12
O4 --> P13
O4 --> P14
O4 --> P15

O4 --> DOC1
O4 --> DOC2
O4 --> DOC3
O4 --> DOC4
O4 --> DOC5
O4 --> DOC6
O4 --> DOC7
O4 --> DOC8
```

### O5 → Testing + Security + Verbs

```mermaid
graph TD
O5[SE12 2] --> T1
O5 --> T2
O5 --> T3
O5 --> T4
O5 --> T5
O5 --> T6
O5 --> T7
O5 --> T8
O5 --> T9
O5 --> T10
O5 --> T11

O5 --> S1
O5 --> S2
O5 --> S3
O5 --> S4
O5 --> S5
O5 --> S6
O5 --> S7
O5 --> S8
O5 --> S9

O5 --> V1
O5 --> V2
O5 --> V3
O5 --> V4
O5 --> V5
O5 --> V6
O5 --> V7
O5 --> V8
O5 --> V9
```

---



