# Web Engineering Lab — Course Resources

Easy-to-read notes, task sheets, and lab solutions for the Web Engineering lab course, organized week by week. Each week has two companion files: a plain-English study guide and a fully solved task sheet ready for e-learning submission.

## What's inside

| Week | Topic | Easy Notes | Task Sheet |
|---|---|---|---|
| 01 | How the Web Works — client/server, URLs, HTTP, DevTools, environment setup | [`week01_easynotes.html`](./week01_easynotes.html) | [`week01_tasksheet.html`](./week01_tasksheet.html) |
| 02 | HTML Deep Dive — semantic elements, forms, tables, id/class | [`week02_easynotes.html`](./week02_easynotes.html) | [`week02_tasksheet.html`](./week02_tasksheet.html) |
| 03+ | *Added as the course progresses* | — | — |

## File types

**`weekNN_easynotes.html`**
A self-contained study guide for that week's topic. Every concept is explained twice — a plain-English/layman example next to the formal technical definition — plus annotated code samples, reference tables, and a full glossary of every term used. No setup needed: open the file directly in any browser.

**`weekNN_tasksheet.html`**
Every warm-up, class activity, in-class lab, and homework task for that week, each with a model answer/solution. Tasks that need visual proof (Network tab captures, validator results, rendered pages) have a clearly marked screenshot slot — see below.

## Adding your own screenshots

Each task sheet's screenshot slots point at a `screenshots/` folder that sits **next to** the HTML file:

```
week01_tasksheet.html
week02_tasksheet.html
screenshots/
  activity-c-2xx.png
  activity-d-versions.png
  lab-network200.png
  ...
```

1. Create a folder named exactly `screenshots` alongside the task sheet files.
2. Save each screenshot using the filename printed directly above its box in the task sheet (e.g. `activity-d-form.png`).
3. Reload the page — the "not added yet" placeholder is replaced automatically once the file exists at that path.
4. To use different filenames, edit that box's `<img src="screenshots/...">` line directly.

A full walkthrough is also included at the bottom of every task sheet under **"How to Add Your Screenshots."**

## Viewing the files

No build step, server, or dependencies required — every file is plain, self-contained HTML/CSS.

- **Locally:** double-click any `.html` file to open it in your browser, or right-click → Open With → your browser of choice.
- **On the e-learning portal:** zip the task sheet, its matching `screenshots/` folder, and upload the zip (or upload the HTML file directly if the portal renders HTML inline).

## Naming convention

- `weekNN_easynotes.html` — study notes for week `NN` (zero-padded, e.g. `01`, `02`, `10`)
- `weekNN_tasksheet.html` — solved tasks + screenshot slots for week `NN`
- `screenshots/` — one shared folder per week's task sheet, filenames matched to each activity

## Course info

- **Course:** Web Engineering (Lab)
- **Institution:** Sukkur IBA University
- **Maintained by:** Imran Lateef Unar

---
*These notes are unofficial study aids prepared alongside the official course material — always confirm submission requirements against your instructor's actual instructions before uploading.*
