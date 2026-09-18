# Marieta du Plessis — website

A minimal, static academic website: landing page, publications list, CV.
No build tools, no database — just HTML files and a stylesheet, hosted free
on GitHub Pages.

## What's in this folder

```
index.html              Landing page (who you are, photo, identifiers)
publications.html       Selected publications, grouped by research theme
cv/
  cv.pdf                Condensed 2-page CV (draft — please review)
assets/
  style.css             Shared styling
  photo.jpg             Placeholder — swap for your real headshot
llms.txt                Machine-readable summary of the site (for AI tools)
```

Your GitHub username is `Marieta-du-Plessis`, so once set up this site will
live at **https://marieta-du-plessis.github.io**.

## Step 1 — Create a GitHub account

1. Go to https://github.com/join and sign up (it's free) using the username
   `Marieta-du-Plessis` (or whatever you prefer — just update the GitHub
   link on the homepage and the repository name below to match).

## Step 2 — Create the repository

1. Once logged in, click the **+** in the top-right corner → **New repository**.
2. Name the repository exactly: `Marieta-du-Plessis.github.io` — this exact
   name is what turns on free hosting at that address.
3. Set it to **Public**.
4. Don't add a README, .gitignore, or license here (we already have files).
5. Click **Create repository**.

## Step 3 — Upload the files

1. On your new repository's page, click **uploading an existing file** (or
   **Add file → Upload files**).
2. Drag in all the files and folders from this project, keeping the same
   structure (`index.html`, `publications.html`, `llms.txt`, the `assets/`
   and `cv/` folders).
3. Scroll down, write a short commit message like "Initial site", and click
   **Commit changes**.

## Step 4 — Turn on GitHub Pages

1. In the repository, go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)`. Click **Save**.
4. Wait a minute or two, then visit https://marieta-du-plessis.github.io —
   your site is live.

## What's still needed from you

Everything is filled in except your photo — the upload didn't come through
this time (only the CV arrived), so `assets/photo.jpg` is a grey
placeholder. Send it again and I'll drop it straight in — square, at least
400×400px, works best.

Also worth a look before you publish:

- **cv/cv.pdf** — I condensed your full CV to two pages for the site (career
  summary, qualifications, registration, selected grants, supervision and
  teaching). I left out personal details that don't belong on a public CV
  (date of birth, marital status, equity profile, nationality). Please
  check it reads the way you want.
- **index.html** — the one-line tagline ("I study leadership, and what
  makes it responsible or corrosive") is my draft. Change it to whatever
  line you'd want people to repeat about your work.
- **publications.html** — I grouped a curated set of papers under four
  themes (Leadership; Academic Careers & Higher Education; Wellbeing,
  Engagement & Psychological Capital; Workplace Counselling & I-O
  Psychology Practice) with a link out to your full Google Scholar record.
  Swap in different papers per group if these aren't the ones you'd lead
  with.

## Keeping it current

- When you publish something new, add one `<li>` block to the right theme
  in `publications.html` (copy an existing one and edit it) and update
  `llms.txt` if it changes the summary.
- Update the "Last updated" line on the homepage whenever you touch the
  site — a visible date is what keeps a site from reading as neglected.
- Every change goes through the same **Add file → Upload files** flow in
  Step 3 (GitHub keeps history automatically, so overwriting a file is safe).

## Why this design

- **Two clicks to anything**: home → publications/CV/contact, no deeper
  navigation needed.
- **Portable**: plain HTML/CSS, no framework, no lock-in — it'll still work
  in ten years and can be moved to any host by copying files.
- **Machine-readable**: `llms.txt` and DOI links on every publication mean
  both search engines and AI tools can find and cite your work directly.
- **Nothing to break**: no server, no database, no dependencies to update.

## About the more advanced site you shared (johanfourie.com)

That site adds several things beyond the essentials: a "why I do this"
narrative built around a book and a public blog, a dedicated Teaching page,
and a Public/media page with a large subscriber-driven blog feed. All of
that is genuinely more upkeep — new posts, more pages to keep current — so
it's a good next phase once the essentials site is running and you know
you'll keep it fed, not a starting point. When you're ready, the natural
additions in order would be: (1) the one-paragraph narrative on the
homepage, (2) a Teaching page, (3) a simple public-writing/blog page linking
out to your LinkedIn posts or op-eds rather than a full blogging platform.
