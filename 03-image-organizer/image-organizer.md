# Image Organizer: A Universal Guide

Drop this file into the folder you want cleaned up, connect that folder in Cowork, and say: **"Read the Image Organizer file and organize the images in my Downloads folder."** (Swap in any folder name.)

Claude opens every image to see what it actually shows, suggests a few ways to group them, and sorts them once you pick one. After that, this file becomes the rulebook, so new images get sorted the same way every time.

Each step is tagged:
- 🤖 **Auto**: Claude does this for you
- 🙋 **You decide**: Claude asks, you answer

> **Golden rule:** Move, never delete. Claude only lists delete candidates. Nothing gets deleted, overwritten or renamed without your OK.

---

## How Claude should use this file

You (Claude) are organizing the images in a folder the user names. This file is your operating spec.

1. **First run:** do Steps 1 to 5 in order. Don't move a single file until the user has approved the plan in Step 3.
2. **Every run after that:** read this whole file first, especially **My Image Plan** at the bottom. Sort new images by that plan and only ask about images that don't fit it. The plan in this file outranks anything you remember.
3. **When the user changes their mind** about where something goes, update My Image Plan in the same session.
4. **If the user says "big folders mode,"** skip Step 3 and follow the Big folders mode section. Steps 1, 2 and 4 still apply.

---

## Step 1: Find the folder and count what's there 🤖

- Check that you can open the folder the user named. If you can't, ask the user to connect it in Cowork and wait. Don't start until you have access.
- Also check access to any folder the user wants images sent to.
- Count the images, top level and inside subfolders. Report the total, the file types (PNG, JPG, HEIC, GIF, WEBP, SVG) and how many sit in subfolders.
- Leave anything that isn't an image alone. Don't move, sort or report on other files unless the user asks.

**Two traps to check:**
- **iCloud-synced folders:** files can show up but not be downloaded yet. If an image won't open, don't move or compare it. Flag it.
- **An empty result usually means the wrong path**, not an empty folder. Double-check where you're looking before telling the user it's empty.

---

## Step 2: Look at every image 🤖

Open each image and look at it. Don't sort by filename alone. Names like `IMG_4821.png` or `Screenshot 2025-03-02` say almost nothing about what's in the picture.

For each image, note in a word or two:
- **What it is:** screenshot, photo, logo, icon, design or mockup, illustration, document or receipt, meme, inspiration
- **What it's about:** the app, website, product, place or project it shows, if you can tell
- **The date,** if it's in the filename or the file's info. If there's no reliable date, say so. Don't guess.
- **Duplicates:** the same image, or an older and newer version of it. Compare by name, size, dimensions and what's in the picture.
- **Private stuff:** anything that looks like a password, bank or card details, an ID card, a medical record or someone's home address. Mark it private. Don't file it anywhere until the user decides.

For big folders, work in batches of about 50 and keep your notes as you go, so you don't lose track.

---

## Step 3: Propose how to group them 🤖 then 🙋

Tell the user what you saw in plain language: how many of each kind, the projects or topics you spotted, how many duplicates and how many private images.

Then offer **two or three ways to group them**, built from what's actually there:

| Option | Folders look like | Works well when |
|---|---|---|
| **By project** | One folder per project, with `assets/` and `inspiration/` inside each | Most images belong to work or side projects |
| **By type** | `Screenshots/`, `Inspiration/`, `Photos/`, `Logos/`, `Assets/` | It's a general mix with no clear projects |
| **By date** | One folder per year, or per month inside each year | Most images are photos or screenshots with dates |

Mixing is fine. For example, by project first, then screenshots and inspiration inside each project.

For each option, show the folder names, how many images would go in each and two or three examples per folder. Then ask:

1. Which option do you want, or how should I change it?
2. What are your projects called? (Only if you're grouping by project. Use their names, not your guesses.)
3. Where should the sorted folders live? Inside this folder, or in existing folders somewhere else, like your project folders?
4. Want me to rename generic names like `IMG_4821.png` so they say what's in them? (Default: no.)
5. Anything I should leave exactly where it is?

Show the full plan, including every new folder you'd create, and **wait for a yes** before moving anything.

---

## Step 4: Sort everything 🤖

Once the plan is approved, decide one of these for each image:

1. **Belongs in a folder in the plan:** move it there.
2. **Already covered:** the same image, or a newer version of it, already exists at the destination. Don't move it. Add it to the delete candidates list with the matching file named next to it.
3. **Inspiration, not used yet:** keep it. Move it into the inspiration folder. If the project has no inspiration folder, create one inside that project's folder. Never treat an unused inspiration image as junk.
4. **Private:** leave it where it is and list it for the user.
5. **Unclear:** if you can't tell which folder it belongs in, or whether it's inspiration or an asset, leave it where it is and flag it. Don't guess.

**While you move:**
- **Move, don't copy.** Copies are how duplicates happen.
- **Never overwrite.** If a file with the same name but different content is already at the destination, keep both and add something to the new one's name that tells them apart, like `logo (from Downloads).png`.
- **Check every move.** After each one, confirm the file is in the new place and gone from the old one. If it isn't, stop and tell the user.
- **Never rename** unless the user said yes to renaming in Step 3, or to avoid an overwrite.
- **Only create folders that are in the approved plan.** If an image needs a folder that isn't in it, leave the image and ask.

---

## Step 5: Report back and save the plan 🤖

Report back:
- Images moved, grouped by folder, with each new location
- Inspiration images moved, and any inspiration folders you created
- Delete candidates, each with the existing file that covers it
- Private images left in place
- Images left in place and why (unclear, or not part of the plan)
- Anything you couldn't open or check

Then fill in **My Image Plan** at the bottom of this file, so the next run sorts the same way.

---

## Big folders mode 🙋 then 🤖

For hundreds of images across several projects, the user runs one Claude chat per project. Each chat owns one project. The user tells it the project name and its folder.

If you're one of these chats:
- Only claim images that clearly belong to **your** project. Start with any subfolder that matches your project's name, then go through the loose images.
- Look at each image, not just its name, the same way as Step 2.
- Sort what's yours into your project's existing folder, using the same decisions and rules as Step 4. Use the project's existing `assets` and `inspiration` folders if it has them. If it has no inspiration folder, create one inside the project's folder.
- Leave everything that isn't clearly yours exactly where it is, and add it to a "not mine" list.
- If an image is already gone when you get to it, another chat probably moved it. Skip it.
- Never create a folder outside your project's existing folder.
- Report back the same way as Step 5, plus the "not mine" list.

When every project chat is done, the user runs one normal cleanup on whatever's left.

---

## The rules that keep it clean

- **Don't delete anything.** Deleting is the user's call. You only list candidates.
- **Never overwrite.** Keep both files with a name that tells them apart.
- **Check every move landed.**
- **Flag, don't guess.** Unclear images stay where they are.
- **Keep inspiration images,** even ones that were never used.
- **Never create a new top-level folder** (on the Desktop, in the home folder or at the top of a drive) without asking. New folders go inside the folders the user approved.
- **Match the naming already in the destination folder** if you're renaming. If a folder names files `Logo - Dark - v2`, new files follow that pattern.

---

## What NOT to do ❌

- Don't delete, overwrite or rename anything without asking.
- Don't sort by filename alone. Look at the image.
- Don't file private images. List them.
- Don't move images an app or a code project depends on, like the images inside a website project's folder.
- Don't create a folder to "solve" one odd image. Leave it and flag it.

---

## My Image Plan

*(Filled in by Claude after Step 3. Edit anytime. This is the source of truth.)*

**How images are grouped:**
- 

| Folder | What goes there |
|---|---|
| | |

**Projects:**
- 

**Rename generic names:**
- No

**Never move:**
- 

---

*Built from a real image cleanup: look at every image → ask how to group them → sort → list delete candidates → never delete.*
