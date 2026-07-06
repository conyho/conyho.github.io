# How to Update Your Website — Quick Guide for Cony

Your website lives in this folder: `C:\Users\cony1\Dropbox\phd\website`

It's made of 3 simple pages:

| File | What's on it |
|---|---|
| `index.html` | Home: bio, positions, research interests, selected publications, awards, contact |
| `research.html` | All publications, papers under review, conference presentations, service |
| `teaching.html` | Courses and teaching awards |
| `assets/Cony-Ho-CV.pdf` | The downloadable CV |

## The easy way: ask Claude Code

Open this folder in Claude Code (like you did today) and just say what you want in plain English:

- *"My paper was accepted at Journal of Marketing — add it to my website and move it out of the R&R section."*
- *"I updated my CV — here's the new file: C:\...\CV_2027.pdf. Replace the one on the website."*
- *"Add a new course I taught: Consumer Behavior, Spring 2026, eval 1.2."*
- *"Change my email address to ..."*
- *"Publish the changes"* ← this pushes the update live to the internet.

Claude will edit the files and publish for you. **That's it.**

## Updating the CV PDF manually

1. Copy your new CV PDF into the `assets` folder.
2. Rename it to exactly: `Cony-Ho-CV.pdf` (replacing the old one).
3. Publish (see below).

## Publishing changes to the live site

The site is hosted for free on GitHub Pages. After any change, the update
must be "pushed" to GitHub. In Claude Code just say **"publish my website changes"**.

(Technical detail for reference: the site is a git repository pushed to
`github.com/<your-username>/<your-username>.github.io`, and GitHub Pages
serves it automatically within a minute or two of each push.)

## Rules of thumb

- Small text changes are safe — everything is plain HTML text.
- In `research.html` there are comments like `<!-- ✏️ TO ADD A NEW PUBLICATION ... -->`
  showing exactly where new entries go. Copy an existing block and edit it.
- Never worry about breaking things: every version is saved in git history and
  can be restored by asking Claude to "undo the last website change".
