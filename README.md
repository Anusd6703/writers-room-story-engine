# Writers Room Story Engine

A modular AI-ready story-development skill engine built on Pixar’s 22 Rules, Story Spine, Hero’s Journey, South Park causality, and character-arc design to improve foundations, scenes, and revision workflows.

## What it does

Writers Room Story Engine helps an agent build stronger stories by working in the right order.

Instead of jumping straight into prose, the system develops:
- premise
- story core
- protagonist engine
- Story Spine
- causal beats
- world pressure
- scenes
- revision

This package is designed for standalone fiction, short stories, scripts, narrative concepts, and story revision workflows.

## Why it exists

Many agents can write prose fast.
Few build stories well.

This package is designed to help an agent think like a story architect before it writes like a prose generator.
It gives the model a structured workflow for:
- finding the most compelling premise
- building a protagonist with pressure and contradiction
- keeping plot causal instead of episodic
- using worldbuilding in service of conflict
- drafting scenes that turn
- diagnosing and repairing weak drafts

## Package structure

```text
writers-room-story-engine/
├── README.md
├── AGENT-BOSS-INSTRUCTIONS.md
├── TEST-PROMPTS.md
├── PACKAGE-DESCRIPTION.md
├── SOURCES.md
├── CHANGELOG.md
├── CREATOR.md
├── MEGA-SKILL.md
├── prompts/
│   ├── system-prompt-writers-room-story-engine.md
│   └── workflow-order.md
└── story-suite/
    ├── designing-stories.md
    ├── creating-story-foundations.md
    ├── building-storyworlds.md
    ├── writing-story-scenes.md
    └── revising-stories.md
```

## Core workflow

1. Use `designing-stories.md` to orchestrate story development.
2. Use `creating-story-foundations.md` to build premise, story core, protagonist, ending direction, and Story Spine.
3. Use `building-storyworlds.md` when the world needs to create pressure, values, conflict, or consequence.
4. Use `writing-story-scenes.md` to turn story beats into strong scenes.
5. Use `revising-stories.md` to diagnose and repair what is weak.

If you want a single-file fallback, use `MEGA-SKILL.md`.

## Included frameworks and principles

This package draws from:
- Pixar’s 22 Rules of Story
- Story Spine
- Hero’s Journey analysis
- South Park’s “therefore / but” causality logic
- Star Wars-style character-arc design principles
- revision-first story diagnostics
- modular agent skill architecture

## Recommended use case

Use this package when you want an agent to:
- build a story from zero
- improve a weak story or outline
- design characters with stronger arcs
- avoid flat and-then plotting
- generate more compelling scene work
- separate ideation, structure, scene work, and revision into modular phases

## Testing

Use `TEST-PROMPTS.md` to test:
- generation from zero
- revision quality
- modular routing
- scene drafting quality
- story-world support quality

## Notes

This package is built to support both:
- modular orchestration across multiple focused skills
- simplified deployment through a one-file mega-skill
