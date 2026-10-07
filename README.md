<h1 align="center">안녕하세요, beomzin입니다 👋</h1>

<p align="center">
  배운 것을 직접 만들어 보며 성장하는 <b>웹 개발자</b>입니다.<br/>
  프론트엔드는 React · Vue, 백엔드는 Java · Python을 주로 다룹니다.
</p>

---

### 🙋 About Me

- 🌱 지금 공부하고 있는 것: **AI 에이전트 · Claude Code 플러그인 · 개발 자동화**
- 🤖 실무에서는 **Claude Code** 기반으로 직접 만든 개발 워크플로(**workflow-kit**)에 따라 설계 → 검토 → 구현 → 검증 → 릴리스를 진행해요
- 📚 공부한 내용은 [voyager](https://github.com/beomzin/voyager) 저장소에 예제 코드로 정리하고 있어요
- 💬 관심 있는 것: **팀 단위 AI 협업 개발** — 여러 사람이 AI와 함께 더 쉽고 빠르게 일하는 방법

### 🛠 Tech Stack

| 분류 | 스택 |
| --- | --- |
| 🧩 **Languages** | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| 🎨 **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxt&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white) |
| ⚙️ **Backend** | ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| 🗄 **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| 📨 **Messaging / Infra** | ![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) |
| 🧰 **IDE & Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=eclipseide&logoColor=white) |
| 🤖 **AI-assisted Development** | ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white) ![Codex](https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white) |

### 🤖 How I Work with AI

실제 업무에서는 AI를 "코드 자동완성"이 아니라 **역할이 나뉜 팀**처럼 운영합니다.
Claude Code 플러그인 **workflow-kit**을 직접 만들어, 한 프로젝트에서 다듬은 일하는 방식을 다른 저장소에서도 같은 절차로 재사용하고 있어요.

**기능 하나가 완성되는 흐름**

```
범위·결정 확인 → 설계 (서버·클라이언트 설계 에이전트 병렬)
→ 위험 검토 (인증·인가·마이그레이션 등 민감 경로)
→ 명세 작성 → 구현 (구현 에이전트가 각자 worktree 브랜치에서)
→ 통합 → 검증 (E2E → 서버 테스트 순서 고정) → 리뷰 → 커밋 정돈 → 병합
```

| 영역 | 하는 일 |
| --- | --- |
| 🧭 **설계 · 리뷰** | 설계 · 위험 검토 · 문서 검토 에이전트는 읽기 전용으로 분리해 "만드는 쪽"과 "보는 쪽"을 나눔 |
| 🛠 **구현** | 명세를 받은 구현 에이전트가 독립 worktree 브랜치에서 작업, 병합은 하지 않음 |
| ✅ **검증** | 테스트 실행 순서와 포트 · DB 충돌을 훅으로 강제, 저장 즉시 린트 |
| 📝 **기록** | 되돌리기 비싼 결정은 같은 커밋에 **ADR**로 남기고, push 전 커밋을 "결정 하나 = 커밋 하나"로 정돈 |
| 🚀 **릴리스** | 릴리스 점검 → 버전 커밋 → 클라우드 루틴이 이력 정돈 · 태그 · push → 납품 패키지 빌드 · 스모크 테스트 |

**원칙**

- **결정은 사람, 실행은 AI.** 범위 · 설계 · 병합 · 버전은 항상 직접 확인하고 정합니다.
- **기록은 git에.** AI 세션 사이의 요청도 git과 문서에 남겨 추적 가능하게 합니다.
- AI가 만든 코드는 직접 읽고 이해한 뒤 반영합니다.

### 📌 Repositories

| 저장소 | 설명 |
| --- | --- |
| [voyager](https://github.com/beomzin/voyager) | Java · JSP/Spring · Node.js · Vue 3 학습 예제 모음 |

### 📊 GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=beomzin&show_icons=true&hide_border=true" alt="GitHub Stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=beomzin&layout=compact&hide_border=true" alt="Top Languages" />
</p>
