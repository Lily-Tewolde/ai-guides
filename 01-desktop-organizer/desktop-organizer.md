# Desktop Organizer: A Universal Guide

Drop this file into a folder Claude can read, connect your Desktop in Cowork, and say: **"Read the Desktop Organizer file and organize my Desktop."**

Connect your Downloads folder too. It's in scope by default, and it's usually the bigger mess.

Claude looks at what's actually on your Desktop, suggests a small set of top-level folders that fit *your* life, and files everything into them once you approve. After that, this file becomes the rulebook, so your Desktop stays organized instead of drifting back into chaos.

Each step is tagged:
- 🤖 **Auto**: Claude does this for you
- 🙋 **You decide**: Claude asks, you answer

> **Golden rule:** Move, never delete. Nothing leaves your computer and nothing gets renamed without your OK. Organizing is just putting things in the right place.

---

## How Claude should use this file

You (Claude) are organizing the user's Desktop. This file is your operating spec.

1. **First run:** do Steps 1 to 7 in order. Don't move a single file until the user has approved the map in Step 3.
2. **Every run after that:** read this whole file first, especially **My Folder Map** at the bottom. The map in this file outranks anything you remember.
3. **When the user changes their mind** about where something goes, update My Folder Map in the same session.
4. **The Desktop and Downloads are both in scope** unless the user says otherwise. Everything in this file applies to both.

---

## Step 1: Look before you touch anything 🤖

Scan the whole Desktop and Downloads, top level and a few layers down. Report back in plain language:

- How many top-level folders and how many loose files there are
- The total number of files and their total size, in each place and combined. Write these down. You'll need the combined numbers in Step 6 to prove nothing was lost.
- What kinds of things are there (school, work, receipts, photos, side projects, screenshots, installers)
- Obvious duplicates, and folders that are empty
- **Exact duplicates,** checked by checksum, not by name. A matching name doesn't mean a matching file.
- **Old versions of one document,** like five copies of the same resume
- **Easy junk:** installers for apps that are already installed, and zip files that are already unzipped right next to their folder. If you can't tell whether an app is installed, ask in Step 2.
- Anything that looks important and fragile: tax documents, IDs, contracts, code projects

**Sensitive things get their own group in the report:**
- **Other people's personal details:** someone else's resume, a client's invoice, a form with a friend's address on it
- **Files with passwords in them:** a notes file, a handover document, a list of logins
- **Screenshots of ID or payment pages:** a photo of a licence, a checkout page with card details

**Look inside, not just at the name.** Open the file whenever the name is generic or coded, or the file looks important. Read the first page of PDFs and Office files. If a page is a scan with no text, render it as an image and look at it. Use the file's date only as a tiebreaker.

| Filename | What it actually was |
|---|---|
| `Party Checklist.pdf` | a lease agreement |
| `scan_0042.pdf` | a tax slip |
| `Resume (2).pdf` | someone else's resume |
| `final.pdf` | a signed job offer |

*(Made-up examples. Yours will be different, but this happens a lot.)*

**Three traps to check:**
- **iCloud-synced Desktop:** files can show up but not be downloaded yet. If a file won't open, download it first. Don't report it as broken.
- **An empty result usually means the wrong path**, not an empty folder. Double-check where you're looking before telling the user something is missing.
- **An app icon on the Desktop is often a mounted installer disk**, not a file. It needs ejecting, not filing.

---

## Step 2: Ask how they live 🙋

Keep it short, one small group at a time:

1. What are the big areas of your life that make files? (Work, school, a side business, content, family, money, health, government stuff.)
2. Is there anything you want kept separate from everything else?
3. How do you like names: ALL CAPS folders, Title Case, or whatever's there now?
4. Do you have an external drive or cloud archive for old stuff?
5. Anything I should never move? (A folder an app depends on, a code project, something shared with someone else.)
6. Which areas are you done with? (A school you finished, a job you left, a project that's over.) Their files can go to `_ARCHIVE/` to keep, or to `_TO_DELETE/` for you to check.
7. What should happen to other people's documents? (Keep them in one folder, give them back, or put them in `_TO_DELETE/`.)
8. Do you want your files renamed to one standard pattern? (See Step 5. The default is no.)
9. Should Downloads end up empty, or are there files you keep there on purpose? (The default is empty.)

**Answers can change partway through.** If the user says "actually, the old school stuff can go," update the plan, say what changed, and keep going.

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

- **Include what's going to `_TO_DELETE/` and why,** so nothing in there is a surprise.
- **Include one folder for images,** like `PERSONAL/Images to sort/`. See Step 4.
- **Say where ID documents live,** like `GOVERNMENT/ID/`. ID photos end up there too, once the Image Organizer sorts the images.
- **Say where private files go,** like `PERSONAL/Private/`. That's where files with passwords in them go, so none are left loose on the Desktop. Private images, like a payment screenshot, still go to the images folder. Name each one in your report.

**Warn them about the permission prompt before you start.** Moving files out of Downloads brings up a deletion permission prompt in Cowork. That's because a move between folders is a copy, then removing the original. Nothing gets thrown away. Tell them first, so they don't say no to it by mistake.

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
- **Exact duplicates go to `_TO_DELETE/Duplicates/`.** Only when the checksums match. Keep the copy with the cleanest name in its proper home.
- **Older versions go to `_superseded/`** inside the same folder. Give each one a dated name, like `Resume - 2025-03.pdf`, so the versions are easy to tell apart. That's a rename, so if they said no to renaming, ask first.
- **Installers for apps that are already installed go to `_TO_DELETE/Installers/`.** These are the `.dmg`, `.pkg` and `.exe` files left over after setup.
- **Zips that are already unzipped go to `_TO_DELETE/`.** If the unzipped folder is sitting right next to the zip, the zip is a spare copy.
- **Remind them to eject mounted installer disks.** Apps open from the Applications folder or Launchpad, not from the Desktop.
- **Areas they're done with and other people's documents** go where they said in Step 2.
- **Files with passwords in them go to the private folder** in the map. Flag each one by name.
- **Images go to one folder** for the [Image Organizer](../03-image-organizer/image-organizer.md). Don't sort or rename them here. The Image Organizer does both. Both guides share **My Folder Map**, so an ID photo ends up with the rest of the ID documents instead of in a second ID folder.
- **Empty leftover folders go to `_TO_DELETE/`.** You don't delete, so an emptied folder would otherwise sit there forever.

---

## Step 5: Rename, only if they asked 🤖

Skip this step unless the user said yes to renaming in Step 2.

**The pattern:** `Type - Detail - Date`

- **Date as exact as the document allows:** `2025`, `2025-08` or `2025-08-25`.
- **Versions of the same thing** get `v2`, `v3`.
- **Check what the file is first** (Step 1). Never rename from the old filename alone.
- **Don't rename files with passwords in them,** or anything on the Never move list.
- **If a folder already has its own pattern,** match that instead.

**Made-up examples:**
- `Lease - Apartment - 2024-09-01.pdf`
- `Tax Slip - Bakery Job - 2025.pdf`
- `Resume - 2026-03.pdf` and `Resume - 2026-03 v2.pdf`
- `Phone Bill - 2025-11.pdf`

**Keep looking before you give up on a name.** If a detail isn't obvious, render the page and read the header, the footer and the small print. Only use a placeholder like `Unknown` when it really isn't in the file, and flag it. The user shouldn't have to rename anything themselves.

---

## Step 6: Prove nothing was lost 🤖

Counting top-level folders doesn't catch a lost file. Do this before you report back.

1. **Compare before and after.** The combined file count and total size across the Desktop and Downloads should match what you wrote down in Step 1. The numbers for each place will change, since files move out of Downloads. The only difference allowed is files the user deleted themselves. Files you add yourself, like a `00 FOLDER MAP.md`, don't count.
2. **Checksum every move between folders.** A file only counts as moved when the copy at the destination matches the original.
3. **If a move got cut off halfway,** the destination can have a partial copy while the original is still at the source. Fix it in this order:
   - Leave the original where it is.
   - Replace the partial copy with a fresh copy of the original. The partial copy is yours, not the user's, so replacing it isn't an overwrite.
   - Check the checksums match.
   - Only then remove the original.
4. **If files vanished during the run,** say so plainly. Usually the user deleted them in Finder or File Explorer. Point them to the Trash in case it wasn't on purpose. Report the lower count either way.

---

## Step 7: Leave a map behind 🤖

- Fill in **My Folder Map** at the bottom of this file.
- In any big folder with lots of subfolders (a business, a client, a big project), add a file called **`00 FOLDER MAP.md`** at its top. It says what each subfolder holds, in a line or two each. The `00` keeps it first in the list so it's the first thing you see when the folder opens.
- If the user chose a file naming pattern, write it in the `00 FOLDER MAP.md` too.
- Report back: the final number of top-level folders, what moved where, what's in `_TO_DELETE/`, and what was flagged.
- Also report the file count and size before and after, and anything left for the user to decide, with the reason.

---

## The rules that keep it clean

- **Never create a new top-level folder.** New things nest inside an existing one. If something truly fits nowhere, leave it loose and flag it. Only the user adds a top-level folder.
- **Count the top-level folders at the end of every run** and report the number. If it went up, something broke the rule.
- **File Claude's outputs with the work they belong to.** A resume goes to `CAREER/`, a budget to `MONEY/`, a guide to `CONTENT/`. Never dump outputs on the Desktop root or in a generic "outputs" folder.
- **Match the naming already in the destination folder.** If a folder names files `Client - Thing - Sep 11`, new files follow that pattern.
- **Old versions go in `_superseded/`** inside the same folder, not a dated folder somewhere else.
- **Finished projects go to `_ARCHIVE/`**, and eventually to an external drive if the user has one.
- **Downloads follows the same map as the Desktop.** It isn't a place to keep things, unless the user said otherwise in Step 2.
- **`_TO_DELETE/` builds up over time.** Duplicates, installers, unzipped zips and empty leftover folders all land there. Only the user empties it.
- **If files disappear from `_TO_DELETE/` mid-run,** assume the user deleted them. Say so, and point them to the Trash in case it wasn't on purpose.
- **Claude's temporary files never stay in the user's folders.** Previews, rendered pages and scratch lists go somewhere outside them, or get removed before you finish. The no-delete rule is about the user's files, not yours.

---

## What NOT to do ❌

- Don't delete, rename, or overwrite anything without asking.
- Don't reorganize the inside of code projects or folders an app depends on.
- Don't create a new top-level folder to "solve" one odd file.
- Don't move big files into an iCloud-synced folder just to organize them; it can try to upload everything.
- Don't decide what a file is from its name. Open it.
- Don't call a duplicate a duplicate until the checksums match.
- Don't remove an original until its copy is checked.
- Don't leave your own temporary files behind.

---

## Monthly 5-minute tidy 🤖

A quick recurring routine (easy to schedule in Cowork):

1. File anything loose on the Desktop root using My Folder Map
2. Clear out Downloads the same way
3. Empty the `PERSONAL/INBOX/` into the right homes
4. Rename new files to the pattern, if the user chose one
5. Move old versions to `_superseded/`
6. Move finished projects to `_ARCHIVE/`
7. Report the top-level folder count and anything flagged
8. Remind the user to empty `_TO_DELETE/` if it has anything in it, and then the Trash

---

## My Folder Map

*(Filled in by Claude after Step 3. Edit anytime. This is the source of truth.)*

**Scope:**
- (Desktop and Downloads? Should Downloads end every run empty?)

| Folder | What lives there |
|---|---|
| | |

**Never move:**
- 

**Naming style:**
- 

**File naming:**
- (None, or `Type - Detail - Date`)

**Always goes to `_TO_DELETE/`:**
- 

**Other people's documents:**
- 

**Private files:**
- 

**Images:**
- (The one folder images go to for the Image Organizer, and where ID photos end up)

**Archive location:**
- 

---

*Built from a real Desktop cleanup: look first → ask → propose a few big folders → file everything → leave a map → never add a new top-level folder.*
