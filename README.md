# Museum of You

A UX portfolio project exploring a personal digital museum: a place to gather meaningful photos, screenshots, recordings, and images of keepsakes into small exhibitions about chapters of life.

## Project status

Early concept development. User research and visual design have not started. The audience and problem statements are hypotheses, not research findings.

## Core experience

Name a chapter → add three objects → optionally add notes → preview → save privately → revisit.

Exhibitions persist. Notes are optional captions attached to objects, not temporary social-media Stories. Incomplete exhibitions can be saved as drafts.

## Project documents

- [Project brief](PROJECT-BRIEF.md): purpose, working audience, scope, assumptions, and open questions.
- [First-use flow](FIRST-USE-FLOW.md): proposed screens, interactions, and prototype evaluation tasks.

## Next step

Develop low-fidelity wireframes and evaluate the create-and-return journey. Record actual observations separately from assumptions.

All sample exhibition content is fictional. No interview findings or measured outcomes are claimed.

## Working app

The first browser-based version lives in `app/dist/`. It supports exhibition creation, image and audio uploads, optional object notes, ordering, editing, and revisiting. IndexedDB stores exhibitions and files on the current browser; there is no cross-device sync or cloud backup.

Run locally with `python3 -m http.server 4173 --directory app/dist`, then visit `http://localhost:4173`.

Private hosted app: https://museum-of-you-sumairah.copper-duck-3024.chatgpt.site

Browser QA verified draft creation, saving, persistence after reload, and reopening. Upload and audio playback require further testing with representative files.
