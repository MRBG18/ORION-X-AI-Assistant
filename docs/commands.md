<div align="center">

# 📋 ORION X — Complete Command Reference

*Every command, every feature, fully documented.*

[![Back to README](https://img.shields.io/badge/←_Back_to_README-1E293B?style=flat-square)](../README.md)

</div>

---

## 📑 Table of Contents

| # | Category | Commands |
|---|----------|---------|
| 01 | [👋 Greeting & Conversation](#-01--greeting--conversation) | hey, hello, thanks, bye... |
| 02 | [🖥️ App & Software Control](#️-02--app--software-control) | open chrome, open vscode... |
| 03 | [🔍 Application Discovery](#-03--application-discovery) | list apps, count apps... |
| 04 | [🛑 Application Termination](#-04--application-termination) | close chrome, force quit... |
| 05 | [📁 File & Folder Search](#-05--file--folder-search) | find Main.py, where is... |
| 06 | [🌐 Web Search](#-06--web-search) | google X, search youtube... |
| 07 | [📊 Marks Prediction (ML)](#-07--marks-prediction-ml) | if i study for N hours... |
| 08 | [💼 Salary Prediction (ML)](#-08--salary-prediction-ml) | salary after N years... |
| 09 | [📧 Email Spam Detection](#-09--email-spam-detection) | check email - ... |
| 10 | [😊 Sentiment Analysis](#-10--sentiment-analysis) | check sentiment - ... |
| 11 | [⏰ Reminders & Alerts](#-11--reminders--alerts) | remind me in X minutes... |
| 12 | [🤝 Meeting Planner](#-12--meeting-planner) | schedule a meeting with... |
| 13 | [🧮 Advanced Mathematics](#-13--advanced-mathematics) | sqrt, average, min, max... |
| 14 | [🧠 Smart Help & Guidance](#-14--smart-help--guidance) | what can you do, help me... |
| 15 | [🔁 Daily Smart Routine](#-15--daily-smart-routine) | start my day, today summary... |
| 16 | [💡 Skill Suggestion Engine](#-16--skill-suggestion-engine) | i feel stressed... |

---

<br/>

## 👋 01 · Greeting & Conversation

> ORION X handles casual conversation naturally — no special syntax required.

```
hey
hii
hello
how are you
what's up
good morning
good evening
thanks
thank you so much
bye
goodbye
see you later
```

---

<br/>

## 🖥️ 02 · App & Software Control

> Launch any installed application using natural language.

```
open chrome
open google chrome
open vscode
open visual studio code
open calculator
open photos
open youtube
open notepad
open terminal
```

**How it works:**
- Fuzzy matches your input to installed application names
- Resolves aliases (e.g. `google chrome` → `chrome`)
- Launches via OS-native subprocess call

---

<br/>

## 🔍 03 · Application Discovery

> Explore what's installed on the system without opening a file manager.

```
list apps
list all apps
show installed applications
how many apps are installed
count apps
```

---

<br/>

## 🛑 04 · Application Termination

> Close, quit, or force-kill running applications.

```
close chrome
close vscode
quit calculator
exit photos
force close chrome
force close vscode
```

| Command Type | Behavior |
|-------------|----------|
| `close / quit / exit` | Graceful shutdown (sends quit signal) |
| `force close` | Immediate termination (kills process) |

---

<br/>

## 📁 05 · File & Folder Search

> Locate any file or folder on your system using natural language.

```
find Main.py
find doc1.pdf
find Final_Data.json
find resume
find logo
where is orion_x_logo.png
find config file
find data file
find assets
find controller.py
```

**Supported patterns:**
- Exact filename: `find Main.py`
- Keyword search: `find resume` (matches all files with "resume" in name)
- Natural question: `where is orion_x_logo.png`
- Category terms: `find data file`, `find config file`

---

<br/>

## 🌐 06 · Web Search

> Instantly search Google or YouTube from a voice or text command.

### Google Search

```
search google for python tutorials
google python tutorial
google machine learning basics
google weather today
google latest tech news
search Virat Kohli
search king of cricket
```

### YouTube Search & Playback

```
search youtube for python full course
search youtube for ai projects
open youtube and search tmkoc
youtube play music
```

---

<br/>

## 📊 07 · Marks Prediction (ML)

> Regression model trained to predict academic marks based on study hours.

```
if i study for 4 hours
if i study for 6 hours
if i study for 8 hours
i studied 5 hours
i studied for 3 hours today
study for 10 hours
what if i study 7 hours
```

**Model details:**
- Algorithm: Linear Regression
- Input: Study hours (numeric)
- Output: Predicted score / percentage
- Trained on: Student performance dataset

---

<br/>

## 💼 08 · Salary Prediction (ML)

> Forecasts expected salary based on years of professional experience.

```
salary after 1 year experience
salary after 2.5 year experience
salary after 3 year experience
salary after 5 year experience
salary after 7 years
salary after 10 year experience
expected salary with 4 years experience
salary with 6 years experience
```

**Model details:**
- Algorithm: Linear Regression
- Input: Years of experience (supports decimals like `2.5`)
- Output: Predicted salary (INR / annual)
- Trained on: Experience-salary benchmark dataset

---

<br/>

## 📧 09 · Email Spam Detection

> Classify raw email text as **Spam** or **Not Spam** using NLP.

**Syntax:** `check email - <email body text>`

```
check email - hey bg how are you
check email - meeting tomorrow at 10 am
check email - congratulations you won 1 lakh rupees
check email - claim your free reward now
does mail is spam - click link to win prize
received email is - project update attached
email is - limited offer act fast
check email - invoice for your purchase
```

**Trigger phrases:**
```
check email -
does mail is spam -
received email is -
email is -
```

**Output:** `✅ Not Spam` or `🚨 Spam Detected`

---

<br/>

## 😊 10 · Sentiment Analysis

> Detect the emotional tone of any piece of text.

**Syntax:** `<trigger> - <text to analyze>`

```
check sentiment - i feel very happy today
analyze sentiment - i am stressed
detect sentiment - this project is amazing
sentiment of this - i feel sad and demotivated
check sentiment - today is a great day
analyze sentiment - i am not feeling good
detect sentiment - i love ORION X
sentiment of this - i am disappointed
```

**Trigger phrases:**
```
check sentiment -
analyze sentiment -
detect sentiment -
sentiment of this -
```

**Output classes:** `😊 Positive` · `😐 Neutral` · `😞 Negative`

---

<br/>

## ⏰ 11 · Reminders & Alerts

> Set reminders by relative countdown or absolute clock time.

### Relative Reminders (countdown-based)

```
remind me to drink water in 1 minutes
remind me to study in 10 minutes
set a reminder for take break in 5 minutes
set a reminder to sleep in 30 minutes
```

### Absolute Reminders (clock-based)

```
remind me at 7:30 am
remind me at 2:15 pm
set reminder at 14:45
set reminder at 18:00
```

### View Reminders

```
show reminders
```

**Storage:** All reminders saved to `reminders.json` — persistent across sessions.

---

<br/>

## 🤝 12 · Meeting Planner

> Schedule and manage meetings with person, date, time, and topic.

### Schedule a Meeting

```
schedule a meeting with Bhargav on 25 Jan at 9:20 pm
schedule a meeting with Bhargav on 25 Jan at 10:11 pm for AI-ML
plan a meeting with Rahul on 1 Feb at 11:00 am
plan a meeting with Client on 10 Mar at 4:30 pm for Bank Discussion
```

**Syntax breakdown:**
```
schedule/plan a meeting with <name> on <date> at <time> [for <topic>]
```

| Field | Example |
|-------|---------|
| Person | `Bhargav`, `Rahul`, `Client` |
| Date | `25 Jan`, `1 Feb`, `10 Mar` |
| Time | `9:20 pm`, `11:00 am`, `14:45` |
| Topic (optional) | `AI-ML`, `Bank Discussion` |

### View Meetings

```
show meetings
```

**Storage:** All meetings saved to `meetings.json` — persistent across sessions.

---

<br/>

## 🧮 13 · Advanced Mathematics

> Full arithmetic engine with statistical functions, all from natural language.

### Basic Arithmetic

```
12-11
12-11+5
12 plus 5 minus 3
100 divided by 4
25 multiply 4
1-2-2-2
1224331-555-5555-55
```

### Statistical Operations

```
average of 10 20 30
average of 10 20 30 40
average of 12 18
min of 10 5 20
min of 3 8 1 9
max of 10 5 20
max of 45 22 89 11
```

### Percentage & Score Calculator

```
total marks is 500 i got 450
total marks is 600 i got 420
```

### Difference Calculator

```
difference between 600 and 470
difference between 1000 and 845
```

### Square Root

```
sqrt 144
sqrt 256
sqrt 81
```

**Supported operations:**

| Operation | Syntax Example | Result |
|-----------|---------------|--------|
| Addition | `12 plus 5` | `17` |
| Subtraction | `100 minus 40` | `60` |
| Multiplication | `25 multiply 4` | `100` |
| Division | `100 divided by 4` | `25.0` |
| Average | `average of 10 20 30` | `20.0` |
| Min | `min of 3 8 1` | `1` |
| Max | `max of 45 22 89` | `89` |
| Percentage | `total marks is 500 i got 450` | `90.0%` |
| Difference | `difference between 1000 and 845` | `155` |
| Square Root | `sqrt 144` | `12.0` |

---

<br/>

## 🧠 14 · Smart Help & Guidance

> Explore ORION X's capabilities interactively — built-in assistant guide.

### General Help

```
what can you do?
show commands
help me
what features do you have
how to use orion x
```

### Feature-Specific Explanations

```
what is - web search
what is - reminders
what is - sentiment analysis
what is - salary prediction
what is - advanced mathematics
```

**Syntax:** `what is - <feature name>`

---

<br/>

## 🔁 15 · Daily Smart Routine

> Get an intelligent morning briefing or end-of-day summary.

```
start my day
good morning
daily routine
today summary
```

**What it includes:**
- Current date & time greeting
- Pending reminders
- Scheduled meetings for today
- Motivational prompt or tip

---

<br/>

## 💡 16 · Skill Suggestion Engine

> ORION X detects your mood or context and proactively suggests relevant features.

```
i feel stressed
i feel very bad today
analyze sentiment - i am demotivated
```

**How it works:**
1. Detects negative sentiment or mood keywords in your input
2. Classifies emotional state (stressed / demotivated / sad / anxious)
3. Suggests relevant ORION X features that may help (e.g. reminders, routines, study tips)
4. Optionally runs sentiment analysis on the message itself

---

<br/>

---

<div align="center">

## ◈ Quick Reference Card

| 🎯 Goal | 💬 Say | 
|--------|--------|
| Open an app | `open <app name>` |
| Close an app | `close <app name>` |
| Find a file | `find <filename>` |
| Google something | `google <query>` |
| YouTube search | `search youtube for <query>` |
| Set reminder | `remind me to <task> in <N> minutes` |
| Schedule meeting | `schedule a meeting with <name> on <date> at <time>` |
| Predict marks | `if i study for <N> hours` |
| Predict salary | `salary after <N> year experience` |
| Check email spam | `check email - <email text>` |
| Analyze sentiment | `check sentiment - <text>` |
| Do math | `average of 10 20 30` / `sqrt 144` |
| Get help | `what can you do?` |

</div>

---

<div align="center">

[![Back to README](https://img.shields.io/badge/←_Back_to_README-1E293B?style=flat-square)](../README.md)
[![Demo Video](https://img.shields.io/badge/▶_Watch_Demo-FF0000?style=flat-square&logo=youtube)](https://drive.google.com/file/d/1heV0lzODjndfy4hlWVf8q_wPRK2MtFBY/view?usp=drivesdk)

*ORION X — Built by Bhargav Gondaliya*

</div>
