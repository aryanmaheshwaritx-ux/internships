# Internship Portfolio — Aryan Maheshwari

This folder is the standalone home for everything related to the **internship-focused portfolio**. It is separate from the college / professor outreach portfolio (`portfolio.html` in the parent folder), so do not get the two mixed up.

---

## What lives here

```
Internship_Portfolio/
├─ index.html                              ← the live site
├─ aryan_headshot_circle.png               ← headshot used in the hero
├─ Aryan_Maheshwari_Resume_Internship.pdf  ← downloadable resume
├─ Aryan_Maheshwari_Resume_Internship.docx ← editable resume source
├─ images/                                 ← project gallery photos
│   ├─ IMG_0898_thumb.jpg
│   ├─ IMG_3434_thumb.jpg
│   ├─ IMG_3450_thumb.jpg
│   ├─ ud_drone_render.jpg
│   └─ ud_cad_exploded.jpg
└─ README.md (this file)
```

## One-time setup before deploy

If any of the resume or images files are missing from this folder, drag them in from the parent `Aero Robotics` folder. The exact paths are listed above. Skip files that are already there.

## How to deploy as a separate GitHub Pages site

1. Go to [github.com/new](https://github.com/new) and sign in as `aryanmaheshwaritx-ux`.
2. Create a public repo named `internships` (or whatever you want — that name becomes part of the URL).
3. On the new repo page, click **Add file → Upload files**. Drag the entire contents of this `Internship_Portfolio` folder in (the `index.html`, the `images` subfolder, the headshot PNG, and the resume PDF/DOCX).
4. Commit message: `initial portfolio`. Click **Commit changes**.
5. In the repo, click **Settings → Pages**. Source: Deploy from a branch. Branch: `main`. Folder: `/ (root)`. Save.
6. Wait 30–60 seconds. Refresh the Pages settings page. URL appears at the top: `https://aryanmaheshwaritx-ux.github.io/internships/`.

## After it goes live

Open the URL in an incognito window and check three things:
- Headshot loads (no broken image icon)
- Download resume button actually downloads the PDF
- Project image gallery shows all photos

If anything is broken, it is almost always a filename mismatch — GitHub URLs are case-sensitive. `IMG_3434_thumb.jpg` is not the same as `img_3434_thumb.jpg`.

Then update your **resume header** to point to the new URL (`aryanmaheshwaritx-ux.github.io/internships`) instead of the old `/portfolio` link, otherwise recruiters who download your resume will land on the college portfolio.

## Editing the site later

Open `index.html` in any text editor. Common edits:
- **Add a project**: copy a `<article class="project reveal">` block inside `<section id="projects">` and edit the contents.
- **Update a number**: search for the spec value (e.g. `data-count="20"`) and change it.
- **Update text in hero**: search for `hero-desc` and edit the paragraph there.
- **Swap out a photo**: drop a new file into `images/` and update the `src=` path.

After editing, push the change to the same GitHub repo. The site updates within a minute.

## What this portfolio is not

This is the **internship portfolio**. Tuned for recruiters and hiring engineers — short, scannable, projects with specs.

The **college / professor outreach portfolio** lives in the parent folder as `portfolio.html`. That one is light theme, longer, and pitched at admissions readers and academic mentors.

If you ever want to update both, edit both. They are intentionally separate.
