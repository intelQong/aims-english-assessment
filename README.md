# AIMS English Proficiency Test

Interactive English proficiency test built for **AIMS English** to assess students who arrive for course information.

- **Developer:** Md Mahmudul Hoque Khan

## Purpose

When prospective students visit AIMS English seeking course information, they often don't know their own English level — and what level to enrol in. This tool solves that:

- **Quick self-assessment** — students take a short, IELTS-aligned test (Reading, Listening, Grammar, Writing) and get an instant band score with CEFR level.
- **Course guidance** — results give students an immediate sense of where they stand, helping them and our advisors pick the right course level.
- **Student profiling** — test results feed into student records, giving AIMS accurate baseline data for placing, tracking, and personalising each learner's journey.

## Features

- 4 IELTS-aligned sections: Reading, Listening, Grammar, Writing
- Partial test supported — students can take only the sections relevant to their goal
- Instant results: overall IELTS band + CEFR level (A2–C2) + per-skill breakdown
- Per-section timers with auto-advance
- Study recommendations based on weak areas
- No sign-up required — low friction for walk-in visitors
- Mobile-friendly, single-file static app

## Sections

| Section | Questions | Format | Time |
| --- | --- | --- | --- |
| Reading | 6 | B1–C1 passages, MCQ | 8 min |
| Listening | 5 | Transcript-based, MCQ | 6 min |
| Grammar | 6 | A2–C1, MCQ | 5 min |
| Writing | 1 | Essay 100–200 words | 10 min |

## Scoring

- MCQ sections: percentage correct mapped to a 3.0–8.0 band scale
- Writing: word-count heuristic band
- Overall = mean of section bands, rounded to nearest 0.5
- Band → CEFR mapping (A2/B1/B2/C1/C2)

## Student Profiling

The assessment is designed for use at the point of course enquiry. Advisor workflow:

1. Student arrives for course information.
2. Student completes the test on a stall/lobby device (approx. 25–30 minutes for the full test, or fewer for partial).
3. Student shares the result screen with the advisor.
4. Advisor logs the band score + CEFR level into the student profile.
5. Course placement and future progress tracking use this baseline.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Entire test app (HTML, CSS, JS) |
| `assets/aims-english-logo.svg` | Logo (primary) |
| `assets/aims-english-logo-v2.svg` | Logo (alternate) |
| `CNAME` | Custom domain mapping |
| `.github/workflows/jekyll-docker.yml` | GitHub Pages deploy workflow |

## Run locally

Open `index.html` in any modern browser. No build step or server required.

## Deployment

Hosted on GitHub Pages via the `CNAME` file.
