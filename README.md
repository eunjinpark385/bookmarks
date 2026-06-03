# bookmarks
[English](./README_EN.md) | [한국어](./README.md)

개발 및 연구를 진행하며 개인적으로 흥미롭거나 유용하다고 생각한 레퍼런스들을 카테고리 관계없이 아카이빙

## 📂 Structure
* `README.md` - 유용한 웹 링크 및 유틸리티 모음
* `papers/` - 읽은 논문 분석 및 핵심 매커니즘 구현 노트 [👉 바로가기](papers/)

---

## 📌 Curated Links

### 🌐 System / Infra
* **[Build Your Own Redis](https://build-your-own.org/redis/)** * 외부 라이브러리 없이 C/C++ 또는 Go로 Redis 핵심 기능을 바닥부터 구현하는 가이드. Network Socket, Protocol Parsing, Event Loop 구조 학습용.
  * `Tags` : `Network` `Event Loop` `C/C++` `Go` `Low-Level`
* **[System Design Notes](https://github.com/liquidslr/system-design-notes)** * 대규모 분산 시스템 설계의 주요 아키텍처 패턴(Load Balancing, Caching, DB Sharding 등) 요약본.
  * `Tags` : `Architecture` `Distributed System` `Backend`
* **[Practice C Programming Projects](https://github.com/labex-labs/practice-c-programming-projects)** * Pointer 연산 및 Memory Allocation 등 C 언어 로우레벨 제어 기본기를 다질 수 있는 실습 프로젝트 모음.
  * `Tags` : `C Language` `Memory Allocation` `Pointers`
* **[Computer Networking Fundamentals](https://labs.iximiuz.com/courses/computer-networking-fundamentals)** * 리눅스 가상 환경(Container, Namespace) 기반의 인터랙티브 네트워크 실습 코스. Routing 및 TCP/IP 흐름 검증.
  * `Tags` : `Linux` `Networking` `TCP/IP` `Interactive`

### 🤖 AI / ML & Core Mathematics
* **[Math Behind Cross-Entropy Loss](https://outcomeschool.com/blog/math-behind-cross-entropy-loss)** * 분류(Classification) 및 대조 학습의 기반이 되는 Cross-Entropy Loss를 정보 이론 관점에서 유도하는 과정 기술.
  * `Tags` : `Information Theory` `Loss Function` `Math`
* **[Paper Reading (Mu Li)](https://github.com/mli/paper-reading)** * 전 AWS 수석 과학자 Mu Li 박사의 딥러닝 랜드마크 논문 분석 아카이브.
  * `Tags` : `Deep Learning` `Paper Reading` `Landmark Models`
* **[Transformer Explainer](https://github.com/poloclub/transformer-explainer)** * Transformer(GPT-2 기반) 내부의 텐서 연산 과정을 3D 인터랙티브 화면으로 시각화한 툴.
  * `Tags` : `Transformer` `Visualization` `GPT-2` `Web Tool`
* **[Stanford CS229 Machine Learning Cheatsheets](https://github.com/afshinea/stanford-cs-229-machine-learning)** * 스탠포드 대학교 CS229 강의의 핵심 요약본. 지도/비지도 학습, 딥러닝 수학 공식 및 확률·선형대수 기초 치트시트 모음.
  * `Tags` : `Stanford CS229` `Cheatsheet` `Linear Algebra`
* **[Sophon AI Research Papers](https://sophon.at/papers)** * 실시간 트렌딩 AI 연구 논문, 모델, 벤치마크 데이터를 추적하고 분야별(Language Modeling, Agents 등) 흐름을 파악하기 좋은 플랫폼.
  * `Tags` : `AI Trend` `Research Paper` `LLM` `Benchmark`

### 🛠 Tools & AI Productivity
* **[Understand Anything](https://github.com/Lum1104/Understand-Anything)** * 방대한 코드베이스나 위키 문서를 분석하여 아키텍처 레이어와 함수 종속 관계를 인터랙티브 지식 그래프(Knowledge Graph)로 시각화해주는 오픈소스 툴.
  * `Tags` : `Code Analysis` `Knowledge Graph` `Productivity` `Vibe Coding`
* **[Andrej Karpathy Skills Guidelines](https://github.com/multica-ai/andrej-karpathy-skills/tree/main)** * 안드레아 카파시가 공유한 LLM 코딩 피트폴(Pitfalls)을 방지하기 위한 가이드라인 및 Claude Code, Cursor 전용 규칙 포함.
  * `Tags` : `Karpathy` `LLM Coding` `Cursor` `Claude Code`
* **[Developer Roadmap](https://github.com/nilbuild/developer-roadmap)** * 전 세계 개발자들이 참조하는 roadmap.sh의 직무별/기술 스택별 대화형 커리어 학습 로드맵 가이드라인 저장소.
  * `Tags` : `Career` `Roadmap` `Learning Path`

### 📊 Visualization & Utility
* **[Manim Community](https://github.com/ManimCommunity/manim)** * 수학적 개념이나 알고리즘 매커니즘을 파이썬 코드로 애니메이션화하는 렌더링 엔진.
  * `Tags` : `Python` `Math Animation` `3blue1brown`
* **[VisuAlgo](https://visualgo.net/en)** * 주요 자료구조 및 알고리즘의 동작 과정을 단계별 애니메이션으로 보여주는 플랫폼.
  * `Tags` : `Data Structure` `Algorithm` `Animation`
* **[CSVistool (ArrayList)](https://csvistool.com/ArrayList)** * 동적 배열(ArrayList)의 내부 동작(Resize, 삽입/삭제 시 데이터 시프팅) 메커니즘 시각화 도구.
  * `Tags` : `Array List` `Data Structure` `CS Basics`
* **[cobalt.tools](https://cobalt.tools)** * 광고나 트래커 없이 깔끔하게 미디어 파일만 추출해 주는 웹 유틸리티.
  * `Tags` : `Media Downloader` `Privacy` `Web Utility`

### ✍ Writing / Review
* **[Google Engineering Practices](https://github.com/google/eng-practices/blob/master/review/reviewer/comments.md)** * 구글의 코드 리뷰 커뮤니케이션 가이드라인 및 전문적인 리뷰 댓글 작성 템플릿 문서.
  * `Tags` : `Code Review` `Google` `Engineering Culture`
* **[Academic Phrasebank](https://www.phrasebank.manchester.ac.uk/)** * 맨체스터 대학 제공 학술 영어 작문 템플릿. 논문 섹션별(Intro, Methodology 등) 문장 구조 정리.
  * `Tags` : `Academic Writing` `English` `Research Template`
* **[Write & Improve](https://writeandimprove.com/)** * 캠브리지 대학 개발 AI 기반 실시간 영작 교정 서비스. 문법 오류 검출 및 자가 피드백용.
  * `Tags` : `AI Proofreading` `Cambridge` `Grammar Check`

---

## 📚 Books & Lecture Notes (Official Source Links)

### 💻 Operating Systems & Low-Level
* **[MIT xv6 RISC-V Source & Commentary Book](https://pdos.csail.mit.edu/6.1810/2025/xv6/)**
  * `Source Files` : `book-riscv-rev5.pdf` / `xv6-src-booklet-rev5.pdf` 대체
  * MIT의 OS 강의에서 사용되는 유닉스 기반 커널 xv6의 전체 소스코드 책자 및 아키텍처 환경 구동 이론서 공식 배포처.
  * `Type` : `University Textbook` `Operating System` `RISC-V`

### 🤖 AI Engineering & Prompting
* **[Andrew Ng's Full AI Prompting Course](https://www.youtube.com/watch?v=8ib4Qnh2HFE)** / **[DeepLearning.AI Official](https://www.deeplearning.ai/courses/ai-prompting-for-everyone)**
  * `Source Files` : `Full-AI-Prompting-Course-with-Andrew-Ng-ko.pdf` 대체 자료용 공식 링크
  * 앤드류 응(Andrew Ng) 교수가 직강하는 AI 파워유저용 고급 프롬프팅 강의 코스 (맥락 관리, 멀티 에이전트 설계 등).
  * `Type` : `Video Course` `Prompt Engineering` `DeepLearning.AI`

### 📐 Mathematics & Core Algorithms
* **[Mathematical Foundations of Machine Learning (Seongjai Kim)](https://www.youtube.com/@mathtalent)**
  * `Source Files` : `Machine_Learning_Lecture.pdf` 대체 자료용 공식 채널
  * 머신러닝 모델의 수학 공식을 엄밀하게 유도하는 강의 노트 배포처. SVM KKT 조건, PCA/SVD 분해 증명 포함.
  * `Type` : `Lecture Notes` `Machine Learning Math` `Matrix Decomposition`
* **[Calculus: Early Transcendentals Web Text](https://open.umn.edu/opentextbooks/textbooks/415)**
  * 미네소타 대학 오픈 텍스트북 라이브러리에 등록된 David Guichard 교수의 미적분학 오픈 교재. 경사하강법 최적화 독학용.
  * `Type` : `Open Textbook` `Calculus` `Optimization`
* **[Machine Learning Systems (Harvard Edge / MIT Press)](https://github.com/harvard-edge/cs249r_book)**
  * `Source Files` : `Machine-Learning-Systems.pdf` 대체 자료용 공식 저장소
  * 하버드 및 MIT 등에서 활용되는 단일 노드 최적화부터 대규모 분산 모델 인프라 구조까지 다루는 고품질 ML 시스템 전문 서적 리포지토리.
  * `Type` : `Open Book` `MLSys` `Infrastructure`
* **[Breaking the Sorting Barrier for Directed SSSP (arXiv)](https://arxiv.org/abs/2504.17033)**
  * `Source Files` : `Breaking the Sorting Barrier...pdf` 대체 자료용 공식 아카이브
  * 방향 그래프 최단 경로 알고리즘(SSSP) 분야에서 다익스트라의 시간 복잡도 정렬 장벽을 돌파한 최신 결정론적 알고리즘 연구 논문.
  * `Type` : `Research Paper` `Graph Algorithm` `arXiv`
