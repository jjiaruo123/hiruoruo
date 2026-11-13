# hiruoruo

Beginner documentation for **Canva**, an online graphic design platform. This repository holds the project proposal, the document plan, and the planned guides that help new users start from a template, personalize a design, and export or share the finished piece.

---

## 1. Project Proposal

### 1.1 Product

- **Product:** Canva, an online design platform that lets users without design training create posters, social media graphics, presentations, resumes, invitations, and other visual materials from ready-made templates.
- **Documentation scope:** the beginner workflow from signing in to finishing and downloading or sharing one design. This project does not cover advanced features such as team collaboration, Brand Kit, paid Pro elements, or video animation.

### 1.2 Platform

| Component | Role in the workflow |
| --- | --- |
| Canva web app | Runs in a desktop browser at canva.com; the main place to browse templates and edit designs. |
| Canva desktop and mobile app | Optional companion apps for designing offline or on a phone; designs stay synced to the account. |
| Template library and editor | Thousands of ready-made templates; a drag-and-drop editor for text, images, shapes, colors, and fonts. |
| Download and share | Exports a finished design as PNG, JPG, or PDF, or shares it through a link. |
| Documentation host | All guides are written in Markdown and stored in this GitHub repository, where they are rendered directly in the browser. |

### 1.3 Reader

- **Primary reader:** university students and first-time users without design experience. They make visuals for coursework, club events, and social media posts.
- **Assumed knowledge:** basic web browsing and general computer operation. No experience with design software such as Photoshop is required.
- **Reader goals:** start a design from a template, personalize the text and visuals, and produce a finished design they can download or share.

### 1.4 Core Tasks

The documentation is built around the three tasks a new user must complete first.

1. **Sign in and start a design.** Create or sign in to a Canva account and start a new design from a suitable template.
2. **Edit text and elements.** Replace the placeholder text, upload or choose images, and adjust shapes, colors, and fonts in the editor.
3. **Download or share the design.** Export the finished design in the right file format, or copy a share link for others to view.

### 1.5 Problem and Purpose

Beginners often face a blank canvas and do not know where to begin, and they assume design tools require advanced skills. Canva's official help center is thorough but broad and scattered across many topics. This project produces a short, task-based beginner guide set that lets a new user complete the three tasks above independently. Every guide follows the course style guide: a clear starting point, verb-led steps, one term for one thing, conditions placed first, numbered steps for ordered actions, and a concrete result check.

---

## 2. Document Plan

### 2.1 Repository Structure

```
hiruoruo/
├── README.md                          # Project proposal, reader, tasks, plan, and tool choice (this file)
├── docs/
│   ├── quickstart.md                  # One-page quick start: sign in, pick a template, finish a first design
│   ├── how-to/
│   │   ├── start-a-design-from-template.md       # Task 1
│   │   ├── edit-text-and-elements.md              # Task 2
│   │   └── download-and-share-your-design.md       # Task 3
│   ├── reference.md                   # Glossary of terms and key interface elements
│   └── troubleshooting.md             # Common problems and fixes
└── practice/
    └── github-repository-guide.md     # Earlier GitHub tutorial, kept for practice
```

### 2.2 Document Inventory

| Document | Type | Reader goal | Status |
| --- | --- | --- | --- |
| `docs/quickstart.md` | Quick start | Finish a first design from a template in under ten minutes. | Planned |
| `docs/how-to/start-a-design-from-template.md` | How-to guide | Complete Task 1: sign in and start a design from a template. | Planned |
| `docs/how-to/edit-text-and-elements.md` | How-to guide | Complete Task 2: edit text, images, and elements. | Planned |
| `docs/how-to/download-and-share-your-design.md` | How-to guide | Complete Task 3: download or share the finished design. | Planned |
| `docs/reference.md` | Reference | Look up terms such as template, canvas, element, text box, and share link. | Planned |
| `docs/troubleshooting.md` | Troubleshooting | Fix common issues: template will not open, missing element, paid item, font display. | Planned |

### 2.3 Writing Order

1. Write the three how-to guides first, because they map directly to the core tasks.
2. Add the quick start as a condensed version of the first two tasks.
3. Complete the reference glossary and troubleshooting guide after the how-to guides are stable.

---

## 3. Tool Choice

I write the documentation in Markdown and store it in this GitHub repository. Markdown is plain text, so files are easy to version, compare, and review, and GitHub renders them directly in the browser without extra software. I edit the Markdown files in a plain text editor and use GitHub's built-in preview to check the formatting before each commit. This keeps the toolchain simple and keeps the practice materials and the project guides in the same repository.

---

## 4. Practice Materials

The earlier GitHub tutorial, which explains how to create a private repository with a README, is kept under `practice/` so that it stays separate from the new project documentation. See [`practice/github-repository-guide.md`](practice/github-repository-guide.md).
