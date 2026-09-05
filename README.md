# Your website — how to edit and publish

## Files
- `index.html` — Home (hero, experience, skills, education, honors, contact)
- `research.html` — Research page
- `projects.html` — Projects page
- `publications.html` — Publications page
- `styles.css` — All design/colors/fonts (you normally never touch this)

## How to publish on GitHub Pages
1. On GitHub, create a new repository named exactly: `jahidhasansagor-buet.github.io`
2. Upload ALL files in this folder (the HTML files and styles.css together)
3. Also upload your CV as `CV.pdf` (the "Download CV" button expects this filename)
4. Wait 1–2 minutes. Your site is live at: https://jahidhasansagor-buet.github.io

## How to edit
Open any .html file in a plain text editor (Notepad, VS Code) or edit directly
on GitHub (pencil icon). Change the text, save/commit, and the live site updates
in about a minute.

### Add a project
In `projects.html`, find any block that starts with `<!-- PROJECT START -->`
and ends with `<!-- PROJECT END -->`. Copy the whole block, paste it where you
want the new project, and edit the text inside. Delete a block to remove a project.

Template:

    <!-- PROJECT START -->
    <div class="project">
      <h3>Project title</h3>
      <div class="project-context">Where · Year</div>
      <p><strong>The problem:</strong> ...</p>
      <p><strong>What I did:</strong> ...</p>
      <p><strong>Result:</strong> ...</p>
      <p class="project-tools"><strong>Skills:</strong> skill 1, skill 2</p>
      <div class="project-links"><a href="LINK">Link text</a></div>
    </div>
    <!-- PROJECT END -->

(The problem / What I did / Result lines are optional — plain paragraphs work too.)

### Add a publication
In `publications.html`, copy a `<div class="pub">...</div>` block and edit it.
Use `class="pub highlight"` for your first-author papers (red accent line),
`class="pub"` for others. Add or remove the `pub-status` line for
"Under review" / "In preparation" tags.

### Things to update now
1. Replace `YOUR_SCHOLAR_ID` (in index.html and publications.html) with your
   real Google Scholar profile link.
2. Upload your CV as `CV.pdf` in the same folder.
3. When a paper gets published, move it up, remove the status line, and add
   its DOI link.

### Update the "Last updated" date
Each page has a footer line — change the month/year when you make edits.
