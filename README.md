## 🧑 About Me

**"어렵고 힘든 도전 속에서 성장을 즐기는 개발자"**

안녕하세요! **준소프트웨어**에서 백엔드 개발자로 일하고 있는 **이영석(BlueHarmel)** 입니다.

🔭 **Java/Spring 기반 레거시 시스템 운영·현대화**가 주 업무입니다<br>
🤖 **AI 에이전트 오케스트레이션**으로 실무를 운영합니다 — 기획·검수하는 에이전트와 구현하는 에이전트를 분리해, 대규모 레거시 마이그레이션을 검증된 슬라이스 단위로 밀어냅니다<br>
🌱 **Kubernetes**, **Cloud Native** 기술을 학습 중입니다<br>
🎮 **Game Development**도 AI와 협업하며 탐구하고 있습니다

🎯 **Goal**: AI를 가장 잘 부리는 개발자 되기 — 대체되지 않는 법은 지휘하는 것

---

## 💼 Experience

| 기간 | 소속 | 내용 |
|------|------|------|
| 2025.10.27 ~ 현재 | 준소프트웨어 | Backend Developer — 공공 분야 Java/Spring 웹 시스템 3종 운영·기능 개선, Struts 2 → Spring Boot 점진 마이그레이션(스트랭글러 패턴) 주도, Jenkins 기반 배포 파이프라인 구축, 레거시에 Playwright E2E 회귀 검증 문화 도입, AI 멀티 에이전트 개발 워크플로우 설계·운영 |
| 2025 | Kernel360 4기 | 백엔드 개발자 부트캠프 수료 |
| - | 한국외국어대학교 | 글로벌비즈니스테크놀로지학부 |

---

## 🛠 Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Frameworks & Libraries
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)

### Infrastructure & DevOps
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

### AI Tooling
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![OpenAI](https://img.shields.io/badge/Codex_CLI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_CLI-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)

### Tools & IDE
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🤖 AI-Driven Development

실무에서 검증한 멀티 에이전트 개발 워크플로우를 운영합니다:

- **역할 분리 오케스트레이션**: Planner(슬라이스 명세·산출물 검수·검증·커밋) ↔ Executor(구현) — 서로 다른 모델로 교차 검증. 1,400+ 액션 규모 레거시 마이그레이션에서 하루 6개 검증 슬라이스 커밋 실측
- **검증 게이트**: 명세 기반 위임 → 라인 단위 원본 대조 → 테스트·빌드·기동·시나리오 검증 후에만 커밋
- **로컬 LLM 인프라**: DGX Spark 위에 SSH 터널 + Anthropic 호환 프록시를 구성해 Claude Code에서 로컬 모델(qwen3-coder, gemma) 세션을 운영, 한국어 셋업 가이드 작성
- **AI 안전 가드레일**: 파괴적 명령 차단·설정 보안 점검·검증 체크리스트를 에이전트 hook으로 강제하는 운영 기준 수립
- **지식 기반 연동**: Obsidian vault를 에이전트 영구 메모리로 연결한 세션-지식 파이프라인 운영

📘 [**agent-orchestration-playbook**](https://github.com/BlueHarmel/agent-orchestration-playbook) — 위 워크플로우를 누구나 가져다 쓸 수 있게 일반화한 플레이북<br>
📚 [**ai-encyclopedia**](https://github.com/BlueHarmel/ai-encyclopedia) — 백엔드 개발자를 위한 AI 개념·서비스·레시피 정리

---

## 📁 Key Projects

⚔️ **Arena Survivor** - AI와 협업해 개발 중인 모바일 서바이버 게임 (Unity, Android 빌드·터치 컨트롤·성능 검증까지 완료)<br>
🏠 **HouseHub** - 부동산 매물 관리 플랫폼<br>
🎨 **ArtCon** - 캡스톤 프로젝트<br>
💬 **TechTalk** - 기술 토론 플랫폼

---

## ⏱️ Weekly Development Breakdown

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C770%20hrs%2032%20mins-blue?style=flat)

![Lines of code](https://img.shields.io/badge/%EC%A0%80%EB%8A%94%20%EC%97%AC%ED%83%9C%EA%B9%8C%EC%A7%80%20-51.68%20million%20%EC%A4%84%EC%9D%98%20%EC%BD%94%EB%93%9C%EB%A5%BC%20%EC%9E%91%EC%84%B1%ED%96%88%EC%96%B4%EC%9A%94.-blue?style=flat)

**저는 아침형 인간이에요. 🐤** 

```text
🌞 아침                     3375 commits        ████░░░░░░░░░░░░░░░░░░░░░   17.61 % 
🌆 낮　                     10434 commits       ██████████████░░░░░░░░░░░   54.44 % 
🌃 저녁                     4259 commits        ██████░░░░░░░░░░░░░░░░░░░   22.22 % 
🌙 밤　                     1097 commits        █░░░░░░░░░░░░░░░░░░░░░░░░   05.72 % 
```


📊 **저는 이번주를 이렇게 시간을 보냈어요.** 

```text
🕑︎ Timezone: Asia/Seoul

💬 프로그래밍 언어들: 
Other                    2 hrs 23 mins       ██████░░░░░░░░░░░░░░░░░░░   26.00 % 
Java                     2 hrs 20 mins       ██████░░░░░░░░░░░░░░░░░░░   25.44 % 
Markdown                 2 hrs 12 mins       ██████░░░░░░░░░░░░░░░░░░░   24.09 % 
TOML                     26 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   04.75 % 
XML                      25 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   04.67 % 

🔥 에디터들: 
Claude Code              5 hrs 18 mins       ██████████████░░░░░░░░░░░   57.78 % 
Unknown Editor           1 hr 33 mins        ████░░░░░░░░░░░░░░░░░░░░░   16.87 % 
Notion                   1 hr 24 mins        ████░░░░░░░░░░░░░░░░░░░░░   15.39 % 
JetBrainsGateway         45 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   08.22 % 
IntelliJ IDEA            9 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   01.73 % 

💻 운영 체제들: 
Windows                  9 hrs 11 mins       █████████████████████████   100.00 % 
```


 Last Updated on 25/06/2026 19:20:05 UTC
<!--END_SECTION:waka-->

 ---

 ## 🏅 Algorithm Practice

 [![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=dldjdtjr)](https://solved.ac/dldjdtjr/)

 ---

 ## 🔗 Connect with Me

 [![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dldjdtjr12@gmail.com)
 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BlueHarmel)
 [![Solved.ac](https://img.shields.io/badge/Solved.ac-17CE3A?style=for-the-badge&logo=solved.ac&logoColor=white)](https://solved.ac/dldjdtjr)
