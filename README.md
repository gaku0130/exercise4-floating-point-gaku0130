# Exercise 4 — Vector Norms and Matrix Norms

Numerical Analysis 2026 / Lecture 4 assignment bundle.

This single repository contains **all four parts** (Ex 4.0 – 4.3) of Lecture 4.
Edit the `.qmd` files directly, run them locally, then `git push` to submit.

---

## Files

| File | Topic |
|---|---|
| `4th-handout.qmd` | **Ex 4.0** — your edited handout (>= 3 Q&A blocks) |
| `ex4-1.qmd` | Prove that the standard vector norms are norms |
| `ex4-2.qmd` | Verify norm inequalities numerically |
| `ex4-3.qmd` | Estimate induced matrix norms by random search |
| `requirements.txt` | Python packages used in the exercises |

For Ex 4.0, copy `4th-handout.qmd` from the
[`materials`](https://github.com/waseda-num-analysis-2026/materials/blob/main/040/4th-handout.qmd)
repo into the root of this repo, then add Q&A blocks following
[`AI_TUTOR.md`](https://github.com/waseda-num-analysis-2026/materials/blob/main/AI_TUTOR.md).

---

## Setup (one-time)

You may either reuse a virtual environment from a previous lecture or set
up a fresh one here.

### Option A — Virtual environment (recommended, safer)

```bash
# In this repository's root
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

> Do not forget to **select the `.venv` interpreter** in VS Code
> (`Cmd/Ctrl + Shift + P` -> *Python: Select Interpreter*) so that
> Quarto and the Jupyter kernel actually use it.

### Option B — System Python

```bash
pip3 install -r requirements.txt
```

---

## How to work

1. Open the `.qmd` file you want to work on in VS Code.
2. Edit the markdown answer slots and the code cells marked `TODO`.
3. Render to check your output:
   ```bash
   quarto render ex4-1.qmd
   quarto render ex4-2.qmd
   quarto render ex4-3.qmd
   ```
4. Submit by `git push`.

> AI use is allowed where stated, but you must verify and explain the
> results yourself. Verification is part of numerical analysis.

---

## Submission

```bash
git add 4th-handout.qmd ex4-1.qmd ex4-2.qmd ex4-3.qmd
git commit -m "Submit Ex 4"
git push
```

You may push as many times as you like before the deadline; the **last
commit before the deadline** will be graded.

**Deadline (JST):** **May 14 (Thu), 23:59** — all four parts (Ex 4.0–4.3).

---

## Ex 4.0 — Evolve the Handout with AI

**Goal.** While studying the Lecture 4 handout, insert **at least 3 Q&A
blocks** of your own — questions you actually had while reading,
answered with the help of GitHub Copilot (or another AI) following the
protocol in
[`AI_TUTOR.md`](https://github.com/waseda-num-analysis-2026/materials/blob/main/AI_TUTOR.md).

**Steps.**

1. Copy
   [`4th-handout.qmd`](https://github.com/waseda-num-analysis-2026/materials/blob/main/040/4th-handout.qmd)
   from the `materials` repo into the **root of this repo**.
2. Open it in VS Code and, for each question:
   - First prime the chat once with `AI_TUTOR.md`.
   - Highlight the line you do not understand.
   - Press `Cmd+L` / `Ctrl+L`, then ask the AI to add a Q&A block.
   - Verify the AI's answer, then accept the inserted Q&A block.
3. Repeat for **>= 3 distinct questions**, then commit and push.

Both Japanese and English questions are accepted — match the language of
your question.

---

## Need help?

- Mattermost: <https://class.s-top.dev/numerical-analysis-2026/channels/question>
- Materials repo: <https://github.com/waseda-num-analysis-2026/materials>
- Lecture 4 slides: <https://waseda-num-analysis-2026.github.io/materials/040/4th.html>
- Lecture 4 handout: <https://waseda-num-analysis-2026.github.io/materials/040/4th-handout.html>
