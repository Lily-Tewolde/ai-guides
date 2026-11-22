# How to organize your Desktop with Claude

*Updated Nov 2026*

I wrote this rulebook after cleaning up my own Desktop with Claude. It's down to six folders now, and it stays that way because Claude follows the same rules every time it tidies up. This guide gives you that rulebook and walks you through the first cleanup.

It covers your Downloads folder too, since that's usually where the real mess is. Claude opens files to see what they actually are instead of trusting the names, and it checks at the end that nothing was lost.

## At a glance

| | |
|---|---|
| **Difficulty** | Easy, no coding |
| **Time** | One sitting for the first cleanup, then 5 minutes a month |
| **You'll end up with** | 5 to 8 folders on your Desktop, a map of what goes where, and nothing deleted |
| **Covers** | Your Desktop and Downloads |

## Start here

Download [`desktop-organizer.md`](desktop-organizer.md), put it on your Desktop, then paste this into Claude:

```text
Read the Desktop Organizer file and organize my Desktop.
```

## What you need

- The Claude desktop app with Cowork (Claude Code works too)
- Your Desktop connected as a folder in Cowork
- Your Downloads folder connected too
- The [`desktop-organizer.md`](desktop-organizer.md) file from this folder

## Steps

1. **Download the rulebook.** Click [`desktop-organizer.md`](desktop-organizer.md), then the download button at the top right of the file.
   You're done when the file is on your Desktop.
2. **Connect your Desktop and Downloads.** In Cowork, add both as folders.
   You're done when Claude can list what's on them.
3. **Paste the prompt** from Start here.
   You're done when Claude tells you what it found:
   - how many folders
   - how many loose files
   - how many files in total and how big they are
   - duplicates and old versions
   - anything that looks important
   - anything sensitive, like other people's details, passwords or screenshots of your ID
4. **Answer Claude's questions.** It asks about:
   - the big areas of your life
   - what to keep separate
   - how you like folder names
   - what it should never move
   - which areas you're done with
   - what to do with other people's documents
   - whether you want your files renamed

   You're done when Claude shows you a proposed map of 5 to 8 folders.
5. **Check the map before anything moves.** Change anything that doesn't fit, then say yes. Claude won't move a single file until you do.
   You're done when you've said yes.
6. **Let Claude file everything.** It moves files into the new folders and puts anything that looks like junk in a `_TO_DELETE/` folder instead of deleting it. That includes exact duplicates, installers for apps you already have, and zips you've already unzipped. Older versions go to a `_superseded/` folder next to the current one.
   You're done when everything has a home.
7. **Optional: let Claude rename your files.** Only if you said yes in step 4. It uses `Type - Detail - Date`, like `Phone Bill - 2025-11.pdf`, and it checks what each file is before naming it.
   You're done when the names make sense without opening anything.
8. **Check nothing was lost.** Claude compares the file count and total size from before and after, and checks every file it moved between folders.
   You're done when Claude reports the number of folders, what moved where, what it flagged, and that the before and after numbers match.
9. **Empty `_TO_DELETE/` yourself.** Look through it first. Deleting is always your call. Then empty the Trash.
   You're done when both are empty.
10. **Optional: schedule the monthly tidy.** The rulebook has a 5-minute routine at the bottom. It clears out Downloads too. Ask Claude to run it on the first of every month.

## Tips and watch outs

💡 **Fewer folders is better.** Every folder should be a big area of your life, like work, money or school, not a single project.

💡 **The map is the source of truth.** Claude fills in a "My Folder Map" section at the bottom of the rulebook. Next time, it reads that first, so you never have to explain your setup again.

💡 **Big folders get their own map.** For a business or a big project, Claude adds a `00 FOLDER MAP.md` file at the top that says what each subfolder holds.

💡 **Filenames lie.** A file called `Party Checklist.pdf` can turn out to be a lease. Claude opens files to check what they are, so things don't get filed by a bad name.

💡 **Photos go to the Image Organizer.** Claude gathers your images into one folder and leaves the sorting to the [Image Organizer](../03-image-organizer/image-organizer.md). Both guides use the same folder map.

⚠️ **Moving out of Downloads asks for permission to delete.** Cowork shows a deletion prompt because a move is a copy, then removing the original. Nothing gets thrown away. Say yes.

⚠️ **iCloud files can look broken.** If your Desktop syncs to iCloud, some files show up but aren't downloaded yet. Download them first. They're not missing.

⚠️ **"Empty" usually means the wrong folder.** If Claude says a folder is empty and you know it isn't, it's looking in the wrong place.

⚠️ **Leave code projects and app folders alone.** Claude can move the whole folder, but it shouldn't rearrange anything inside.

⚠️ **That app icon on your Desktop might be an installer.** It's often a mounted installer disk. Eject it and open the app from Applications or Launchpad.

---

Something didn't work? [Open an issue](https://github.com/Lily-Tewolde/ai-guides/issues/new?template=something-didnt-work.yml) and tell me what happened.

Made by [Lily Tewolde](https://github.com/Lily-Tewolde). Find me on TikTok at [@lilytewolde](https://www.tiktok.com/@lilytewolde) and on Instagram at [@promptesss](https://www.instagram.com/promptesss).
