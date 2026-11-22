# Image Organizer: A Universal Guide

Drop this file into the folder you want cleaned up, connect that folder in Cowork, and say: **"Read the Image Organizer file and organize the images in my Downloads folder."** (Swap in any folder name.)

Claude opens every image to see what it actually shows, suggests a few ways to group them, and sorts them once you pick one. After that, this file becomes the rulebook, so new images get sorted the same way every time.

**Using the Desktop Organizer too?** Run it first. It gathers your images into one folder and leaves a folder map behind. Then run this guide on that one folder, and it sorts into the same folder map. Private images go to the ID area that guide made, so you don't end up with two ID folders.

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
5. **If the user ran the Desktop Organizer first,** work only on the one folder it gathered the images into. Read its **My Folder Map** and use those folders as your destinations. Private images go to the ID area in that map. Don't invent new destinations.

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
  - For photos, use the date the photo was taken (from its EXIF info) when it has one. That's more reliable than the file date, which changes when a photo gets copied or downloaded.
- **Duplicates:** the same image, or an older and newer version of it. Compare by name, size, dimensions and what's in the picture.
- **Bursts and near-duplicates:** lots of shots of the same moment, like ten photos of the same group pose or a run of nearly identical screenshots. Note them as one set.
- **People:** whether it's a photo of the user or their friends. These need an extra check before anything gets deleted (see Step 3).
- **Private stuff:** anything that looks like a password, bank or card details, an ID card, a medical record or someone's home address. Mark it private. Don't file it anywhere until the user decides.
  - Payment screens and health claim screenshots count as private too.

For big folders, work in batches of about 50 and keep your notes as you go, so you don't lose track.

**Contact sheets make this faster:**
- **Convert HEIC first.** Lots of tools can't open HEIC photos. Make JPG copies to look at (for example with `sips` on a Mac, or ImageMagick). These copies are only for looking. Never move them into the user's folders.
- **Make numbered sheets.** Put about 20 thumbnails on each sheet and label each one with a number (`#1`, `#2` and so on). Number them straight through, so the second sheet starts at `#21`.
- **Keep an index file.** It maps each number to its filename, so `#14` always points to one exact file.
- **Keep your working files out of the user's folders.** Build the sheets, the index and the HEIC copies in a scratch folder outside the user's folders. If you have to build them inside, delete them before you finish. They're your working files, not the user's images.
- **Open the full image when a thumbnail isn't clear.** The sheet is for speed. It doesn't replace looking.

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
4. Want me to rename generic names like `IMG_4821.png` so they say what's in them? (Default: no.) If yes, I'll use `Type - Detail - Date`, with the date the photo was taken.
5. Anything I should leave exactly where it is?
6. Where should private images go? (Default: ID photos to the ID area of your folder map. Anything else stays where it is.)
7. Should delete candidates stay in this folder, or move to `_TO_DELETE/Images/`? Moving them is handy if you want this folder empty when we're done. Either way, I don't delete anything. You empty it.

**Plan for the tricky ones too:**
- **Private images get a destination, not just a flag.** ID photos, like a driver's licence or a health card, go to the ID area of the folder map (the one the Desktop Organizer made, if the user ran it). Never put an ID photo in the delete pile without saying so.
- **Payment and health claim screenshots get flagged by name,** even if the user wants them deleted. They should know exactly what's in the pile.
- **Photos of the user or their friends:** if the plan sends any of these to delete, confirm once and name what's included. For example: "This includes your graduation photos and the beach day with your friends. Delete those too?" Ask once for the whole group, not once per photo.
- **Bursts and near-duplicates:** offer "keep the best 3 to 5" instead of all or nothing. Show which ones you'd keep and why, like sharpest or eyes open.

Show the full plan, including every new folder you'd create, and **wait for a yes** before moving anything.

---

## Step 4: Sort everything 🤖

Once the plan is approved, decide one of these for each image:

1. **Belongs in a folder in the plan:** move it there.
2. **Already covered:** the same image, or a newer version of it, already exists at the destination. Don't move it. Add it to the delete candidates list with the matching file named next to it.
3. **Inspiration, not used yet:** keep it. Move it into the inspiration folder. If the project has no inspiration folder, create one inside that project's folder. Never treat an unused inspiration image as junk.
4. **Private:** leave it where it is and list it for the user.
   - If the user gave private images a destination in Step 3, like the ID area, move them there instead and still list them.
5. **Unclear:** if you can't tell which folder it belongs in, or whether it's inspiration or an asset, leave it where it is and flag it. Don't guess.
6. **Burst or near-duplicate:** keep the shots the user picked and sort them like any other image. The rest become delete candidates, each listed next to the kept shot that covers it.
7. **Photo of the user or their friends headed for delete:** only if the user confirmed it in Step 3. If they didn't, leave it where it is and ask.

**While you move:**
- **Move, don't copy.** Copies are how duplicates happen.
- **Never overwrite.** If a file with the same name but different content is already at the destination, keep both and add something to the new one's name that tells them apart, like `logo (from Downloads).png`.
- **Check every move.** After each one, confirm the file is in the new place and gone from the old one. If it isn't, stop and tell the user.
- **Never rename** unless the user said yes to renaming in Step 3, or to avoid an overwrite.
- **Only create folders that are in the approved plan.** If an image needs a folder that isn't in it, leave the image and ask.
- **Delete candidates go where the user picked.** They stay in the source folder, or move to `_TO_DELETE/Images/` if that's what the user approved. Use the same `_TO_DELETE/` folder the Desktop Organizer uses if there is one. That move is an approved move. It's still not a delete.

**If the user said yes to renaming:**
- **Use `Type - Detail - Date`.** For example: `Photo - Beach Day - 2025-07-12.jpg`, `Screenshot - Flight Booking - 2025-03-02.png`, `Logo - Dark Version - 2024-10.png`.
- **Use the date the photo was taken,** from its EXIF info, not the file date.
- **No reliable date? Leave it off.** For example: `ID - Health Card.jpg`. Don't guess a date.
- **Match the destination first.** If the folder already has its own naming pattern, follow that instead.

---

## Step 5: Report back and save the plan 🤖

Report back:
- Images moved, grouped by folder, with each new location
- Inspiration images moved, and any inspiration folders you created
- Delete candidates, each with the existing file that covers it
- Private images left in place
- Private images moved to the ID area, or wherever the user picked
- Payment and health claim screenshots, flagged by name, even if they're delete candidates
- Bursts: which shots you kept and which are delete candidates
- Where the delete candidates are: still in the source folder, or in `_TO_DELETE/Images/`
- Images left in place and why (unclear, or not part of the plan)
- Anything you couldn't open or check
- That your contact sheets, index and HEIC copies are gone from the user's folders

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
- **Moving candidates to `_TO_DELETE/Images/` is fine only if the user approved it.** It's a move, not a delete. The user empties it.
- **Private images never go in the delete pile without saying so.**
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
- Don't file private images. List them. The only exception is a destination the user approved in Step 3, like the ID area.
- Don't move images an app or a code project depends on, like the images inside a website project's folder.
- Don't create a folder to "solve" one odd image. Leave it and flag it.
- Don't send photos of the user or their friends to delete without confirming once first.
- Don't leave contact sheets, index files or HEIC copies in the user's folders.
- Don't make a new ID folder when the Desktop Organizer already made one.

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

**Naming (if renaming):**
- `Type - Detail - Date`, using the date the photo was taken

**Never move:**
- 

**Source folder:**
- 

**Private images go to:**
- 

**Delete candidates go to:**
- *(stay in the source folder, or `_TO_DELETE/Images/`)*

**Photos of the user or friends:**
- Confirm once before any go to delete

---

*Built from a real image cleanup: look at every image → ask how to group them → sort → list delete candidates → never delete.*
