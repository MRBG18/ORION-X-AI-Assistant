<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0015,50:1a0a3e,100:2d1b69&height=160&section=header&text=ORION%20X%20—%20Command%20Reference&fontSize=42&fontColor=ffffff&fontAlignY=45&desc=Every%20command%20%7C%20Every%20feature%20%7C%20Fully%20documented&descAlignY=68&descSize=16&animation=fadeIn"/>

<br/>

<img src="https://img.shields.io/badge/Total%20Commands-100%2B-7C3AED?style=for-the-badge&labelColor=0a0015"/>
<img src="https://img.shields.io/badge/Categories-16-4F46E5?style=for-the-badge&labelColor=0a0015"/>
<img src="https://img.shields.io/badge/Works%20On-GUI%20%7C%20CLI%20%7C%20Voice-22C55E?style=for-the-badge&labelColor=0a0015"/>

</div>

---

## 📑 Table of Contents

| # | Category | Quick Commands |
|:-:|:--------|:--------------|
| [01](#-01--greeting--conversation) | 👋 Greeting & Conversation | hey, hello, thanks, bye... |
| [02](#-02--app--software-control) | 🖥️ App & Software Control | open chrome, open vscode... |
| [03](#-03--application-discovery) | 🔍 Application Discovery | list apps, count apps... |
| [04](#-04--application-termination) | 🛑 Application Termination | close chrome, force quit... |
| [05](#-05--file--folder-search) | 📁 File & Folder Search | find Main.py, where is... |
| [06](#-06--web-search--browser) | 🌐 Web Search & Browser | google X, search youtube... |
| [07](#-07--marks-prediction-ml) | 📊 Marks Prediction (ML) | if i study for N hours... |
| [08](#-08--salary-prediction-ml) | 💼 Salary Prediction (ML) | salary after N years... |
| [09](#-09--email-spam-detection) | 📧 Email Spam Detection | check email - ... |
| [10](#-10--sentiment-analysis) | 😊 Sentiment Analysis | check sentiment - ... |
| [11](#-11--reminders--alerts) | ⏰ Reminders & Alerts | remind me in X minutes... |
| [12](#-12--meeting-planner) | 🤝 Meeting Planner | schedule a meeting with... |
| [13](#-13--advanced-mathematics) | 🧮 Advanced Mathematics | sqrt, average, min, max... |
| [14](#-14--smart-help--guidance) | 🧠 Smart Help & Guidance | what can you do, help me... |
| [15](#-15--daily-smart-routine) | 🔁 Daily Smart Routine | start my day, today summary... |
| [16](#-16--skill-suggestion-engine) | 💡 Skill Suggestion Engine | i feel stressed... |

---

## 👋 01 · Greeting & Conversation

> ORION X handles casual conversation naturally — no special syntax required. The conversational layer  handles greetings, thanks, and farewells.

```
hey
hii
hello
how are you
what's up
good morning
good evening
good night
thanks
thank you
thank you so much
bye
goodbye
see you later
take care
```

---

## 🖥️ 02 · App & Software Control

> Launch any installed application using natural language. ORION X resolves aliases and launches the correct executable.

```
open chrome
open google chrome
open browser
open vscode
open visual studio code
open calculator
open calc
open photos
open youtube
open notepad
open terminal
open cmd
```



---

## 🔍 03 · Application Discovery

> Explore what's installed on the system without opening a file manager.

```
list apps
list all apps
show apps
show installed applications
show all installed apps
how many apps are installed
count apps
count all applications
what apps do i have
what apps are installed
```

**Output example:**
```
✦ Found 23 applications installed on your system:
  Chrome, VSCode, Calculator, Notepad, Photos...
```

---

## 🛑 04 · Application Termination

> Close, quit, or force-kill any running application. Two termination modes available.

```
close chrome
close vscode
close calculator
close notepad
quit calculator
quit chrome
exit photos
force close chrome
force close vscode
force close notepad
force quit chrome
kill chrome
```

| Command Type | Behavior | Internal Method |
|:------------:|:--------:|:---------------:|
| `close` / `quit` / `exit` | Graceful shutdown — sends quit signal | `terminate()` |
| `force close` / `force quit` / `kill` | Immediate kill — terminates process | `kill()` |

---

## 📁 05 · File & Folder Search

> Locate any file or folder on your system. Powered by `skills/automation`.

```
find Main.py
find controller.py
find hello.txt
find doc1.pdf
find data_full.json
find resume
find logo
find orion_x_logo.png
find mic.png
where is orion_x_logo.png
where is Main.py
find config file
find data file
find assets

```

**Supported search patterns:**

| Pattern Type | Example | Matches |
|:------------|:--------|:--------|
| Exact filename | `find Main.py` | Only `Main.py` |
| Keyword search | `find resume` | All files with "resume" in name |
| Natural question | `where is orion_x_logo.png` | Finds and shows full path |
| Category term | `find data file` | Files matching data-related names |
| Extension search | `find .json` | All JSON files |

---

## 🌐 06 · Web Search & Browser

> Instantly search Google or YouTube, or open any website from voice or text command.

### Google Search

```
google python tutorial
google machine learning basics
google weather today
google latest tech news
google Virat Kohli
google king of cricket
google Gujarat weather
google best AI projects 2024
search google for python tutorials
search google for data structures
search for machine learning course
search Lionel Messi
```

### YouTube Search & Playback

```
search youtube for python full course
search youtube for machine learning tutorial
search youtube for AI projects
search youtube for data science roadmap
open youtube and search tmkoc
open youtube and search motivational speech
youtube play music
youtube play lofi
youtube search python for beginners
```

**Trigger phrases for Google:** `google`, `search google for`, `search for`
**Trigger phrases for YouTube:** `search youtube for`, `youtube play`, `open youtube and search`

---

## 📊 07 · Marks Prediction (ML)

> Regression model predicts academic performance based on study hours. Model: `marks_predictor` using `marks_prediction_model.joblib`.

```
if i study for 1 hour
if i study for 2 hours
if i study for 3 hours
if i study for 4 hours
if i study for 5 hours
if i study for 6 hours
if i study for 7 hours
if i study for 8 hours
if i study for 9 hours
if i study for 10 hours
i studied 5 hours
i studied for 3 hours today
i studied for 6 hours
study for 10 hours
what if i study 7 hours
predict marks for 4 hours study
```

**Model details:**

```
Algorithm : Linear Regression
Input     : Study hours (numeric, float supported)
Output    : Predicted score out of 100
Dataset   : Student performance benchmark dataset
File      : skills/ml_models/models/marks_prediction_model.joblib
```

**Sample outputs:**
```
"if i study for 4 hours"  →  Predicted Marks: 64.2 / 100
"if i study for 8 hours"  →  Predicted Marks: 88.7 / 100
```

---

## 💼 08 · Salary Prediction (ML)

> Forecasts expected salary based on years of professional experience. Model: `salary_predictor.py` using `salary_model.joblib`.

```
salary after 1 year experience
salary after 2 year experience
salary after 2.5 year experience
salary after 3 year experience
salary after 4 years experience
salary after 5 year experience
salary after 6 year experience
salary after 7 years
salary after 8 year experience
salary after 10 year experience
expected salary with 4 years experience
salary with 6 years experience
predict salary for 5 years
what is salary after 3 years
```

**Model details:**

```
Algorithm : Linear Regression
Input     : Years of experience (supports decimals: 2.5, 3.5)
Output    : Estimated annual CTC in INR
Dataset   : Experience-salary benchmark dataset
File      : skills/ml_models/models/salary_model.joblib
```

**Sample outputs:**
```
"salary after 2 year experience"   →  Estimated CTC: ₹4.1 LPA
"salary after 5 year experience"   →  Estimated CTC: ₹8.4 LPA
"salary after 10 year experience"  →  Estimated CTC: ₹14.2 LPA
```

---

## 📧 09 · Email Spam Detection

> Classify raw email text as spam or legitimate using a trained NLP classifier. Model: `spam_predictor.py` using `spam_model.joblib`.

**Syntax:** `<trigger> - <email body text>`

### ✅ Legitimate Email Examples

```
check email - hey bg how are you
check email - meeting tomorrow at 10 am
check email - project update is attached please review
check email - your interview is scheduled for friday
check email - invoice for your recent purchase
check email - please find the report attached
does mail is spam - team standup at 9 am tomorrow
received email is - your order has been dispatched
email is - quarterly report is ready for review
```

### 🚨 Spam Email Examples

```
check email - congratulations you won 1 lakh rupees
check email - claim your free reward now click here
check email - you have been selected win iphone
check email - limited offer act fast discount 90%
check email - click link to win prize today
does mail is spam - click link to win prize
received email is - you are selected for lottery
email is - free money transfer urgent response needed
```

**Trigger phrases:**
```
check email -
does mail is spam -
received email is -
email is -
```

**Output format:**
```
🚨 SPAM DETECTED      (confidence: 97.3%)
✅ LEGITIMATE EMAIL   (confidence: 99.1%)
```

---

## 😊 10 · Sentiment Analysis

> Detect the emotional tone of any text. Model: `sentiment_predictor.py` using `sentiment_model.joblib`.

**Syntax:** `<trigger> - <text to analyze>`

### 😊 Positive Sentiment Examples

```
check sentiment - i feel very happy today
check sentiment - today is a great day
check sentiment - i love ORION X
analyze sentiment - this project is amazing
analyze sentiment - i am feeling great
detect sentiment - this is fantastic work
sentiment of this - i am excited about the future
sentiment of this - i just got promoted today
```

### 😟 Negative Sentiment Examples

```
check sentiment - i am not feeling good
check sentiment - i feel sad and demotivated
analyze sentiment - i am stressed about my exams
analyze sentiment - i am disappointed with the results
detect sentiment - i feel very bad today
detect sentiment - everything is going wrong
sentiment of this - i am anxious and worried
sentiment of this - i hate this situation
```

### 😐 Neutral Sentiment Examples

```
check sentiment - today i went to college
analyze sentiment - the meeting is scheduled for tomorrow
detect sentiment - i have a project due next week
sentiment of this - it is currently 3 pm
```

**Trigger phrases:**
```
check sentiment -
analyze sentiment -
detect sentiment -
sentiment of this -
```

**Output format:**
```
😊 POSITIVE   (score: 0.94)
😐 NEUTRAL    (score: 0.71)
😟 NEGATIVE   (score: 0.81)
```

---

## ⏰ 11 · Reminders & Alerts

> Set time-based reminders using relative countdowns or absolute clock times. Stored in `Json/reminders.json`.

### Relative Reminders (countdown-based)

```
remind me to drink water in 1 minutes
remind me to drink water in 5 minutes
remind me to study in 10 minutes
remind me to take a break in 15 minutes
remind me to call mom in 20 minutes
remind me to exercise in 30 minutes
set a reminder for take break in 5 minutes
set a reminder to sleep in 30 minutes
set a reminder for submit assignment in 60 minutes
```

### Absolute Reminders (clock-based)

```
remind me at 7:30 am
remind me at 8:00 am
remind me at 10:15 am
remind me at 2:15 pm
remind me at 6:00 pm
set reminder at 14:45
set reminder at 18:00
set reminder at 09:30
set reminder at 21:00
```

### Reminder Management

```
show reminders
list reminders
view reminders
what are my reminders
show all reminders
```

**Storage:** `Json/reminders.json` — persistent across sessions, survives restarts.

---

## 🤝 12 · Meeting Planner

> Schedule and manage professional meetings with person, date, time, and topic. Stored in `Json/meetings.json`.

### Schedule a Meeting

**Full syntax:**
```
schedule/plan a meeting with <name> on <date> at <time> [for <topic>]
```

```
schedule a meeting with Bhargav on 25 Jan at 9:20 pm
schedule a meeting with Bhargav on 25 Jan at 10:11 pm for AI-ML
schedule a meeting with Rahul on 1 Feb at 11:00 am
schedule a meeting with Rahul on 1 Feb at 11:00 am for Project Review
plan a meeting with Client on 10 Mar at 4:30 pm for Bank Discussion
plan a meeting with Team on 15 Feb at 10:00 am for Sprint Planning
schedule a meeting with Manager on 20 Jan at 3:00 pm
schedule a meeting with Prof Sharma on 5 Feb at 9:00 am for Research
```

**Parsed fields:**

| Field | Example Values | Required |
|:-----:|:--------------:|:--------:|
| Person | Bhargav, Rahul, Client, Team | ✅ Yes |
| Date | 25 Jan, 1 Feb, 10 Mar | ✅ Yes |
| Time | 9:20 pm, 11:00 am, 14:45 | ✅ Yes |
| Topic | AI-ML, Bank Discussion, Sprint Planning | Optional |

### View Meetings

```
show meetings
list meetings
view meetings
what meetings do i have
show all meetings
my schedule
```

**Storage:** `Json/meetings.json` — persistent across sessions.

---

## 🧮 13 · Advanced Mathematics

> Full natural language arithmetic engine. Parses and computes math expressions from plain English.
> Powered by `math_engine` and `math_parser`.

### Basic Arithmetic

```
12-11
12-11+5
12 plus 5 minus 3
100 divided by 4
25 multiply 4
1-2-2-2
1224331-555-5555-55
500 plus 200
1000 minus 350
7 multiply 8
200 divided by 5
```

### Statistical Operations

```
average of 10 20 30
average of 10 20 30 40
average of 12 18 24 36
average of 5 10 15 20 25
min of 10 5 20
min of 3 8 1 9 2
min of 45 22 89 11
max of 10 5 20
max of 45 22 89 11
max of 3 8 1 9 100
```

### Percentage & Score Calculator

```
total marks is 500 i got 450
total marks is 600 i got 420
total marks is 100 i got 87
total marks is 1000 i got 830
total is 200 i got 180
```

### Difference Calculator

```
difference between 600 and 470
difference between 1000 and 845
difference between 500 and 299
difference between 100 and 47
```

### Square Root

```
sqrt 144
sqrt 256
sqrt 81
sqrt 625
sqrt 49
sqrt 100
```

### Full Operation Reference

| Operation | Syntax Example | Result |
|:---------:|:--------------:|:------:|
| Addition | `12 plus 5` | `17` |
| Subtraction | `100 minus 40` | `60` |
| Multiplication | `25 multiply 4` | `100` |
| Division | `100 divided by 4` | `25.0` |
| Chained | `12 plus 5 minus 3` | `14` |
| Average | `average of 10 20 30` | `20.0` |
| Min | `min of 3 8 1 9` | `1` |
| Max | `max of 45 22 89 11` | `89` |
| Percentage | `total marks is 500 i got 450` | `90.0%` |
| Difference | `difference between 1000 and 845` | `155` |
| Square Root | `sqrt 144` | `12.0` |

---

## 🧠 14 · Smart Help & Guidance

> Explore ORION X's capabilities interactively — built-in assistant guide. Powered by `skills/help` and `skills/info`.

### General Help

```
what can you do?
show commands
help me
what features do you have
how to use orion x
capabilities
what are your skills
tell me what you can do
```

### Feature-Specific Explanations

**Syntax:** `what is - <feature name>`

```
what is - web search
what is - reminders
what is - sentiment analysis
what is - spam detection
what is - salary prediction
what is - marks prediction
what is - advanced mathematics
what is - meeting scheduler
what is - daily routine
what is - app control
what is - file search
what is - skill suggestion
```

**Output:** ORION X explains the feature, shows the syntax, and gives example inputs/outputs.

---

## 🔁 15 · Daily Smart Routine

> Get an intelligent daily briefing powered by `daily_routine`.

```
start my day
good morning
daily routine
today summary
morning briefing
what's on today
my daily plan
start daily routine
```

**What the daily routine includes:**

1. 🕐 **Current date & time** with a personalized greeting
2. 📋 **Pending reminders** — lists any active reminders from `reminders.json`
3. 📅 **Today's meetings** — shows meetings scheduled for today from `meetings.json`
4. 💡 **Motivational prompt** — a context-aware tip or daily motivational line

---

## 💡 16 · Skill Suggestion Engine

> ORION X detects your mood or context and proactively suggests relevant features.
> Powered by `intelligence/suggestion_engine`.

```
i feel stressed
i feel very bad today
i am very anxious
i feel demotivated
i am sad today
i feel overwhelmed
i am not feeling well
i am frustrated
i feel lost today
analyze sentiment - i am demotivated
check sentiment - i feel terrible
i need help with my mood
i am burned out
```

**How the suggestion engine works:**

```
Step 1: Detect emotional keywords (stressed, sad, anxious, demotivated...)
Step 2: Classify emotional state
Step 3: Map to relevant ORION X features
Step 4: Suggest + optionally auto-run sentiment analysis

Example:
  Input: "i feel stressed"
  → Detected: NEGATIVE_EMOTION (stressed)
  → Suggestion: "You might benefit from setting a break reminder."
               "Try: remind me to take a break in 15 minutes"
  → Auto-runs: Sentiment analysis on the input
  → Output: 😟 NEGATIVE (score: 0.82)
```

---

<div align="center">

## ◈ Quick Reference Card

| 🎯 Goal | 💬 Say | Module |
|:--------|:-------|:-------|
| Open an app | `open <app name>` | System / App Control |
| Close an app | `close <app name>` | System / App Control |
| Force close | `force close <app name>` | System / App Control |
| Find a file | `find <filename>` | Automation / File Ops |
| Google search | `google <query>` | Web Intelligence |
| YouTube search | `search youtube for <query>` | Web Intelligence |
| Set reminder (relative) | `remind me to <task> in <N> minutes` | Automation / Reminders |
| Set reminder (absolute) | `remind me at <time>` | Automation / Reminders |
| Schedule a meeting | `schedule a meeting with <name> on <date> at <time>` | Automation / Meetings |
| Predict exam marks | `if i study for <N> hours` | ML Models / Marks |
| Predict salary | `salary after <N> year experience` | ML Models / Salary |
| Check email for spam | `check email - <email text>` | ML Models / Spam |
| Analyze text sentiment | `check sentiment - <text>` | ML Models / Sentiment |
| Do math | `average of 10 20 30` / `sqrt 144` | Math Engine |
| Get help | `what can you do?` | Help / Info |
| Start daily routine | `start my day` | Routines |
| Mood-aware suggestions | Express how you feel naturally | Suggestion Engine |

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=twinkling"/>

<sub>ORION X Command Reference · Built by Bhargav Gondaliya · AI / ML Engineer</sub>

</div>
