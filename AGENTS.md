# Mailroom — Agent Rules

Mailroom is a small Python tool for a newsletter. It counts subscribers, checks an issue
before it goes out, and sends it to a practice mail server.

## Project setup

- Python project managed with `uv`, Python 3.12 or newer.
- Never use a real person's email address. Use `@example.com` for sample/test data, and
  `@resend.dev` for practice sends.

## Course context

- Following the Agent Factory course, "Programming Fundamentals" chapter, sections 13
  through 13.7: https://agentfactory.panaversity.org/building-ai-workers/programming-fundamentals/overview/
- The learner already knows the material up to chapter 13.

## Teaching style (how Claude should work with the learner)

- Whenever something new comes up (a new concept, tool, or library), slow down: teach the
  concept first, then help the learner practice it. Don't just do it silently.
- Before explaining anything new, ask the learner to predict what will happen or what the
  answer is, before revealing it.
- Keep `notes/predictions.md` updated: append every prediction the learner makes, each one
  separated from the next by a line of three hyphens (`---`).
- Update zia-tutor-ai with the learner's progress as it's made.
