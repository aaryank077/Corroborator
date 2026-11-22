# Corroborate

A concept workspace for a newsroom's breaking-news desk. It turns a flood of posts, alerts and calls into a short list of claims, counts how many truly independent sources stand behind each one, and keeps the published story tied to that evidence.

Product design portfolio project: a working prototype, a case study, and the research behind it.

**Live:** [aaryank077.github.io/Corroborator/corroborate.html](https://aaryank077.github.io/Corroborator/corroborate.html)

## What's here

| File | What it is |
|---|---|
| [`corroborate.html`](corroborate.html) | The prototype and case study in one page. Open it in a browser; use the **Prototype** and **Case study** tabs. |
| [`research/haneda-reconstruction.md`](research/haneda-reconstruction.md) | A claim-by-claim reconstruction of how NHK, CNN and AP covered the 2024 Haneda runway collision, from archived pages. The case study's findings come from here. |

No build step and no dependencies. The page loads fonts from Google Fonts and otherwise runs offline.

## Try the prototype

- **C4, "One worker killed":** three reports, but one independent source. Log the county coroner as an official, on-the-record source and it becomes publishable.
- **C7, the smoke video:** marked false but still in the live story. Use **Correct** to fix it.
- **C11, three workers hospitalized:** the story already says two. Publish it and supersede the old line, or publish as-is and watch the number check flag both lines.

- **The long tail:** 150 claims. Filter to *Needs decision* or *Unassigned*, switch to compact rows, and select several to assign or dismiss in bulk.
- **Source map:** the tab above the claim. Channel 8's unnamed source sits behind both C4 and C12.
- **Demo state** (top right): switch to *Feed offline* or *Reporter view* to see those states.

Keyboard: `j`/`k` to move, `/` to search, `x` to select, `m` for the source map, `?` for the full list. Every action has Undo.

## Research changed the design

The Haneda reconstruction led to four changes in the prototype:

- a **Superseded** status
- a **number check** across the live story
- storing a source's **exact words**
- a **summary** in which each point keeps its source

The case study's "What the research changed" section walks through each one.

## Notes

The newsroom, plant, people and event in the prototype are fictional. Translations from Japanese in the research file were drafted with machine assistance and reviewed by the author.
