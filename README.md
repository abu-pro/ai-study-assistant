# AI Study Assistant — by Sufyan

A free web app that turns your own notes into study material, automatically.

**Live demo:** https://abu-pro.github.io/ai-study-assistant/

## What it does
- **Quiz Maker** — paste your notes and the assistant picks the key word out of every sentence to build a fill-in-the-blank quiz, then checks your answers and shows your score.
- **Flashcards** — turns "Term: definition" lines from your notes into flip cards for quick revision.
- **Study Plan** — give it your subject, your topics and the days you have; it spreads the topics over your days and keeps the last day for revision and a self test.
- **Focus Timer** — 25-minute study rounds with 5-minute breaks (Pomodoro style).
- **Progress Tracker** — every quiz attempt is saved in your browser, showing your best score and your last five attempts, so you can watch yourself improve.

## How to try it
1. Open the live demo link above — no install, no sign-up.
2. Paste your own notes into the Quiz Maker and press **Make my quiz**.
3. Or download `index.html` from this repo and open it in any browser — it works offline too.

## How it works
One single `index.html` file — plain HTML, CSS and JavaScript. No server, no sign-up, no data leaves your browser. The quiz, flashcards, plan, timer and progress tracking all run locally in the page using simple JavaScript rules: the quiz picks the key word in each sentence, flashcards read "Term: definition" lines, and the plan spreads your topics across your days.

## Why I built it
Students write notes and then only re-read them, which is the weakest way to revise. Testing yourself works far better. This assistant turns any notes into a test in seconds.

Made by **Abu Sufyan** — BS Software Engineering student, Riphah International University, Sahiwal.
