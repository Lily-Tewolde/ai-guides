# Desktop Organizer: A Universal Guide

Drop this file into a folder Claude can read, connect your Desktop in Cowork, and say: **"Read the Desktop Organizer file and organize my Desktop."**

Claude looks at what's actually on your Desktop, suggests a small set of top-level folders that fit *your* life, and files everything into them once you approve. After that, this file becomes the rulebook, so your Desktop stays organized instead of drifting back into chaos.

Each step is tagged:
- 🤖 **Auto**: Claude does this for you
- 🙋 **You decide**: Claude asks, you answer

> **Golden rule:** Move, never delete. Nothing leaves your computer and nothing gets renamed without your OK. Organizing is just putting things in the right place.

---

## How Claude should use this file

You (Claude) are organizing the user's Desktop. This file is your operating spec.

1. **First run:** do Steps 1 to 5 in order. Don't move a single file until the user has approved the map in Step 3.
2. **Every run after that:** read this whole file first, especially **My Folder Map** at the bottom. The map in this file outranks anything you remember.
3. **When the user changes their mind** about where something goes, update My Folder Map in the same session.

---

## Step 1: Look before you touch anything 🤖

Scan the whole Desktop, top level and a few layers down. Report back in plain language:

- How many top-level folders and how many loose files there are
- What kinds of things are there (school, work, receipts, photos, side projects, screenshots, installers)
- Obvious duplicates, and folders that are empty
- Anything that looks important and fragile: tax documents, IDs, contracts, code projects

**Two traps to check:**
- **iCloud-synced Desktop:** files can show up but not be downloaded yet. If a file won't open, download it first. Don't report it as broken.
- **An empty result usually means the wrong path**, not an empty folder. Double-check where you're looking before telling the user something is missing.

---

## Step 2: Ask how they live 🙋

Keep it short, one small group at a time:

1. What are the big areas of your life that make files? (Work, school, a side business, content, family, money, health, government stuff.)
2. Is there anything you want kept separate from everything else?
3. How do you like names: ALL CAPS folders, Title Case, or whatever's there now?
4. Do you have an external drive or cloud archive for old stuff?
5. Anything I should never move? (A folder an app depends on, a code project, something shared with someone else.)

---

## Step 3: Propose the top-level folders 🤖 then 🙋

Suggest **5 to 8 top-level folders** based on Steps 1 and 2. Fewer is better. Every folder should be a big area of life, not a single project.

**A starter set that works well (adjust to them):**

| Folder | What lives there |
|---|---|
| `CONTENT/` | Creative work: raw footage, edits, audio, graphics, scripts, reference guides |
| `GOVERNMENT/` | Taxes, benefits, licences, official letters |
| `CAREER/` | Resumes, job applications, interview prep, certificates, past roles |
| `MONEY/` | Bank statements, credit cards, budgets, financial planning |
| `PERSONAL/` | Medical, family, personal documents, a loose-ends `INBOX/` |
| `VENTURES/` | Businesses and side projects, one folder each, plus `_ARCHIVE/` for finished ones |

Swap out whatever doesn't fit. A student might need `SCHOOL/`, a parent might need `KIDS/`, someone with no side business drops `VENTURES/`.

Show the full proposed map, including where the current folders would move to, and **wait for a yes** before moving anything.

---

## Step 4: File everything 🤖

Once the map is approved:

- **Move, don't copy.** Copies are how duplicates happen.
- **Never overwrite.** If a file with the same name already exists at the destination, stop and ask.
- **Never rename** unless the user asks. Moving is enough.
- **Keep projects together.** A folder that belongs to one project moves as a whole, with everything inside it untouched.
- **Code projects and app folders don't get reorganized inside.** Move the whole folder if needed, but leave what's inside alone.
- **Don't delete anything.** If something looks like junk, put it in a `_TO_DELETE/` folder and tell the user. They empty it themselves.
- **Anything that doesn't clearly fit** stays loose and gets flagged. Don't invent a new top-level folder to hold it.

---

## Step 5: Leave a map behind 🤖

- Fill in **My Folder Map** at the bottom of this file.
- In any big folder with lots of subfolders (a business, a client, a big project), add a file called **`00 FOLDER MAP.md`** at its top. It says what each subfolder holds, in a line or two each. The `00` keeps it first in the list so it's the first thing you see when the folder opens.
- Report back: the final number of top-level folders, what moved where, what's in `_TO_DELETE/`, and what was flagged.

---

## The rules that keep it clean

- **Never create a new top-level folder.** New things nest inside an existing one. If something truly fits nowhere, leave it loose and flag it. Only the user adds a top-level folder.
- **Count the top-level folders at the end of every run** and report the number. If it went up, something broke the rule.
- **File Claude's outputs with the work they belong to.** A resume goes to `CAREER/`, a budget to `MONEY/`, a guide to `CONTENT/`. Never dump outputs on the Desktop root or in a generic "outputs" folder.
- **Match the naming already in the destination folder.** If a folder names files `Client - Thing - Sep 11`, new files follow that pattern.
- **Old versions go in `_superseded/`** inside the same folder, not a dated folder somewhere else.
- **Finished projects go to `_ARCHIVE/`**, and eventually to an external drive if the user has one.

---

## What NOT to do ❌

- Don't delete, rename, or overwrite anything without asking.
- Don't reorganize the inside of code projects or folders an app depends on.
- Don't create a new top-level folder to "solve" one odd file.
- Don't move big files into an iCloud-synced folder just to organize them; it can try to upload everything.

---

## Monthly 5-minute tidy 🤖

A quick recurring routine (easy to schedule in Cowork):

1. File anything loose on the Desktop root using My Folder Map
2. Empty the `PERSONAL/INBOX/` into the right homes
3. Move finished projects to `_ARCHIVE/`
4. Report the top-level folder count and anything flagged
5. Remind the user to empty `_TO_DELETE/` if it has anything in it

---

## My Folder Map

*(Filled in by Claude after Step 3. Edit anytime. This is the source of truth.)*

| Folder | What lives there |
|---|---|
| | |

**Never move:**
- 

**Naming style:**
- 

**Archive location:**
- 

---

*Built from a real Desktop cleanup: look first → ask → propose a few big folders → file everything → leave a map → never add a new top-level folder.*
