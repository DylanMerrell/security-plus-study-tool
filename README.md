# Security+ Study Tool

A single-page study app for CompTIA Security+ (SY0-701) built with plain HTML, CSS, and JavaScript. No frameworks, no build step, no backend.

**Live demo:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

## Features
- **Practice Test**: exam-style scenario questions plus generated term/definition questions, with explanations for every wrong answer (why your pick was wrong, why the correct one is right).
- **Select-all-that-apply** questions with proper multi-select grading.
- **Flashcards, Learn mode, and Match game** for memorizing terms.
- **Glossary** organized by chapter and subsection, with quick-contrast boxes for easily confused terms and a "quiz myself" mode that hides definitions.
- **Progress tracking**: missed questions and per-chapter accuracy are saved in the browser (localStorage) to show where to focus next.

## How it works
- All content lives in one JSON array (`window.__CHAPTERS__`) inside `index.html`: each chapter has terms (with subsections), questions, per-choice rationales, and contrasts.
- Learn, Match, and generated practice questions are built from that data at runtime.
- Progress is stored locally in the browser, so nothing is sent anywhere.

## Run locally
Open `index.html` in a browser.

## Note
This public build contains one sample chapter. Security+ and CompTIA are trademarks of CompTIA, Inc.; this project is not affiliated with or endorsed by CompTIA.
