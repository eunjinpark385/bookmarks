# bookmarks
[English](./README_EN.md) | [한국어](./README.md)

Personal archive of interesting or useful references discovered during development and research, spanning various technical categories.

## 📂 Structure
* `README.md` - Curated list of useful web links and utilities (Korean)
* `README_EN.md` - Curated list of useful web links and utilities (English)
* `papers/` - Research paper analysis notes and core mechanism implementation notebooks [👉 Shortcuts](papers/)

---

## 📌 Curated Links

### 🌐 System / Infra
* **[Build Your Own Redis](https://build-your-own.org/redis/)**
  * A comprehensive guide to building core Redis functionalities from scratch using C/C++ or Go without external libraries<br>
    Ideal for learning Network Sockets, Protocol Parsing, and Event Loops
  * `Tags` : `Network` `Event Loop` `C/C++` `Go` `Low-Level`
* **[System Design Notes](https://github.com/liquidslr/system-design-notes)**
  * A well-structured summary of major architectural patterns used in large-scale distributed systems<br>
    Covers core infrastructures such as Load Balancing, Caching, and DB Sharding
  * `Tags` : `Architecture` `Distributed System` `Backend`
* **[Practice C Programming Projects](https://github.com/labex-labs/practice-c-programming-projects)**
  * A collection of practical C programming projects designed to strengthen low-level control fundamentals<br>
    Focuses on robust custom implementation of pointer operations and memory allocation
  * `Tags` : `C Language` `Memory Allocation` `Pointers`
* **[Computer Networking Fundamentals](https://labs.iximiuz.com/courses/computer-networking-fundamentals)**
  * An interactive networking practical course based on Linux virtual environments (Containers, Namespaces)<br>
    Provides simulation interfaces to thoroughly verify routing paths and TCP/IP flows
  * `Tags` : `Linux` `Networking` `TCP/IP` `Interactive`

### 🤖 AI / ML & Core Mathematics
* **[Math Behind Cross-Entropy Loss](https://outcomeschool.com/blog/math-behind-cross-entropy-loss)**
  * Analysis of the core loss function that forms the basis of classification and contrastive learning<br>
    Describes the mathematical derivation of Cross-Entropy Loss from an information theory perspective
  * `Tags` : `Information Theory` `Loss Function` `Math`
* **[Paper Reading (Mu Li)](https://github.com/mli/paper-reading)**
  * A repository of deep learning landmark paper analyses by Dr. Mu Li, former Principal Scientist at AWS<br>
    Provides intuitive code implementations and organized summaries from live paper-reading sessions
  * `Tags` : `Deep Learning` `Paper Reading` `Landmark Models`
* **[Transformer Explainer](https://github.com/poloclub/transformer-explainer)**
  * An interactive 3D visualization tool illustrating tensor operations inside the Transformer architecture<br>
    Visualizes Self-Attention and layer-by-layer data streams based on the GPT-2 model structure
  * `Tags` : `Transformer` `Visualization` `GPT-2` `Web Tool`
* **[Stanford CS229 Machine Learning Cheatsheets](https://github.com/afshinea/stanford-cs-229-machine-learning)**
  * Core summary charts and quick refreshers for Stanford's prestigious CS229 course<br>
    Covers supervised/unsupervised learning, deep learning math formulas, and probability/linear algebra basics
  * `Tags` : `Stanford CS229` `Cheatsheet` `Linear Algebra`
* **[Sophon AI Research Papers](https://sophon.at/papers)**
  * A discovery platform for tracking real-time trending AI research papers, models, and benchmarks<br>
    Perfect for keeping up with the bleeding edge across fields like language modeling and agents
  * `Tags` : `AI Trend` `Research Paper` `LLM` `Benchmark`

### 🛠 Tools & AI Productivity
* **[Understand Anything](https://github.com/Lum1104/Understand-Anything)**
  * An open-source tool designed to instantly capture the architectural picture of massive codebases or project wikis<br>
    Visualizes intricate architectural layers and function dependencies into an interactive Knowledge Graph
  * `Tags` : `Code Analysis` `Knowledge Graph` `Productivity` `Vibe Coding`
* **[Andrej Karpathy Skills Guidelines](https://github.com/multica-ai/andrej-karpathy-skills/tree/main)**
  * Practical coding guidelines derived from Andrej Karpathy's observations on LLM coding engineering pitfalls<br>
    Includes tailor-made custom rules and prompting tricks optimized for Claude Code and Cursor
  * `Tags` : `Karpathy` `LLM Coding` `Cursor` `Claude Code`
* **[Developer Roadmap](https://github.com/nilbuild/developer-roadmap)**
  * The official open-source repository for the globally referenced roadmap.sh developer career handbook<br>
    Features interactive learning paths mapped out neatly by job role or specific technology stack
  * `Tags` : `Career` `Roadmap` `Learning Path`

### 📊 Visualization & Utility
* **[Manim Community](https://github.com/ManimCommunity/manim)**
  * A programmatic animation engine used to generate precise mathematical explanations and algorithmic visualizations via Python<br>
    An open-source framework popular for producing high-quality 3Blue1Brown-style educational math videos
  * `Tags` : `Python` `Math Animation` `3blue1brown`
* **[VisuAlgo](https://visualgo.net/en)**
  * A visualization platform displaying step-by-step animations for core data structures and algorithm behaviors<br>
    Allows real-time tracking of data transitions across sorting, trees, and complex graph algorithms
  * `Tags` : `Data Structure` `Algorithm` `Animation`
* **[CSVistool (ArrayList)](https://csvistool.com/ArrayList)**
  * A dedicated visual simulator showing the exact inner mechanics of a dynamic array structure (ArrayList)<br>
    Intuitively illustrates array scaling mechanisms and data shifting during value insertions or deletions
  * `Tags` : `Array List` `Data Structure` `CS Basics`
* **[cobalt.tools](https://cobalt.tools)**
  * A clean web utility to extract raw media files directly without intrusive advertisements or tracking scripts<br>
    Supports fast downloads into the original format without annoying popup redirections or friction
  * `Tags` : `Media Downloader` `Privacy` `Web Utility`

### ✍ Writing / Review
* **[Google Engineering Practices](https://github.com/google/eng-practices/blob/master/review/reviewer/comments.md)**
  * Google's official internal handbook containing best-practice guidelines for professional code reviews<br>
    Summarizes constructive comment templates and standard engineering team communication expectations
  * `Tags` : `Code Review` `Google` `Engineering Culture`
* **[Academic Phrasebank](https://www.phrasebank.manchester.ac.uk/)**
  * A widely recognized academic English writing phrase repository hosted by the University of Manchester<br>
    Organizes standard vocabulary structures and formal sentences sorted by paper section (Intro, Methods, etc.)
  * `Tags` : `Academic Writing` `English` `Research Template`
* **[Write & Improve](https://writeandimprove.com/)**
  * An AI-powered, real-time English composition checking service designed by Cambridge University experts<br>
    Instantly detects grammatical errors and acts as an essay feedback tool for automated self-study
  * `Tags` : `AI Proofreading` `Cambridge` `Grammar Check`

---

## 📚 Books & Lecture Notes (Official Source Links)

### 💻 Operating Systems & Low-Level
* **[MIT xv6 RISC-V Source & Commentary Book](https://pdos.csail.mit.edu/6.1810/2025/xv6/)**
  * Official home repository for the educational Unix-like kernel xv6 used in MIT's core operating systems class<br>
    Serves as the official archive source for both `book-riscv-rev5.pdf` and `xv6-src-booklet-rev5.pdf` texts
  * `Type` : `University Textbook` `Operating System` `RISC-V`

### 🤖 AI Engineering & Prompting
* **[Andrew Ng's Full AI Prompting Course](https://www.youtube.com/watch?v=8ib4Qnh2HFE)** / **[DeepLearning.AI Official](https://www.deeplearning.ai/courses/ai-prompting-for-everyone)**
  * Advanced prompt engineering course video directory taught directly by global AI pioneer Professor Andrew Ng<br>
    Provides the official source channel outlining programmatic context management and multi-agent pipeline design
  * `Type` : `Video Course` `Prompt Engineering` `DeepLearning.AI`

### 📐 Mathematics & Core Algorithms
* **[Mathematical Foundations of Machine Learning (Seongjai Kim)](https://www.youtube.com/@mathtalent)**
  * Lecture material archive presenting rigorous mathematical derivations of early machine learning models<br>
    Acts as the primary source behind `Machine_Learning_Lecture.pdf` derivations, including SVM KKT and PCA/SVD proofs
  * `Type` : `Lecture Notes` `Machine Learning Math` `Matrix Decomposition`
* **[Calculus: Early Transcendentals Web Text](https://open.umn.edu/opentextbooks/textbooks/415)**
  * An open calculus textbook by Professor David Guichard listed in the University of Minnesota Open Textbook Library<br>
    Provides the underlying calculus foundation essential for self-studying modern optimization methods like Gradient Descent
  * `Type` : `Open Textbook` `Calculus` `Optimization`
* **[Machine Learning Systems (Harvard Edge / MIT Press)](https://github.com/harvard-edge/cs249r_book)**
  * An academic textbook used at Harvard and MIT covering topics ranging from single-node deployment to large-scale distributed training<br>
    The official public GitHub repository for accessing the open text originally listed as `Machine-Learning-Systems.pdf`
  * `Type` : `Open Book` `MLSys` `Infrastructure`
* **[Breaking the Sorting Barrier for Directed SSSP (arXiv)](https://arxiv.org/abs/2504.17033)**
  * Official paper publication link presenting a breakthrough deterministic algorithm for directed graphs<br>
    Breaks the classic Dijkstra time complexity sorting bottleneck for Single-Source Shortest Paths
  * `Type` : `Research Paper` `Graph Algorithm` `arXiv`
