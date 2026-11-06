# How to organize a messy image folder with Claude

*Updated Nov 2026*

I built this to clean up my own messy image folders with Claude. A filename like `IMG_4821.png` doesn't tell you much, so Claude opens every image to see what's in it, asks how you want things grouped, and only then moves anything. It never deletes. This guide gives you the rulebook and walks you through your first cleanup.

## At a glance

| | |
|---|---|
| **Difficulty** | Easy, no coding |
| **Time** | One sitting for most folders. Big folders take longer because Claude opens every image |
| **You'll end up with** | Your images sorted into folders you picked, a list of likely duplicates for you to decide on, and nothing deleted |

## Start here

Download [`image-organizer.md`](image-organizer.md), put it in the folder you want cleaned up, then paste this into Claude:

```text
Read the Image Organizer file and organize the images in my Downloads folder.
```

If your mess lives somewhere else, like your Screenshots or Desktop folder, swap in that folder's name.

## What you need

- The Claude desktop app with Cowork (Claude Code works too)
- The messy folder connected as a folder in Cowork
- Any folders you want images sent to, connected too (for example, your project folders)
- The [`image-organizer.md`](image-organizer.md) file from this folder

## Steps

1. **Download the rulebook.** Click [`image-organizer.md`](image-organizer.md), then the download button at the top right of the file. Move it into the folder you're cleaning up.
   You're done when the file is in that folder.
2. **Connect your folders.** In Cowork, add the messy folder. If you want images to go into folders that live somewhere else, like project folders on your Desktop, add those too. Claude can only move files between folders it can see.
   You're done when Claude can list what's in each one.
3. **Paste the prompt** from Start here.
   You're done when Claude tells you how many images it found and what file types they are.
4. **Let Claude look at every image.** It opens each one and notes what it shows, like a screenshot of a receipt, a logo, a product photo or a design you saved for ideas. The filename is only a hint. What's in the picture decides where it goes.
   You're done when Claude shows you a summary of what it found and two or three ways to group it.
5. **Pick how you want them grouped.** Choose one of Claude's options or mix them. You can group by project, by type (screenshots, inspiration, photos, logos, assets) or by date. Rename any folder, and tell Claude your project names so it can match images to them. Claude won't move a single file until you say yes.
   You're done when you've said yes to the plan.
6. **Let Claude sort.** It moves each image into its folder, checks that every move landed and keeps both files if two share a name. Anything it isn't sure about stays where it is and gets flagged.
   You're done when Claude reports what moved where, the delete candidates and what it flagged.
7. **Decide on what's left.** The images still in the original folder are the delete candidates and the flagged ones. Claude lists each delete candidate next to the file that already covers it. Look through them and delete what you don't want yourself. Deleting is always your call.
   You're done when every image left in the folder is one you chose to keep there.
8. **Optional: use big folders mode.** For hundreds of images across several projects, the rulebook has a mode where you run one Claude chat per project and each one claims only its own images. See the tip below.

## Tips and watch outs

💡 **Name your projects out loud.** Claude can see a logo is a logo, but it can't know which project it's for unless you tell it. A short list of your projects in step 5 makes the sorting a lot more accurate.

💡 **Keep your inspiration.** An image you saved for ideas and never used isn't junk. The rulebook puts it in an inspiration folder instead of the delete list.

💡 **The plan is saved for next time.** Claude fills in a "My Image Plan" section at the bottom of the rulebook. Next time, paste "Read the Image Organizer file and sort my new images," and it follows the same plan without asking again.

💡 **Big folders mode.** Open a separate Claude chat for each project and paste: "Read the Image Organizer file. Use big folders mode. You own the images for [project name], and its folder is [folder name]." Each chat takes only its own images and leaves the rest. When they're all done, run one normal cleanup on what's left.

⚠️ **Screenshots can hold private stuff.** Claude flags images that look like passwords, bank details or ID cards instead of filing them. Check those yourself.

⚠️ **iCloud files can look broken.** If the folder syncs to iCloud, some images show up but aren't downloaded yet. Download them first. Claude flags any image it can't open instead of guessing.

⚠️ **"Empty" usually means the wrong folder.** If Claude says a folder has no images and you know it does, it's looking in the wrong place.

⚠️ **Looking takes time.** Claude opens every image, so a folder with thousands of them is slow. Split it into smaller batches or use big folders mode.

---

Something didn't work? [Open an issue](https://github.com/Lily-Tewolde/ai-guides/issues) and tell me what happened.

Made by [Lily Tewolde](https://github.com/Lily-Tewolde). Find me on TikTok at [@lilytewolde](https://www.tiktok.com/@lilytewolde) and on Instagram at [@promptesss](https://www.instagram.com/promptesss).
