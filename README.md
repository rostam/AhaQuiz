# AhaQuiz

Exploring the **Aha Stack** (Astro + htmx + Alpine.js) by building a quiz app. This repo contains two sub-projects at different stages of development.

## Sub-projects

### `DefaultAstro/`
The minimal Astro + htmx starter — a simple counter with increment/decrement buttons served via Astro API routes. Used to verify the stack works before adding quiz logic.

### `QuizPulse/`
A quiz app built with Astro. Iterating toward bringing the [QuizPulse browser extension](https://github.com/rostam/quizpulse) vocabulary quiz into a web-native Astro app.

## Getting started

```bash
cd QuizPulse
npm install
npm run dev
```

Requires Node.js. The dev server starts at `http://localhost:4321`.

## Stack

| Tool | Role |
|------|------|
| [Astro](https://astro.build) | Framework + SSR |
| [htmx](https://htmx.org) | Partial page updates without a full SPA |

## Related

- [quizpulse](https://github.com/rostam/quizpulse) — the original browser extension this is based on
- [generate_questions_for_quiz](https://github.com/rostam/generate_questions_for_quiz) — tooling to generate the quiz question data
