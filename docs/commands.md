<div align="center">

# ⚡ ORION X — Complete Command Reference

<img src="https://img.shields.io/badge/Commands-100%2B-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Modules-10%2B-3B82F6?style=for-the-badge"/>
<img src="https://img.shields.io/badge/NLP%20Powered-spaCy%20%2B%20TF--IDF-22C55E?style=for-the-badge"/>

</div>

-----

> 📌 **How to Read This Guide**
> 
> - Commands shown in `code blocks` are exact inputs you can type or speak
> - `[value]` means replace with your own input
> - All commands work in **GUI**, **CLI**, and **Voice** modes

-----

## 📑 Table of Contents

|# |Module                                                           |Commands|
|--|-----------------------------------------------------------------|--------|
|1 |[👋 Greetings & Conversation](#-greetings--conversation)          |12      |
|2 |[🖥️ App Control — Open](#️-app-control--open)                      |9       |
|3 |[🔍 Application Discovery](#-application-discovery)               |5       |
|4 |[🛑 App Control — Close](#-app-control--close)                    |6       |
|5 |[📁 File & Folder Search](#-file--folder-search)                  |10      |
|6 |[🌐 Web Search](#-web-search)                                     |11      |
|7 |[📊 Marks Prediction (ML)](#-marks-prediction-ml)                 |7       |
|8 |[💼 Salary Prediction (ML)](#-salary-prediction-ml)               |8       |
|9 |[📧 Email Spam Detection](#-email-spam-detection)                 |8       |
|10|[😊 Sentiment Analysis](#-sentiment-analysis)                     |8       |
|11|[⏰ Reminders & Alerts](#-reminders--alerts)                      |9       |
|12|[🤝 Meeting Planner](#-meeting-planner)                           |5       |
|13|[🧮 Advanced Mathematics](#-advanced-mathematics)                 |21      |
|14|[🧠 Smart Help / Capability Guide](#-smart-help--capability-guide)|10      |
|15|[🔁 Daily Routine](#-daily-smart-routine)                         |4       |
|16|[💡 Skill Suggestion Engine](#-skill-suggestion-engine)           |3       |

-----

## 👋 Greetings & Conversation

> Handles casual conversation, pleasantries, and social interactions.

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

**Expected Behavior:** ORION X responds with context-aware, friendly replies. `good morning` triggers the daily routine module.

-----

## 🖥️ App Control — Open

> Launch any installed application by name. Supports aliases and full names.

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

**Supported Aliases:**

|Alias       |Resolves To       |
|------------|------------------|
|`chrome`    |Google Chrome     |
|`vscode`    |Visual Studio Code|
|`calculator`|System Calculator |
|`photos`    |Photos App        |

-----

## 🔍 Application Discovery

> Inspect what’s installed on the system.

```
list apps
list all apps
show installed applications
how many apps are installed
count apps
```

**Expected Output:** Returns a count and/or enumerated list of installed applications on the system.

-----

## 🛑 App Control — Close

> Terminate running applications gracefully or by force.

```
close chrome
close vscode
quit calculator
exit photos
force close chrome
force close vscode
```

**Verb Mapping:**

|Verb                     |Behavior              |
|-------------------------|----------------------|
|`close` / `quit` / `exit`|Graceful termination  |
|`force close`            |Immediate process kill|

-----

## 📁 File & Folder Search

> Locate files and folders anywhere on the system by name, keyword, or extension.

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

**Tips:**

- Use partial names: `find resume` will match `resume_v2.pdf`, `my_resume.docx`, etc.
- Extension search: `find .json` returns all JSON files
- Keyword search: `find config` matches any file with “config” in the name

-----

## 🌐 Web Search

> Open Google or YouTube searches directly from voice or text.

```
search google for python tutorials
google python tutorial
google machine learning basics
search youtube for python full course
search youtube for ai projects
open youtube and search tmkoc
youtube play music
search Virat Kohli
search king of cricket
google weather today
google latest tech news
```

**Routing Logic:**

```
google [query]        →  Opens google.com/search?q=[query]
youtube [query]       →  Opens youtube.com/search?q=[query]
youtube play [topic]  →  Opens YouTube and plays first result
```

-----

## 📊 Marks Prediction (ML)

> Predicts exam score based on study hours using a trained regression model.

```
if i study for 4 hours
if i study for 6 hours
if i study for 8 hours
i studied 5 hours
i studied for 3 hours today
study for 10 hours
what if i study 7 hours
```

**Model Info:**

- Algorithm: Linear / Polynomial Regression
- Input: Study hours (numeric)
- Output: Predicted marks out of 100

**Sample Predictions:**

|Hours|Predicted Score|
|-----|---------------|
|3h   |~58 / 100      |
|6h   |~76 / 100      |
|10h  |~94 / 100      |

-----

## 💼 Salary Prediction (ML)

> Estimates salary based on years of work experience using a trained model.

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

**Model Info:**

- Algorithm: Linear Regression
- Input: Years of experience (numeric, supports decimals)
- Output: Estimated annual salary (₹ LPA)

**Sample Predictions:**

|Experience|Estimated Salary|
|----------|----------------|
|1 year    |~₹3.5 LPA       |
|5 years   |~₹8.2 LPA       |
|10 years  |~₹18.5 LPA      |

-----

## 📧 Email Spam Detection

> Classifies email content as spam or legitimate using NLP classification.

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

**Input Format:** `check email - [email text]`

**Classification Labels:**

|Label       |Confidence Threshold|
|------------|--------------------|
|🚨 SPAM      |> 0.6 probability   |
|✅ LEGITIMATE|> 0.6 probability   |

**Spam Indicators Detected:** prize/win/reward language, urgent CTAs, suspicious links, financial promises.

-----

## 😊 Sentiment Analysis

> Detects the emotional tone of any text — positive, negative, or neutral.

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

**Input Format:** `[trigger] - [text to analyze]`

**Trigger Words:** `check sentiment`, `analyze sentiment`, `detect sentiment`, `sentiment of this`

**Output Scale:**

```
😊 POSITIVE   →  score: 0.7 to 1.0
😐 NEUTRAL    →  score: 0.4 to 0.7
😟 NEGATIVE   →  score: 0.0 to 0.4
```

-----

## ⏰ Reminders & Alerts

> Set smart reminders by relative time or exact clock time.

```
remind me to drink water in 1 minutes
remind me to study in 10 minutes
set a reminder for take break in 5 minutes
set a reminder to sleep in 30 minutes
remind me at 7:30 am
remind me at 2:15 pm
set reminder at 14:45
set reminder at 18:00
show reminders
```

**Formats Supported:**

|Format            |Example                   |
|------------------|--------------------------|
|Relative (minutes)|`remind me in [N] minutes`|
|Absolute (12h)    |`remind me at 7:30 am`    |
|Absolute (24h)    |`set reminder at 14:45`   |
|List all          |`show reminders`          |

**Storage:** Reminders persisted in `reminders.json` with timestamp and label.

-----

## 🤝 Meeting Planner

> Schedule, store, and retrieve meetings with person, date, time, and topic.

```
schedule a meeting with Bhargav on 25 Jan at 9:20 pm
schedule a meeting with Bhargav on 25 Jan at 10:11 pm for AI-ML
plan a meeting with Rahul on 1 Feb at 11:00 am
plan a meeting with Client on 10 Mar at 4:30 pm for Bank Discussion
show meetings
```

**Parsed Fields:**

|Field |Extracted From          |
|------|------------------------|
|Person|`with [Name]`           |
|Date  |`on [Day Month]`        |
|Time  |`at [HH:MM am/pm]`      |
|Topic |`for [Topic]` (optional)|

**Storage:** Persisted in `meetings.json` with full structured data.

-----

## 🧮 Advanced Mathematics

> Full-featured math engine supporting natural language expressions.

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

### Statistics

```
average of 10 20 30
average of 10 20 30 40
average of 12 18
```

### Percentage

```
total marks is 500 i got 450       →  90%
total marks is 600 i got 420       →  70%
```

### Difference

```
difference between 600 and 470     →  130
difference between 1000 and 845    →  155
```

### Min / Max

```
min of 10 5 20                     →  5
min of 3 8 1 9                     →  1
max of 10 5 20                     →  20
max of 45 22 89 11                 →  89
```

### Square Root

```
sqrt 144                           →  12.0
sqrt 256                           →  16.0
sqrt 81                            →  9.0
```

**Supported Natural Language Keywords:**
`plus`, `minus`, `multiply`, `divided by`, `average of`, `min of`, `max of`, `sqrt`, `difference between`, `total marks`, `i got`

-----

## 🧠 Smart Help / Capability Guide

> Discover what ORION X can do and get module-specific explanations.

```
what can you do?
show commands
help me
what features do you have
how to use orion x
what is - web search
what is - reminders
what is - sentiment analysis
what is - salary prediction
what is - advanced mathematics
```

**`what is - [module]` explains:**

- What the module does
- How to use it
- Example commands
- Expected output format

-----

## 🔁 Daily Smart Routine

> Start your day with a smart briefing from ORION X.

```
start my day
good morning
daily routine
today summary
```

**Routine includes:**

- 🕐 Current time and date
- ☁️ Weather summary (if connected)
- 📋 Pending reminders for today
- 🤝 Meetings scheduled for today
- 💡 Motivational tip or suggestion

-----

## 💡 Skill Suggestion Engine

> Detects emotional cues and proactively offers personalized suggestions.

```
i feel stressed
i feel very bad today
analyze sentiment - i am demotivated
```

**Trigger Conditions:** Negative sentiment detected in input or explicit emotional keywords.

**Response Includes:**

- 🌿 Wellness tip (breathing, break suggestion)
- 📚 Productivity recommendation
- 🎯 Motivational message
- 🔁 Optionally prompts daily routine start

-----

<div align="center">

-----

**ORION X Command Reference** · 100+ Commands · 10+ Modules

*Built by Bhargav Gondaliya — AI/ML Engineer*

-----

</div>
