# What a Lesson Looks Like

A v4 lesson keeps the same editorial, warm, code-forward look as v2/v3 — clean and
Karpathy-minimal, calm to read, nothing gratuitous — because four of the six pipeline
steps in [TEACHING-STYLE.md](TEACHING-STYLE.md) (build-from-scratch, predict-before-reveal,
one-change-fix, compress-to-plain-language) are exactly what that look was built to keep
visible. It adds exactly one new component: a callout for the moment a concept is seen
from a second angle.

## Palette

| Role | Hex |
|------|-----|
| Paper background | `#fbfaf7` |
| Ink (body) | `#16191d` |
| Muted (labels, captions, angle note) | `#5b6470` |
| Orange accent | `#b4531f` |
| Failure marker | `#a8443a` |
| Working marker | `#5e7d4f` |
| Code block bg / ink | `#1d2127` / `#e6e1d6` |
| Hairlines | `#e7e3da` |

## Typography

- **Body:** serif (Iowan Old Style / Palatino / Georgia), ~18px, line-height 1.7.
- **Headline, eyebrow, section labels, captions:** sans-serif (Inter / system UI).
- **Code & numeric output:** monospace (SF Mono / Menlo / Consolas).

## Components

- **Eyebrow** — small uppercase orange kicker (lesson number · topic).
- **Headline + lede** — large Inter title, one calm serif lede line under it.
- **Section labels** — short uppercase muted Inter headings.
- **Code blocks** — dark, rounded, soft-shadowed; the *one line that changed* gets a
  faint orange highlight.
- **Result block** — the real output under the code, plainly: a small "Result" tag, the
  actual numbers in monospace, and a one-line italic verdict. A quiet left-border marks
  failure (`#a8443a`) vs working (`#5e7d4f`).
- **Figure** — a real plot, centered, thin border, sans caption, built from values
  produced by running the lesson's actual code — never hand-drawn to illustrate the
  shape of the idea.
- **Angle note** — a single boxed aside, left-bordered in muted gray (`#5b6470`), no
  background tint, placed inline right where the concept is re-seen from a second angle
  (geometric vs. algebraic, code vs. diagram). It appears once per lesson, not as a
  permanent column — because the second angle is one specific moment, not a running
  commentary. Kept deliberately quieter than the pull-line below, so the two never
  compete for the reader's eye.
- **Pull-line** — one orange-bordered sentence carrying the lesson's single insight.
- **Rebuild card** — a soft white card at the end with the blank-page question.

## What must stay on the page (the struggle)

The look exists to show how the lesson *actually happened*, so these are required:

- **The prediction** — the learner's guess before the reveal, struck through if wrong.
  The wrong guess is the most valuable thing on the page.
- **The failure** — the dumb first version and the exact way it broke, kept visible.
- **The one-change fix** — the single thing that changed and the result it produced.
- **The second angle** — at least one angle note showing the same concept from a
  different view before the formula is allowed to stand alone.
- **The rebuild card** — the blank-page question that sends the learner to try it.

A lesson that shows only the polished final answer has hidden the teaching. That is the
one thing this style must never do.

## No noise

No emoji or icon ornaments · no decorative imagery that isn't a real figure · no third
accent colour beyond the palette above (the angle note reuses the existing muted gray,
it does not introduce a new one) · no boxes added just to look "finished." The finished
look is the calm one. Keep the page quiet enough that the code, the result, and the one
angle note are what catch the eye.
