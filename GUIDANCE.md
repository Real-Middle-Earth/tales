# Guidance for New Tales

This repository is a *story shelf*: a place for short stories, folktales, songs, riddles, and other small compositions from Middle Earth.

The aim is simple: **well-told pieces** with **a strong mood**, **clear language**, and **one image** that captures the essence.

---

## 1) What to add

A contribution should be one of the following:
- A **short story** (long enough to be worthy of the name)
- A **folktale** (the sort that might be told by a fire and change a little with each telling)
- A **song, riddle, or verse**
- A **small roadside piece**: a scene, a memory, a rumour, a warning, a wonder

If the piece feels like a note or a throwaway sentence, it is better saved until it grows into something with shape.

---

## 2) Tone and craft

Keep the voice **timeless** and **readable**.

- Prefer **plain, vivid words** over modern slang.
- Give the reader **something to hold**: a concrete detail (weather, light, sound, texture, scent).
- Let each tale have a **beginning, a turn, and a finish** — even if it is short.
- Avoid explaining the moral too plainly; let the story do its work.

A good rule: if it reads well *out loud*, it is usually on the right path.

---

## 3) Length: “befitting its purpose”

There is no strict word count, but the piece must earn its label.

- **Short story:** not a paragraph; it should feel complete.
- **Folktale:** long enough to carry the listener through, with a clear shape.
- **Riddle/verse:** brief is fine — but it must still feel finished.

If in doubt, add one more strong scene or one more meaningful turn rather than padding.

---

## 4) File layout

- Create a new page under: `entries/`
- Use a simple, consistent name. Recommended:
  - `entries/YYYY-MM-DD.html` for date-stamped tales
  - or `entries/<slug>.html` for named tales (kebab-case)

If you introduce a new convention, keep it consistent and update the Story Shelf.

---

## 5) Every entry needs an essence image

Each entry **must** include a generated image that captures the mood.

- Put images in: `assets/images/`
- Keep images tasteful: **no readable text**, **no logos**, no modern signage.
- The image should be a **glimpse** — it should not explain everything.

### Suggested formats
- `.webp` (preferred)
- `.png` (acceptable)

---

## 6) “Back to the Story Shelf” icon

Every entry page should include a small **shelf/books icon** that links back to the Story Shelf page:

- Link target: `./` should not be assumed; use a relative link back to the shelf index: `../entries/`
- Place it near the top (so a reader is never lost).

If you copy the icon from an existing entry, keep it consistent.

---

## 7) Update the Story Shelf

When you add a new tale, also update:
- `entries/index.html`

Add the new tale to the list (newest first), with:
- title
- date (if applicable)
- a short, quiet one-line description (optional, but helpful)

---

## 8) A quick checklist before committing

- [ ] The new entry reads well (especially the first paragraph and the ending)
- [ ] The entry includes its essence image and the image loads correctly
- [ ] The shelf/books icon links back to the Story Shelf
- [ ] The Story Shelf lists the new entry and the link works
- [ ] Paths are relative (GitHub Pages serves this site under `/tales/`)

---

## 9) Notes on sources and borrowing

If you quote or closely adapt a known Tolkien passage, note the source plainly. Otherwise, keep it original.

---

## 10) When in doubt

Aim for one thing: **a tale worth rereading**.

Better one well-made story than three hurried scraps.
