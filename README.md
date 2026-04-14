<p align="center">
  <img src="icon-192.png" alt="Elementa Builder" width="96" height="96">
</p>

<h1 align="center">Elementa Builder</h1>

<p align="center">
  A free, offline-first legal complaint builder — structured drafting without the Word formatting hell.
</p>

<p align="center">
  <a href="./elementa-builder.html"><strong>→ Launch the App</strong></a>
</p>

---

## Why Elementa Builder exists

Legal drafting has a structure problem. A complaint isn't just paragraphs — it's facts mapped to elements, elements assembled into counts, and counts forming a coherent pleading. But most people draft in Word, which fights you the entire way: renumbering paragraphs by hand, losing track of which facts support which claims, formatting that breaks when you move things around.

Elementa Builder was created to solve that. It keeps the structure explicit so you can focus on the substance.

The name comes from the Latin *elementa* — the basic principles, the first parts, the essential components. That is exactly the method: identify the required elements of each claim, connect your facts to those elements, and let the document build itself around that structure.

---

## What it does

- **Caption builder** — fill in court, district, county, case number, and parties; the caption formats itself
- **Sections with numbered paragraphs** — add sections, headings, and paragraphs; numbering runs globally and automatically across the entire document
- **Exclude without deleting** — hide any paragraph from export while keeping it in your workspace
- **Causes of action / Counts** — define the legal elements of each count and map specific numbered paragraphs to each element
- **Fact mapping** — see exactly which paragraphs support which elements; unmapped facts are flagged
- **Drag to reorder** — reorder sections, paragraphs, counts, and element paragraphs by dragging
- **Live preview** — rendered document view before you export
- **Export to Markdown** — clean `.md` output with proper heading hierarchy and paragraph numbering
- **Save / load** — saves to a `.complaint` file (JSON-based custom format) that you own and can version control

---

## How to use it

**Option 1 — Use it in your browser (no install needed)**

[Launch Elementa Builder →](./elementa-builder.html)

**Option 2 — Install it as an app (PWA)**

Visit the link above in Chrome or Edge, look for the install icon (⊕) in the address bar, and click **Install**. It opens in its own window with no browser chrome, like a native app.

**Option 3 — Download and run locally**

1. Download `elementa-builder.html`, `manifest.json`, `icon-192.png`, and `icon-512.png`
2. Drop them in a folder
3. Open `elementa-builder.html` in any browser
4. Works fully offline — no server, no account, no internet required

---

## Building a complaint: the workflow

```
1. Caption      →  fill in court info and parties
2. Sections     →  add your facts as numbered paragraphs
3. Counts       →  add each cause of action
4. Elements     →  define the required elements for each count
5. Map facts    →  connect numbered paragraphs to elements
6. Preview      →  review the full rendered document
7. Export MD    →  download your complaint as Markdown
```

---

## Why it's built this way

Elementa Builder is a single HTML file — no framework, no backend, no database, no account. Your data lives in a `.complaint` file on your own machine. The app runs entirely in your browser.

This was a deliberate choice. Legal documents are sensitive. The tool should work offline, be portable, and give you full ownership of your files. It also means you can host it yourself, fork it, or just keep a copy locally.

---

## Background

This tool was built as a companion to the [Jurisdictionary course](https://jurisdictionary.com) — a practical course on how to litigate your own case. Jurisdictionary teaches the method; Elementa Builder is the drafting environment that puts that method into practice.

If you're interested in understanding how the legal system actually works and how to navigate it as a pro se litigant, the course is worth a look. It's already paid for itself.

---

## File structure

```
Elementa-Builder/
├── elementa-builder.html    ← the full application
├── manifest.json            ← PWA manifest
├── icon-192.png             ← app icon (192×192)
├── icon-512.png             ← app icon (512×512)
└── README.md                ← this file
```

---

## License

MIT — free to use, fork, and build on. Attribution appreciated but not required.

---

<p align="center">
  Built by <a href="https://github.com/aku762">aku762</a>
</p>
