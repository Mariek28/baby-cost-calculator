# Baby Cost File Location Report

Report date: May 21, 2026

## Files Found

The three known baby-cost HTML files were found in two locations: the old mixed folder and the safety backup of that folder.

### Old Mixed Folder

Folder:

`/Users/Annmarie/Documents/New project`

Files:

- `/Users/Annmarie/Documents/New project/first-year-baby-costs.html`
  - Title: `How Much Does a Baby Cost in the First Year? | Baby Cost Calculator`
  - H1: `How Much Does a Baby Cost in the First Year?`
- `/Users/Annmarie/Documents/New project/new-baby-budget-checklist.html`
  - Title: `New Baby Budget Checklist | Baby Cost Calculator`
  - H1: `New Baby Budget Checklist`
- `/Users/Annmarie/Documents/New project/diaper-and-formula-cost-guide.html`
  - Title: `Diaper and Formula Cost Guide | Baby Cost Calculator`
  - H1: `Diaper and Formula Cost Guide`

### Backup Folder

Folder:

`/Users/Annmarie/Desktop/CODEX/backups/New-project-before-cleanup`

Files:

- `/Users/Annmarie/Desktop/CODEX/backups/New-project-before-cleanup/first-year-baby-costs.html`
  - Title: `How Much Does a Baby Cost in the First Year? | Baby Cost Calculator`
  - H1: `How Much Does a Baby Cost in the First Year?`
- `/Users/Annmarie/Desktop/CODEX/backups/New-project-before-cleanup/new-baby-budget-checklist.html`
  - Title: `New Baby Budget Checklist | Baby Cost Calculator`
  - H1: `New Baby Budget Checklist`
- `/Users/Annmarie/Desktop/CODEX/backups/New-project-before-cleanup/diaper-and-formula-cost-guide.html`
  - Title: `Diaper and Formula Cost Guide | Baby Cost Calculator`
  - H1: `Diaper and Formula Cost Guide`

## Which Folder They Are Currently In

The active original copies are in:

`/Users/Annmarie/Documents/New project`

The backup copies are in:

`/Users/Annmarie/Desktop/CODEX/backups/New-project-before-cleanup`

## Do They Appear To Be The Real Baby-Cost Project?

Yes.

The three files appear to belong together as one baby-cost content project because:

- They share the same `Baby Cost Calculator` title branding.
- They cover related topics:
  - first-year baby costs
  - new baby budget checklist
  - diaper and formula costs
- They have matching standalone HTML page structure.

## Is There Already A Git Repo?

The folders containing these files are Git repos, but they are not baby-cost repos.

`/Users/Annmarie/Documents/New project`:

- Git repo: yes
- Remote: `https://github.com/Mariek28/would-you-rather-generator.git`
- This is the old mixed folder and should not be used for active baby-cost work.

`/Users/Annmarie/Desktop/CODEX/backups/New-project-before-cleanup`:

- Git repo: yes
- Remote: `https://github.com/Mariek28/would-you-rather-generator.git`
- This is a backup of the old mixed folder and should stay as a backup.

`/Users/Annmarie/Desktop/CODEX/04-FirstYearBabyCosts`:

- Git repo: no
- This is the intended clean destination folder.

## Supporting Project Files Found In The Containing Folders

Both containing folders include project files such as:

- `index.html`
- `sitemap.xml`
- `robots.txt`
- `README.md`
- `_redirects`
- `netlify.toml`
- `package.json`

However, those files belong to the mixed old folder state and should not automatically be moved with the baby-cost pages.

The baby-cost project should be separated carefully so it does not inherit unrelated Fun Question Generator or Little Decoders files.

## Should Files Be Copied Or Moved Into `04-FirstYearBabyCosts`?

Recommendation: copy first, do not move yet.

Reason:

- The old folder is mixed and risky.
- The backup should remain untouched.
- Copying the three baby-cost HTML files into `04-FirstYearBabyCosts` would create a clean starting point without disturbing the old folder or backup.

After copying, the clean baby-cost folder should be audited before creating a Git repo.

## Recommended Next Step

Copy these three files from `/Users/Annmarie/Documents/New project` into:

`/Users/Annmarie/Desktop/CODEX/04-FirstYearBabyCosts`

Files to copy later:

- `first-year-baby-costs.html`
- `new-baby-budget-checklist.html`
- `diaper-and-formula-cost-guide.html`

Then inspect the copied pages and decide:

- Which page should become `index.html`
- Whether a sitemap and robots file should be created
- Whether a README should be created
- Whether a new GitHub repo should be created
- Whether the site needs a domain or Netlify setup

## Current Completeness

The three files are enough to begin a small static baby-cost site, but the project is not complete yet.

Missing pieces likely needed before launch:

- `index.html` or a chosen homepage
- `sitemap.xml`
- `robots.txt`
- `README.md`
- `_redirects` if clean URLs are desired
- A new Git repo
- Netlify deployment setup
- Domain decision

## Safety Confirmation

- No files were moved.
- No files were copied.
- No files were deleted.
- No files were renamed.
- No files were edited.
- Nothing was staged.
- Nothing was committed.
- Nothing was pushed.
