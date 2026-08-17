# Konstancja Tanjga

**Design engineer.** I build design systems as code — tokens, component APIs,
review gates, versioning, and the migration work that decides whether teams
actually adopt a new version.

Twelve years in product design, the last few spent moving from Figma into the
repository. I author and merge component pull requests across Angular, React
and web components, and I treat accessibility as a build gate rather than a
review comment.

Currently: enterprise ERP and AI-assisted analytics at Asseco. Previously
Volvo, Xecta, Deloitte.

---

### 🎩 [bighat-design-system](https://github.com/bighatpoland/bighat-design-system)

A small design system built to show the decisions, not the component count.

- **Two token layers** — primitives and semantics, with product code allowed to
  touch only the second. Dark theme is a swap of the semantic layer alone.
- **WCAG AA as a build error** — 58 contrast assertions across both themes,
  run in CI before the docs deploy. The gate knows a focus ring is non-text and
  needs 3:1, not 4.5:1.
- **`StateBlock`** — empty, loading and error as one component, each with a
  different announcement strategy. The screens nobody designs.
- **One breaking change**, argued for in `MIGRATION.md`, with a deprecation
  window and a scripted rename.
- **`agent/SKILL.md`** — the system's rules written so a coding agent follows
  them instead of inventing its own.

**[Storybook →](https://bighatpoland.github.io/bighat-design-system/)**

---

### Also here

Small React and TypeScript apps, mostly built to try an idea quickly. They are
prototypes rather than products, and they are labelled as such.

| | |
|---|---|
| [classic-countdown](https://github.com/bighatpoland/classic-countdown) | Desktop-first workday countdown with a configurable Mon–Fri schedule |
| [Docu-Manager](https://github.com/bighatpoland/Docu-Manager) | Single-page document management prototype — upload, classify, secure |
| [KindaSpanish](https://github.com/bighatpoland/KindaSpanish) | Spaced-repetition Spanish practice for adults who want to speak, not conjugate |
| [spam-detector](https://github.com/bighatpoland/spam-detector) | Paste text, find out whether it reads as spam |

