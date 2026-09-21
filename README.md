
## 1. What It Is

Arithmetic Quiz is a fully local, offline mental-math quiz tool for elementary school students. Enter your name, pick an operation mode and a number range, work through a 20-question paper, and get it graded the moment you submit — complete with green checks, red Xs, and a teacher-style handwritten score. Every attempt is saved on your own computer so you can look back anytime.

Three things that define it:

- **Zero network, zero accounts.** No backend, no database, no internet requests of any kind. Everything works offline, and the name you type never leaves your device.
- **Instant grading feedback.** Correct answers get a green check; wrong or blank ones get a red X with the correct answer shown in red. Score = 5 points per correct answer, up to 100.
- **A local score book.** Each submission is automatically recorded — all 20 questions with correct answers, the score, and the time — keeping the most recent 50, clearable in one click.

## 2. Who It's For

| Audience | How they use it |
|----------|-----------------|
| Elementary school students (primary users) | Daily mental-math practice: choose a mode and range, take a 20-question paper, see results instantly, and earn a celebration for a perfect score |
| Parents and teachers | Set an appropriate mode and range for the child, and follow progress through grading results and the score history |
| Anyone practicing arithmetic | A quick 20-question self-test whenever you want one |

## 3. How It Works

1. **Enter your name** — required, up to 50 characters — and click "Start Quiz".
2. **Choose your difficulty.** Two dropdowns at the top right: 7 operation modes (Addition (+), Subtraction (−), Multiplication (×), Division (÷), Add & Subtract, Multiply & Divide, All Four Operations) and 3 number ranges (Within 10 / Within 100 / Within 1000). Defaults: Addition within 10.
3. **Answer 20 questions.** Each looks like `(3) 5+2=[____]` with the question number on a colored badge; answer boxes accept digits only, up to 7 digits.
4. **Submit.** Click "Submit" at the bottom right. If any questions are blank, a confirmation asks whether to keep answering or submit anyway.
5. **Automatic grading.** Correct answers earn a green ✓; wrong or unanswered ones get a red ✗ with the correct answer displayed in red beneath the question. Score = correct answers × 5, max 100 (the score area shows `--` before submitting).
6. **Perfect-score celebration.** A score of exactly 100 triggers the banner "Congratulations, {name}! Perfect score: 100!" with a confetti effect that runs about 3 seconds and never blocks the page.
7. **Review and retry.** Check your mistakes against the red answers, click "New Set" at the bottom right for a fresh paper, or dial the difficulty up. Every attempt lands in "History" automatically.

**Question guarantees (true for every paper):**

- Operands always fall inside the chosen range (boundaries included); zero never appears;
- Division questions always divide exactly (integer answers);
- Subtraction never goes negative;
- No duplicate questions within a paper;
- Mixed modes draw the operator at random for each question, so one paper trains multiple operations.

## 4. Interface Tour

A single-page app with four screens (no page navigation):

| Screen | Highlights |
|--------|-----------|
| Name entry | The default first screen: a centered card (welcome message, name box with a live character counter, "Start Quiz" button); language toggle at the top right |
| Quiz paper | The main screen, sized to 80% of your display width and height (resizes with the window). **Top left:** your name and the score (handwritten-style score number with two red pen strokes). **Top right:** operation and range dropdowns, "History", and the language toggle. **Center:** the 20-question grid with numbered badges. **Bottom left:** "About the Author". **Bottom right:** "Submit" (disabled after grading) and "New Set" (appears after grading) |
| About the Author | Opened from the bottom-left button: author photo (rounded 3:4 portrait), bio, motto, and WeChat ID as plain text; close via the × or the overlay — your paper is untouched |
| Score History | Opened from the top-bar "History" button: one record per row (record number, name, mode · range, score with correct count, submission time; the 20-question string scrolls horizontally), newest first, with a "Clear History" option |

The interface **switches between Chinese and English with one tap** (Chinese by default; toggles on the name-entry screen and the quiz top bar). Switching only re-renders text — it never interrupts your paper — and the preference is remembered on this device.

## 5. System Requirements

| Item | Requirement |
|------|-------------|
| Web edition | A modern desktop browser: Chrome or Edge (latest two major versions). Pure static files — just double-click to open, no installation |
| Windows desktop edition | Windows 10 (version 1809 / build 17763) or later. Five formats to choose from: NSIS trial installer and portable trial (2-hour full-feature trial with a remaining-time reminder every 20 minutes), NSIS permanent installer (2-hour trial + **unlock permanently with an activation code after paying ¥19.90 via WeChat QR**; up to 5 installs), MSIX package (permanent, no trial, no activation), and the Microsoft Store edition (2-hour full-feature trial, then unlock by purchasing in the Store; available once published) |
| Input | Keyboard and mouse (digits only in answer boxes) |
| Network | Not required — all features work fully offline |
| Disk usage | Minimal: static page files, plus (on the desktop edition) tiny local files for trial timing and install count |

## 6. Privacy and Contact

Zero network, zero collection: the app makes no network requests of any kind, and practice data (score history and language preference) stays on your device, clearable anytime. See the Privacy Policy (privacy-policy.md, in Chinese) for details.

- Developer: Fan Jiapeng — lives in Shanghai, works near Zhangjiang, and is a tech enthusiast. Motto: "The right path in life is shaped by vicissitudes."
- WeChat ID: fanjiapeng6022
