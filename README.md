# Little Days — A Digital Photo Journal

A UX portfolio project for gathering photos, screenshots, voice notes, and personal notes into a journal you can return to.

The current direction replaces the original Museum of You concept with an open-book photo journal, inspired by a user-provided visual reference. The GitHub repository and hosted app address retain their original names.

## Working app

The browser-based app lives in `app/dist/`. Features include:

- Layered journal spreads with photo collages, paper textures, and handwritten details.
- Browsing entries, an entry index, and animated page navigation.
- Creating and editing entries, image and audio uploads, optional captions and notes, ordering, and deletion.
- Persistent browser storage using IndexedDB. Existing museum collections are displayed as journal entries without deleting their data.
- A responsive layout and support for reduced-motion preferences.

Entries and uploaded files stay in the current browser. There is no cross-device sync, cloud backup, or sharing.

Run locally with `python3 -m http.server 4173 --directory app/dist`, then visit `http://localhost:4173`.

[Open the private hosted app](https://museum-of-you-sumairah.copper-duck-3024.chatgpt.site).

## Design status

Concept and prototype development. No user research has been conducted. Sample entries use fictional notes and landscape photos from Unsplash; they are not user research or personal memories.

[Original project brief](PROJECT-BRIEF.md) and [original first-use flow](FIRST-USE-FLOW.md) document the earlier museum direction. The current journal direction supersedes their museum-specific interface decisions.

## Sample image credits

Landscape photography is supplied through Unsplash image endpoints and stored in `app/dist/assets/`: [lake](https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1), [forest](https://images.unsplash.com/photo-1441974231531-c6227db76b6e), and [mountains](https://images.unsplash.com/photo-1464822759023-fed622ff2c3b).
