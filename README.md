# Hi, I'm Brian Chase

**AI solutions architect.** I design the plumbing that lets AI agents do real work: capturing how
people actually do a task, turning it into something a model can read, and putting human review
around everything the model does.

## What I work on

- **Human-to-agent handoff:** turning demonstrated work into structured, replayable task specs
- **Agent tooling and MCP:** giving models safe, scoped access to the context they need
- **Human-in-the-loop systems:** audit trails, review checkpoints, and feedback that improves the next run
- **Local-first, privacy-first AI:** redaction, exclusion and data boundaries built in, not bolted on

## Featured project

### [TaskTrace](https://github.com/BrianChase515/tasktrace)
A Mac menu-bar app that turns a task you do once into one compact file any AI can read and act on.

- **Records what you meant, not just where you clicked:** the button or field by name (including inside
  Chrome and Electron apps), the text on screen, what each click caused, which values change between
  runs, and your own notes on *why*.
- **AI writes the plan, you stay in charge:** any assistant, even a locked-down corporate one, writes a
  plan as text. TaskTrace runs it step by step while you approve, pauses to ask when the plan isn't sure,
  and stops the moment you say so.
- **Every run is audited:** who wrote the plan, what was found, what happened, and your corrections,
  triaged back to the AI for the next version.
- **Private by design:** local-only, password fields and password managers never recorded, secrets redacted.
- **Ships like a real app:** one-click download, guided permissions, signed in-app updates, and a build
  that clicks through its own dialogs on a real Mac before every release.

`Python` · `macOS Accessibility` · `PyObjC` · `MCP` · `on-device OCR` · `GitHub Actions`

[Download for Mac](https://github.com/BrianChase515/tasktrace/releases/download/latest/TaskTrace.dmg)

## How I build

I keep probabilistic generation separate from deterministic control wherever reliability matters:

- Explicit data and evidence boundaries
- Structured validation, with failures that stop instead of guess
- Human review checkpoints and auditable decisions
- Reproducible demos on synthetic data
- Clear lines between evidence, inference, and assumption

## Portfolio safety

Public repositories here use fictional organizations, synthetic data and clean-room implementations.
They contain no employer, customer or confidential information.

## Support my work

If my projects save you time, you can buy me food and a beer:

[![Donate with PayPal](https://img.shields.io/badge/Donate-PayPal-00457C?logo=paypal&logoColor=white)](https://www.paypal.com/donate/?business=R3PWW7XAVVP2Y&no_recurring=0&item_name=Help+me+buy+food+and+beer.&currency_code=USD)

## Open to

Senior and lead roles in AI solutions architecture, applied AI, and agent platforms.
