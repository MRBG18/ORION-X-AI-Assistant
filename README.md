<div align="center">

<!-- HERO BANNER -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=ORION%20X&fontSize=90&fontColor=ffffff&fontAlignY=38&desc=Autonomous%20AI%20Assistant%20System&descAlignY=58&descSize=22&animation=fadeIn"/>

<br/>

<!-- ANIMATED TITLE -->

<a href="#">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=28&duration=3000&pause=1000&color=7C3AED&center=true&vCenter=true&multiline=true&width=800&height=80&lines=Intelligent+%E2%80%A2+Autonomous+%E2%80%A2+Adaptive;NLP+%7C+ML+%7C+Automation+%7C+Voice+%7C+GUI" alt="Typing SVG" />
</a>

<br/><br/>

<!-- BADGE ROW 1 -->

<img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PySide6-GUI-41CD52?style=for-the-badge&logo=qt&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/spaCy-NLP-09A3D5?style=for-the-badge&logo=spacy&logoColor=white"/>

<br/>

<!-- BADGE ROW 2 -->

<img src="https://img.shields.io/badge/TF--IDF-Intent%20Engine-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Voice-Enabled-EF4444?style=for-the-badge&logo=microphone&logoColor=white"/>
<img src="https://img.shields.io/badge/Status-Stable%20%E2%9C%94-22C55E?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Architecture-Stateless-F59E0B?style=for-the-badge"/>

<br/><br/>

<!-- DEMO VIDEO CTA -->

<a href="https://drive.google.com/file/d/1heV0lzODjndfy4hlWVf8q_wPRK2MtFBY/view?usp=drivesdk">
  <img src="https://img.shields.io/badge/▶️%20WATCH%20LIVE%20DEMO-FF0000?style=for-the-badge&logo=youtube&logoColor=white&labelColor=1a1a1a" height="45"/>
</a>

<br/><br/>

</div>

-----

## ◈ What is ORION X?

<div align="center">
<table>
<tr>
<td width="60%">

**ORION X** is a full-stack AI assistant that bridges the gap between natural language and real-world system execution. It’s not just a chatbot — it’s a complete autonomous agent with:

- 🧠 **Machine Learning** at its core (TF-IDF + Logistic Regression)
- 🗣️ **NLP pipelines** powered by spaCy + custom rule engines
- 🖥️ **Triple interface** — GUI, CLI, and Voice
- ⚙️ **Real automation** — apps, files, web, reminders, and more

Built as a **modular, stateless system** with JSON-based memory and a professional-grade UX.

</td>
<td width="40%" align="center">

```
┌─────────────────────┐
│     ORION X CORE    │
│  ┌───────────────┐  │
│  │  Intent Layer │  │
│  │  TF-IDF + LR  │  │
│  └──────┬────────┘  │
│         ▼           │
│  ┌───────────────┐  │
│  │   NER Engine  │  │
│  │ spaCy + Rules │  │
│  └──────┬────────┘  │
│         ▼           │
│  ┌───────────────┐  │
│  │  Skill Router │  │
│  │  10+ Modules  │  │
│  └───────────────┘  │
└─────────────────────┘
```

</td>
</tr>
</table>
</div>

-----

## ◈ Interface Modes

<div align="center">

|Interface  |Technology    |Use Case                                  |
|:---------:|:------------:|:----------------------------------------:|
|🖥️ **GUI**  |PySide6 (Qt6) |Primary visual interface with voice button|
|💻 **CLI**  |Pure Python   |Lightweight terminal interaction          |
|🎤 **Voice**|Built into GUI|Hands-free command execution              |

</div>

-----

## ◈ Feature Arsenal

<details>
<summary><b>🗣️ Natural Language Understanding</b></summary>

<br/>

|Capability           |Details                                                          |
|---------------------|-----------------------------------------------------------------|
|Intent Classification|TF-IDF vectorizer + Logistic Regression trained on custom dataset|
|Entity Extraction    |spaCy NER + custom rule-based patterns                           |
|Command Parsing      |Multi-token, multi-pattern phrase resolution                     |
|Context Handling     |Stateless per-turn with smart defaults                           |

**Example Inputs:**

```
"open chrome"              → APP_OPEN intent + entity: chrome
"search python tutorials"  → WEB_SEARCH intent + query: python tutorials
"remind me in 5 minutes"   → REMINDER_SET intent + delta: 5min
```

</details>

<details>
<summary><b>⚙️ System Automation</b></summary>

<br/>

```
┌─────────────────────────────────────────────────────┐
│  APP CONTROL         FILE SYSTEM       DISCOVERY     │
│  ─────────────       ──────────────    ──────────    │
│  ✦ Open apps         ✦ Find files      ✦ List apps   │
│  ✦ Close apps        ✦ Locate paths    ✦ Count apps  │
│  ✦ Force quit        ✦ Folder search   ✦ Show info   │
└─────────────────────────────────────────────────────┘
```

- Works with **Chrome, VSCode, Calculator, Photos, Notepad, Terminal, YouTube**
- Supports `open`, `close`, `quit`, `exit`, and `force close` verbs
- File search by name, extension, or keyword across the system

</details>

<details>
<summary><b>🌐 Web Intelligence</b></summary>

<br/>

|Command Pattern             |Action                           |
|----------------------------|---------------------------------|
|`google [query]`            |Opens Google search for the query|
|`search google for [query]` |Direct Google search             |
|`search youtube for [query]`|YouTube search automation        |
|`youtube play [content]`    |Direct YouTube playback          |

</details>

<details>
<summary><b>📊 Machine Learning Predictions</b></summary>

<br/>

**🎓 Marks Predictor**

> Predicts exam performance based on study hours using regression model

```
Input:  "if i study for 6 hours"
Output: Predicted marks → 82.4 / 100
```

**💼 Salary Estimator**

> Forecasts salary based on years of experience

```
Input:  "salary after 3 years experience"
Output: Estimated CTC → ₹6.2 LPA
```

Both models trained on curated datasets with real-world distributions.

</details>

<details>
<summary><b>📧 NLP Intelligence</b></summary>

<br/>

**Email Spam Detector**

```
check email - congratulations you won 1 lakh rupees
→ 🚨 SPAM DETECTED (confidence: 97.3%)

check email - meeting tomorrow at 10 am  
→ ✅ LEGITIMATE (confidence: 99.1%)
```

**Sentiment Analyzer**

```
check sentiment - i feel very happy today
→ 😊 POSITIVE (score: 0.94)

analyze sentiment - i am stressed
→ 😟 NEGATIVE (score: 0.81)
```

</details>

<details>
<summary><b>⏰ Productivity Suite</b></summary>

<br/>

**Reminders**

- Relative: `"remind me to drink water in 5 minutes"`
- Absolute: `"remind me at 7:30 am"`
- Management: `"show reminders"`

**Meeting Scheduler**

```
"schedule a meeting with Bhargav on 25 Jan at 9:20 pm for AI-ML"
→ ✅ Meeting saved: Bhargav | Jan 25 | 21:20 | Topic: AI-ML
```

</details>

<details>
<summary><b>🧮 Advanced Math Engine</b></summary>

<br/>

|Operation  |Example Input                    |Output|
|-----------|---------------------------------|------|
|Arithmetic |`12 plus 5 minus 3`              |`14`  |
|Percentage |`total 500 i got 450`            |`90%` |
|Statistics |`average of 10 20 30`            |`20.0`|
|Min / Max  |`max of 45 22 89 11`             |`89`  |
|Square Root|`sqrt 144`                       |`12.0`|
|Difference |`difference between 1000 and 845`|`155` |

</details>

<details>
<summary><b>🧠 Smart Suggestions & Help</b></summary>

<br/>

- `what can you do?` — Full capability overview
- `what is - sentiment analysis` — Module-specific explanation
- `i feel stressed` → Triggers wellness tip + mood-aware response
- `start my day` → Daily routine launcher with weather + reminders

</details>

-----

## ◈ Architecture

```
╔══════════════════════════════════════════════════════════════╗
║                    ORION X ARCHITECTURE                       ║
╠══════════════════════════════════════════════════════════════╣
║                                                               ║
║   INPUT LAYER                                                 ║
║   ┌──────────┐  ┌──────────┐  ┌──────────┐                  ║
║   │  GUI     │  │  CLI     │  │  Voice   │                   ║
║   │ PySide6  │  │ Console  │  │ SpeechRec│                   ║
║   └────┬─────┘  └────┬─────┘  └────┬─────┘                  ║
║        └─────────────┴─────────────┘                         ║
║                       │                                       ║
║   PROCESSING LAYER    ▼                                       ║
║   ┌───────────────────────────────────┐                       ║
║   │         Intent Classifier        │                        ║
║   │    TF-IDF Vectorizer + LogReg     │                       ║
║   └──────────────┬────────────────────┘                      ║
║                  ▼                                            ║
║   ┌───────────────────────────────────┐                       ║
║   │           NER Engine             │                        ║
║   │     spaCy + Rule-Based Patterns  │                        ║
║   └──────────────┬────────────────────┘                      ║
║                  ▼                                            ║
║   SKILL ROUTER   │                                            ║
║   ┌──────────────▼────────────────────┐                       ║
║   │  AppControl │ WebSearch │ MLModel │                       ║
║   │  FileSearch │ Reminders │ NLPCore │                       ║
║   │  MathEngine │ Scheduler │ Suggest │                       ║
║   └──────────────────────────────────┘                       ║
║                  │                                            ║
║   STORAGE LAYER  ▼                                            ║
║   ┌───────────────────────────────────┐                       ║
║   │    JSON Storage (Stateless)      │                        ║
║   │  reminders.json | meetings.json  │                        ║
║   └───────────────────────────────────┘                       ║
╚══════════════════════════════════════════════════════════════╝
```

-----

## ◈ Screenshots

<div align="center">

### 🖥️ GUI Interface

![GUI](screenshots/GUI.jpeg)

### 💻 CLI Interaction

![CLI](screenshots/CLI.jpeg)

### 🎤 Voice Control

![Voice](screenshots/Voice%20Control.jpeg)

</div>

-----

## ◈ Tech Stack

<div align="center">

|Layer              |Technology                                                                                                       |
|:-----------------:|:---------------------------------------------------------------------------------------------------------------:|
|Language           |![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)              |
|GUI Framework      |![Qt](https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white)                     |
|ML / Classification|![sklearn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)|
|NLP                |![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square)                                            |
|Voice              |![SpeechRecognition](https://img.shields.io/badge/SpeechRecognition-EF4444?style=flat-square)                    |
|Data Storage       |![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)                    |
|Text Vectorization |`TF-IDF`                                                                                                         |
|Classifier         |`Logistic Regression`                                                                                            |

</div>

-----

## ◈ Repository Structure

```
ORION-X-AI-Assistant/
│
├── 📹 OrionX Demo Video.MP4
├── 📄 README.md
│
├── 📁 screenshots/
│   ├── 🖼️ CLI.jpeg
│   ├── 🖼️ GUI.jpeg
│   └── 🖼️ Voice Control.jpeg
│
└── 📁 docs/
    └── 📋 commands.md
```

-----

## ◈ Why ORION X Stands Out

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                                                              │
│   Basic ML Project      vs      ORION X                     │
│   ───────────────────           ──────────────────          │
│   ✗ Single model                ✓ 10+ integrated modules    │
│   ✗ No real execution           ✓ Real system automation    │
│   ✗ No user interface           ✓ GUI + CLI + Voice         │
│   ✗ Static predictions          ✓ Live NLP + intent engine  │
│   ✗ No productivity tools       ✓ Reminders + Scheduling    │
│   ✗ Single input mode           ✓ Multi-modal interaction   │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

</div>

ORION X is a **complete AI ecosystem** — not a demo, not a toy. It integrates ML models, real-world automation, a professional NLP pipeline, and multi-modal UX into a single cohesive system.

-----

## ◈ Commands Reference

📋 **[View Complete Command Reference →](docs/commands.md)**

Includes all 100+ test commands across every module — greetings, app control, ML predictions, NLP, math, reminders, web search, and more.

-----

## ◈ Built By

<div align="center">

<br/>

**Bhargav Gondaliya**

`AI / ML Engineer`

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)

<br/>

</div>

-----

## ◈ Notice

> 🔒 **Source code is private.**  
> This repository exists for **demonstration and portfolio purposes only.**  
> All features shown are fully functional in the private codebase.

-----

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer"/>

<sub>ORION X · Built with intelligence · Powered by ML + NLP</sub>

</div>
