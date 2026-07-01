# Anveshaka · अन्वेषक

**A research-matching platform for IIIT Hyderabad — built to fix how students and professors actually find each other.**

▶ [Open the live app](./index.html)

---

## Why this exists

Every semester, the same thing happens twice.

Students cold-email professors hoping to land a research slot, and most of those emails go nowhere — no visibility into whether they're even a fit. Meanwhile professors get buried under generic, copy-pasted applications with no way to tell who's genuinely interested versus who's mass-emailing the whole department. Nobody wins, and good matches get missed by accident.

Anveshaka is my attempt at fixing that with a few deliberate design choices instead of a generic "job board for research."

## The design choices that matter

**Transparent matching, not a black box.** Every project shows a real skill-overlap percentage, plus exactly which required skills you have and which you're missing. No mystery scoring.

**A comprehension gate before you can apply.** Before submitting, students have to read the project's linked paper and answer a short, auto-generated quiz about it. It's a small amount of friction that filters out "please consider my profile" applications and leaves professors with people who've actually engaged with the work.

**Reliability, not just skill.** Alongside skills, every student profile carries a commitment score and a reliability index — things like meeting attendance, task completion, and response time. It surfaces the thing that normally only shows up *after* a professor has already committed weeks to a student.

**Evidence over keywords.** Skills aren't just listed — each one is backed by something checkable: a GitHub repo, a course grade, a deployed project. A professor can verify a claim in seconds instead of taking it on faith.

**One ranked list instead of an inbox.** On the professor side, applicants are ranked by a single weighted score (skills, quiz, portfolio, commitment) instead of arriving as a pile of unsorted emails.

**Beyond 1:1 matching.** The platform also recommends whole *teams* with complementary skills for a project, and hosts subject-based societies — common rooms where curiosity keeps going even outside of a specific project.

## Try it

Open `index.html` (or the live GitHub Pages link above) and switch between the **student** and **professor** views from the top nav to see both sides:

- **Student** — discover projects with transparent match scores, check a project's skill gaps, clear the paper-checkpoint before applying, and see your own commitment/reliability scores.
- **Professor** — see your lab's supervision overview, browse ranked applicants, get suggested project teams, and post in your department's society.

## What's in this repo

- `index.html` — the full, self-contained web app (no build step, no dependencies — just open it in a browser)

## About

Ideated and designed by **Atharv Ojha**.
