# HighRadius Consulting Intern — Mock Test Portal

A premium, interactive, and high-fidelity mock test portal designed specifically to help candidates prepare for the **HighRadius Consulting Intern** placement exam. 

Live Demo: **[https://varadrz.github.io/Highradius-Consultancy-Mock/](https://varadrz.github.io/Highradius-Consultancy-Mock/)**

---

## 🚀 Key Features

### 🎨 1. Premium Visual Experience
- **Adaptive Themes**: Beautifully-tuned dark mode (default) and light mode theme switcher.
- **Modern Design**: Clean typography (Plus Jakarta Sans & JetBrains Mono), glassmorphic card layouts, smooth transitions, and glowing visual cues.
- **Section Color-Coding**: Dynamic badge themes for the 5 subjects (SQL, Quant, Verbal, Reading Comp, Pattern) to improve readability.

### ⏱️ 2. Production-Grade Exam Console
- **Section Navigation**: Jump to any of the 5 key sections instantly with visual indicator badges showing section-wise completion.
- **Question Matrix Grid**: A full bird's-eye navigator grid of all 70 questions. Clicking a number jumps to that question. Color-coded markers show answered (green/red based on correctness) and bookmarked questions.
- **Pulsing Timer**: Auto-ticking 120-minute countdown timer with warnings at 30 minutes (amber) and 10 minutes (pulsing red).
- **Auto-Save / Resume Session**: Session answers, bookmarks, visited questions, and remaining time are synchronized automatically with `localStorage` so a browser refresh or close won't lose your work.

### ⌨️ 3. Expert Keyboard Shortcuts
Take the test like a power user without lifting your hands from the keyboard:
- <kbd>A</kbd>, <kbd>B</kbd>, <kbd>C</kbd>, <kbd>D</kbd> — Select answer choices.
- <kbd>←</kbd> / <kbd>→</kbd> — Navigate to the previous/next question.
- <kbd>F</kbd> — Toggle Bookmark/Flag status on the active question.

### 📊 4. Analytical Diagnostics Dashboard
Upon submitting the exam, review a comprehensive performance analysis page:
- **Circular Gauge Score**: Beautifully animated SVG ring tracking your accuracy percentage alongside correct-to-total fractions.
- **Grade Badges**: Custom graded feedback (A+, A, B, C) matching competitive cutoffs (70%+ recommended target).
- **Subject Domain Breakdown**: Horizontal progress bars evaluating your performance in each distinct section.
- **Review Explorer**: Detailed question review filterable by state (All, Correct, Wrong, Skipped, Bookmarked) and searchable by concept keywords.
- **Explanatory Insight**: Code copy-to-clipboard blocks and instant conceptual explanations unlocked for every question.

---

## 📚 Exam Structure

Proportional coverage representing the competitive placement curriculum:
- **SQL** (30 Questions, 43% of total score) — JOINs, Aggregates, NULLs, HAVING vs WHERE, Window functions, CTEs.
- **Quantitative Aptitude** (10 Questions) — Percentages, Averages, Time & Work, Speed & Distance, Probability, P&C.
- **Verbal Ability** (10 Questions) — Subject-verb agreement, idioms, synonyms, para-jumbles.
- **Reading Comprehension** (10 Questions) — Passages assessing fact extraction, tone analysis, and logical conclusions.
- **Pattern Matching** (10 Questions) — Numerical/Alphabetical series, analogies, matrix rules, mirror images, input-output logic.

---

## 🛠️ Local Execution

1. Clone this repository:
   ```bash
   git clone https://github.com/varadrz/Highradius-Consultancy-Mock.git
   ```
2. Open the `index.html` file in any modern browser (Chrome, Firefox, Safari, Edge):
   - You can double-click the file in your explorer or run a local server (e.g. Live Server extension in VS Code).

---

## 🌐 Deploying to GitHub Pages

To make the site live:
1. Go to your repository on GitHub: **`https://github.com/varadrz/Highradius-Consultancy-Mock`**
2. Click on the **Settings** tab.
3. On the left sidebar, click on **Pages** (under the "Code and automation" section).
4. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: Select **`main`** and folder **`/ (root)`**
5. Click **Save**.
6. After 1-2 minutes, GitHub will publish your site to:
   **`https://varadrz.github.io/Highradius-Consultancy-Mock/`**
