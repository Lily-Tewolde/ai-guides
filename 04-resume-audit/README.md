# How to audit and tailor your resume with Claude

*Updated Nov 2026*

This is how I audit my resume against a job post and tailor it, step by step, with a copy-paste prompt for each step. I built it during my own job search. I do it with Claude on an editable .docx, but the steps work with any AI assistant or by hand. Every example below is made up.

## At a glance

| | |
|---|---|
| **Difficulty** | Easy, no coding |
| **Time** | One sitting to set up your files, then one pass per job post |
| **You'll end up with** | A tailored resume as .docx and .pdf, checked before it goes out, plus a bullet bank you reuse every time |

## Start here

Download [`resume-audit.md`](resume-audit.md), put it in your job search folder, then paste this into Claude:

```text
Read the Resume Audit file and tailor my resume for [ROLE] at [COMPANY]. Here's the job post: [PASTE JOB POST]
```

The first time, Claude helps you fill in your [`My Resume Rules.md`](My%20Resume%20Rules.md), so every resume after that follows the same rules. It lives in your own folder next to your [`Bullet Bank.md`](Bullet%20Bank.md) and, if you want one, a [`Decision Log.md`](Decision%20Log.md). All three are blank templates in this folder (see [Set up once](#set-up-once)). No bullet bank yet? Claude starts with a [first build](#first-build-when-you-dont-have-a-bullet-bank-yet).

Doing this for a friend or family member? Give them their own folder and read [Keeping someone else's resume private](#keeping-someone-elses-resume-private) first. Anything only they can answer goes to them, and new wording stays ★ until they've OKed it.

Want more control? Go step by step below. Every step has its own prompt.

Here's the whole thing in short:

0. Pick one direction, if you're aiming at more than one kind of role
1. Gather the job post, your rules, your bullet bank and your base resume before touching anything
2. Check the role is a real fit and decide if tailoring is worth it
3. Map every must-have to proof, and mark the gaps
4. Mirror the post's exact words, and count keywords as the fallback
5. Swap and reorder bullets from the bank, X-Y-Z, strongest first
6. Keep it to one page, checked in the format that goes out
7. Leave titles alone unless there's a real reason
8. Format the page
9. Run the pre-send checks, save, and review before anything goes out

## What you need

- Claude (any plan), or any AI assistant
- The Claude desktop app with Cowork, if you're using the file (Claude Code works too)
- The [`resume-audit.md`](resume-audit.md) file from this folder
- The blank [`My Resume Rules.md`](My%20Resume%20Rules.md), [`Bullet Bank.md`](Bullet%20Bank.md) and [`Decision Log.md`](Decision%20Log.md) files from this folder
- The full job post
- Your current resume. A PDF is enough to start (see Step 1)
- The files below. The prompts assume you've attached your My Resume Rules.md, your Bullet Bank.md and your base resume

### Set up once

Keep everything in one folder per person, even when it's your own resume. That way it still works when you're helping someone else, and nobody's facts get mixed up.

```
Job search/
├── resume-audit.md
└── [Your name]/
    ├── My Resume Rules.md
    ├── Bullet Bank.md
    ├── Decision Log.md       (optional)
    ├── Story bank
    ├── Standard resume.docx
    └── [Company]/
        └── version history/
```

1. **[`My Resume Rules.md`](My%20Resume%20Rules.md).** Your rules file. Claude reads it first every time, and helps you fill it in if it's still blank. It covers:
   - where your standard resume, bullet bank and story bank live
   - a table of canonical numbers, so the same figure never shows up two different ways
   - your titles, the same as LinkedIn
   - names you can't share, like clients or partners
   - your house style: font, size, margins, header and colour
2. **[`Bullet Bank.md`](Bullet%20Bank.md).** Every bullet you have, grouped by role, each tagged with what it proves (`[onboarding] [experimentation] [revenue]`). Mark new, unapproved bullets ★ and known-weak ones ⚠. At the bottom, a "never write" list of claims you can't back up.
3. **A story bank.** Your interview stories (STAR or similar). Prep keeps surfacing results that never made it onto the resume, and those are often your strongest bullets.
4. **A standard resume** as an editable .docx. This is what goes out by default, and its layout is the template every tailored version is built from. Only have a PDF? See Step 1.
5. **[`Decision Log.md`](Decision%20Log.md), if you want one.** One entry for every decision: the date, the decision and why. It's how you remember later why a bullet moved or a title stayed.
6. **One folder per company** for tailored versions, with a `version history/` folder inside for anything older.
7. **A note per application** that saves the full job post word for word, because postings come down.

### Keeping someone else's resume private

I've used this on a friend's resume, and it's easy to slip when you're also writing about the method in public. When you use it on someone else's resume:

1. Their details stay in their own folder, next to their My Resume Rules.md
2. Their details never go into a public repo, an issue or a shared doc without them knowing
3. Any example you share about what you learned is made up

---

## First build: when you don't have a bullet bank yet

Everything below is "swap, don't rewrite", and that only works once you have a bank of approved bullets. The first time, you build the bank from the resume you already have:

1. Every bullet gets rewritten into X-Y-Z (see Step 5)
2. Anywhere a number is missing gets a `[__]` blank, and Claude asks you for it instead of guessing. The same goes for any other missing fact, like a location. If a line has no result at all, like "Helped plan events", Claude asks what changed because of your work instead of making one up
3. Every line is marked ★, because none of them are approved yet
4. You fill in the blanks and OK each line, and it all goes into your Bullet Bank.md

After that, every tailor is a swap.

**Prompt**

```
I don't have a bullet bank yet. Take every bullet on my current resume and rewrite it in X-Y-Z, outcome and number first, then how. Wherever a number or another fact is missing put a [__] blank and ask me for it, don't guess. If a line has no result at all, ask me what changed because of the work, don't make one up. Mark every line ★ since none of them are approved yet, group them by role, tag each one with what it proves, and save them as my Bullet Bank.md.
```

You're done when every bullet is in your bank in X-Y-Z, every blank has a real number, and you've OKed each line.

---

## Step 0: Pick a direction

Skip this if you know the one kind of role you're going for. If you're split between two, like two master resumes with two different objectives, pick one before you tailor anything.

1. **Compare the paths** on pay, licensing and which title each one leaves on your LinkedIn
2. **Get one recommendation:** one direction and one title, and why
3. **You decide.** The direction goes in your My Resume Rules.md, so every tailor after that points the same way

**Prompt**

```
I'm aiming at two kinds of roles: [PATH 1] and [PATH 2]. Here are both versions of my resume. Compare the two paths on pay, licensing and which title each one would leave on my LinkedIn. Then recommend one direction and one title and tell me why. I'll decide, and then add it to My Resume Rules.md.
```

You're done when you've picked one direction and one title.

---

## Step 1: Gather everything before starting

1. **The full job post, word for word.** Exact title, must-haves, nice-to-haves, every tool named. Save it.
2. **What the recruiter said they want**, if anyone said anything. One line from a recruiter ("we want someone who writes evals") can change which bullets lead.
3. **Your My Resume Rules.md and Bullet Bank.md,** read first, every time. Go by the written files, not memory (yours or the AI's).
4. **The base resume, as the .docx.** Your standard resume by default. Don't use an older role-type variant with different titles, it can contradict your LinkedIn.
   - **Only have a PDF?** That's enough. Claude pulls the text out of the PDF and builds the editable .docx from the template you chose. Nothing gets typed in by hand: every line on the new version comes from the PDF text. Then it carries on with the [first build](#first-build-when-you-dont-have-a-bullet-bank-yet).
5. **Proof the base is what its name says.** A file sitting in a company folder isn't proof it was tailored. When I audited mine, several "company" versions turned out to be the same document renamed. Check size and date, not the filename.
6. **Fresh material** from your story bank.
7. **Facts only you can give.** If the post asks for something your bank doesn't cover, write down the facts yourself before anything gets drafted.
8. **The application form**, if there is one. Check it before drafting, it shows what else is being asked.
9. **Anything else the post asks for,** like a cover letter, a transcript or references. Note it now so it isn't a surprise at the end.

**Prompt**

```
I'm tailoring my resume for [ROLE AS POSTED] at [COMPANY]. Here's the full job post, keep it word for word so we still have it if they take it down: [PASTE JOB POST]. Before you touch anything read My Resume Rules.md and my Bullet Bank.md, and use my standard resume .docx as the base unless I say otherwise. Check the base is really the file you think it is by its size and date, not just its name. The recruiter told me they're looking for [WHAT THEY SAID, OR "nothing yet"]. Don't edit anything yet, just tell me what you've got, what the form asks for, anything else the post wants like a cover letter or references, and what you still need from me.
```

**If you only have a PDF**

```
All I have is my resume as a PDF. Pull the text out of it and build an editable .docx from [MY TEMPLATE FILE]. Don't type anything in by hand, every line on the new version has to come from the PDF text. Then do a first build of my bullet bank from it.
```

You're done when Claude has the job post saved, has read your rules and bullet bank, and has told you what it still needs from you.

---

## Step 2: Check the fit and decide whether to tailor

1. **A matching job title isn't a fit.** Check the must-haves against your real background first. If the core of the role is a domain or stack you've never worked in, skip it. I learned this from a same-day rejection on a role whose domain wasn't anywhere on my resume.
2. **My fit bar:** most or all must-haves, years can flex by about a year, ideally almost all nice-to-haves.
3. **Tailoring works.** I still default to my standard resume when it's already getting replies, and tailor when it's a real competitive edge or necessary.
4. **When I do tailor,** it's bullet swaps and reordering with titles unchanged, saved in that company's folder.

**Prompt**

```
Go through the must-haves and tell me if I really meet most or all of them. Years can flex by about a year. If the core of the role is a domain or a stack that isn't anywhere on my resume, say so and we'll skip it. Then tell me if my standard resume is good enough for this one or if tailoring would give me a real edge, and why. If you think it's worth tailoring, it's bullet swaps and reordering only, titles stay the same.
```

You're done when you've decided to skip the role, send your standard resume, or tailor. If you skip it, stop here.

---

## Step 3: Compare the resume to the job post

1. **Quote the must-haves and nice-to-haves verbatim,** then put your proof next to each one: the bank bullet or tag that covers it.
2. **Mark the gaps and leave them off.** If the post lists a tool or framework you haven't used, it doesn't go on the resume, even when it's listed right next to two you have. If you've used a specific standard, write it with its number rather than a vague family name.
3. **Don't write the gap down either.** No lines admitting what you haven't done. Lead with what you have and let the gap go unmentioned.
4. **Check for gaps you might actually cover.** Some are work you did that never became a bullet. Those are questions for you, not guesses for the AI.
5. **Check the base's weighting.** A version built for one employer leans their way. If your base leads with quality and testing and the new post is about building, demote that or you'll read like a QA specialist.

**Prompt**

```
Quote every must-have and nice-to-have from the post word for word and put my proof next to each one, the bullet or tag from my bullet bank that covers it. If nothing covers it mark it as a gap and don't write anything to fill it, and don't add any line that admits what I haven't done either. Tell me which gaps might be things I've done but never wrote down so I can give you the facts. Also tell me if my base leans too hard one way for this post.
```

You're done when every must-have has proof next to it or is marked as a gap.

---

## Step 4: Find the keywords and mirror the true ones

1. **Pull the literal vocabulary.** The exact title, the phrases in the must-haves, every tool named.
2. **Mirror it in 4 places, only where it's true:**
   1. **The first summary label.** If the post is for a "Payments Product Manager", that can be your label.
   2. **The summary nouns.** If the post asks for "experience in usage-based pricing" and you have it, the summary says so in those words.
   3. **The skills lines.** If the post names 5 analytics tools, list the ones you've used, in their spelling.
   4. **The nouns inside a bullet.** "Tiered pricing" can become "tiered seat-based plans" if that's what it was and that's their word for it.
3. **Keep it sounding like you.** If a keyword makes a line sound machine-written, leave it out. A recruiter notices that faster than any keyword.
4. **Across many posts,** I compare the keywords that repeat in posts that got replies vs the ones that didn't. That steers which roles I search for, not the resume itself.

**Fallback: count the keywords.** Mirroring is the main method, and if your resume already mirrors the posts you apply to, it's usually enough. When it isn't, count:

1. List the words and phrases the post repeats.
2. Count how many times each one shows up in the post.
3. Check which ones are missing from your resume.

The true ones go in the 4 places above and the rest stay off.

**Prompt**

```
Pull out the exact words and phrases the post uses for the title, the skills and the tools. Show me where each one already shows up on my resume and where it could go if it's true for me: the first summary label, the summary nouns, the skills lines, or the nouns inside a bullet. Don't add anything I can't back up, and if a phrase would sound weird said out loud across a table, leave it out.
```

**Fallback prompt**

```
My resume mirrors the post but I want to check it the other way too. List every word and phrase the post repeats with how many times each one shows up, and next to each one say whether it's on my resume. For the missing ones tell me which are true for me and where they'd go, and leave the rest off.
```

You're done when every true keyword has a place on your resume, and nothing untrue made it on.

---

## Step 5: Rewrite the bullets

**Swap, don't rewrite.** The bank holds approved wording. Tailoring is choosing and ordering, and the facts don't move. No bank yet? Start with the [first build](#first-build-when-you-dont-have-a-bullet-bank-yet).

1. **Counts.** Current role 4 to 5, earlier roles 2 to 3, never 6, never a single-bullet role.
2. **Order.** Inside each role, most relevant to this post at the top. Not chronology, not the biggest number. Re-rank on every tailor. The first bullet should make them think you've done this exact job. Side projects like marketing automation go last almost every time.
3. **X-Y-Z.** Accomplished [X] as measured by [Y] by doing [Z]. The outcome and its number open the bullet and the method follows.
   - Good: *Cut checkout time 27% (11 min to 8 min) by shipping a one-page checkout with saved payment methods*
   - Bad: *Shipped a one-page checkout with saved payment methods, cutting checkout time 27%*
4. **Reframe nouns, never facts.** Use the post's word for the same thing. Don't invent.
5. **Bullets stay inside their own role.** If you held several titles at one company, each keeps its own bullets.
6. **Strongest verb.** Weak openers: Caught, Scored, Ran, Helped, Supported, Assisted, Worked on. "Caught 7 pricing errors" becomes "Blocked 7 pricing errors from shipping". "Scored 400+ support replies" becomes "Cut QA review to 45 minutes a week" when speed was the real outcome.
7. **Condensed.** Before-and-after in parentheses with units abbreviated: "27% (11 min to 8 min)", not "27%, from 11 minutes to 8".
8. **Two lines max, no terminal periods, no I, me, my, we or our.**
9. **A complete thought, not a complete sentence.** When a trailing clause only points back ("...and checking every release against it"), collapse it: "by checking every release against a written style guide".
10. **Say it out loud.** If it'd sound odd across a table, it's wrong on the page. "Driving impact at scale" is the kind of phrase to cut.
11. **No repeated opening verb in adjacent bullets,** including the last bullet of one role and the first bullet of the next. Fix it by reordering, not rewording.
12. **Mechanisms that are too specific are interview detail.** "By removing the phone-verification step and adding a guest mode" becomes "by streamlining sign-up".
13. **New bullets** are written X-Y-Z from your story bank or your facts, added to the bank marked ★, and approved by you before they go on anything that goes out. The ★ stays in the bank and never shows on the resume.
14. **New grads: school projects go under Projects.** School and capstone projects go in a Projects section, not Experience, so the only job titles on the page are real ones that match your LinkedIn.

**The summary**

1. Exactly 2 bullets, each with a short bold label that names a kind of person ("Growth Product Manager", "Technical Builder"). If the label runs long, cut it.
2. **The first label matches the post's title.**
3. **The first bullet opens with who you are,** like "Bilingual operations lead".
4. High level, no metrics. These can run 2.5 to 3 lines.
5. **Never repeat a bullet** from further down the page.
6. **Treat the scaffolding as a template you fill in.** Only the labels and the nouns change. Rewriting the clauses reopens wording you've already approved, and it's where tailored summaries start reading strangely.

**The skills**

Bulleted with bold category labels, and the categories get rebuilt around the post's language. A regulated-industry role might get its own compliance line. An AI-tools-heavy role might get a line just for the tools it names.

**Prompt**

```
Now swap bullets, don't rewrite them. Take 4 to 5 for my current role and 2 to 3 for each earlier one from my bullet bank, keep each bullet inside its own role, and order each role by what this employer wants most with the strongest match first. Keep the X-Y-Z format with the outcome and number first, two lines max, no periods, no I or my, the strongest opening verb, and no two bullets in a row starting with the same verb, including across roles. Fix a repeated verb by reordering, not rewording. You can change a noun to match their wording but don't change any facts. If a bullet has to be written from scratch, draft it from my facts in X-Y-Z, mark it new and show me before it goes anywhere. School and capstone projects go under Projects, not Experience. For the summary only swap the two labels and the nouns and leave the rest of each sentence exactly as it is. Rebuild the skills categories around their wording.
```

You're done when every role has the right number of bullets, in the right order for this post, and any new bullet has your OK.

---

## Step 6: Decide what to cut

1. **Always one page.** Check the page count after every build, don't guess. Check it in the format that's going out, Google Docs or the PDF. Different apps lay out pages a little differently, so a .docx that fits can spill over once it's converted. If a bullet goes on, another comes off.
2. **When it runs over, fix it in this order:**
   1. Tighten the spacing
   2. Tighten the wording, never the facts
   3. Cut the weakest bullet, from the bottom of the relevance order

   Never shrink the font below the minimum in your rules file to make room.
3. **Never two bullets on one page that spend the same result.** Two bullets about the same project, or two measurements of the same outcome, read thinner than one.
4. **Unfinished bullets stay off.** No number means not finished.
5. **Process bullets don't show outcomes.** A bullet about your intake or delivery process comes off unless the role is about running that process.
6. **A list of product names isn't a bullet.** A launch count can live in the summary instead.
7. **Side-project-looking bullets go last or come off.**
8. **When the page forces a choice between roles, you make it.** Ask for the options with the page result of each.
9. **If a whole section has to go,** a secondary one (consulting, advisory, volunteer) is usually the first.

**Prompt**

```
Tell me the page count in the format that's going out, the PDF or the Google Doc. It has to be one page. If it runs over, tighten the spacing first, then the wording without changing any facts, then cut the weakest bullet at the bottom of a role. Never shrink the font below the minimum in my rules file. Make sure no two bullets on the page are the same result told twice, nothing without a number goes on, and anything too detailed moves to my interview notes instead. If the only way to fit is choosing between two roles, show me the options with the page result for each and let me pick.
```

You're done when it's one page in the format that's going out.

---

## Step 7: Handle titles

1. **Titles stay the same as LinkedIn and your standard resume by default.** Tailored versions keep them unchanged, and only you change them. When a title or date is unclear, check LinkedIn.
2. **Keep titles consistent, even if another one sounds better.** A recruiter who sees one title on the resume and another on LinkedIn has a question you didn't want them to have.
3. **Retitle only for a real edge, and only to something true.** If your actual role was a product role on a community product, a title that says so can match a community-focused post.
4. **Internal titles recruiters don't search.** If an employer used level codes or HR bands ("Analyst II", "Associate, Level 3"), use the functional title for the work you did, the one a recruiter would type into a search bar, and use the same one on LinkedIn.
5. **Titles that undersell the work.** If your official title doesn't match the industry-standard name for what you actually did (an operations title for product management work, say), recruiters searching for that work won't find you. Switching to the standard title is fair when it describes the work you really did. Change the resume and LinkedIn at the same time.
6. **Your own company or studio.** You set the title there, so it can change to fit the role, as long as it's true to the work.
7. **The post's title goes in the file name and, when it fits, the first summary label.** File name: `Firstname Lastname - <Company> (<Role as posted>).pdf`, spelled the way the posting spells it ("Operations", not "Ops").

**Prompt**

```
Check my titles against LinkedIn and my standard resume and keep them the same unless I say otherwise. If you think a different title would get found more for this role, suggest it and tell me why, but don't change it. Flag any internal or level title that a recruiter wouldn't type into a search bar. Use the role exactly as they posted it in the file name, and in the first summary label if it fits.
```

You're done when your titles match LinkedIn and the file name uses the role exactly as posted.

---

## Step 8: Format the page

**Build from your own template, in the .docx first.** Every version starts from your own template .docx, never a made-up layout. If the resume is going to live in Google Docs, convert it afterwards. Right-aligned dates need tab stops, and those don't come through when you build in Google Docs from scratch.

1. **Length:** always one page (step 6)
2. **Font and margins:** whatever your rules file says. Mine is 10pt body in Calibri, but you might want 10.5. Never shrink below the minimum in your rules file to make something fit
3. **Header:** your name, then one contact line: phone • email • LinkedIn. No location. Email and LinkedIn as live links, the phone as plain text
4. **Colour:** one accent colour, only on your name and the section headings. Nothing else is coloured except the links
5. **Section headings:** all caps and bold, with a thin rule the full text width underneath. Make the rule a paragraph bottom border, not a drawn line, so it moves with the text. Set every heading to keep with the next line
6. **Role block:** role title bold on the left with the dates bold and right-aligned on the same line, then the company in italics on the left with the location in italics and right-aligned on the same line, then the bullets
7. **Dates:** an en dash in date ranges (June 2022 – Present). No em dashes anywhere
8. **Summary:** 2 bullets, each opening with a bold label and a colon
9. **Skills:** bulleted, with bold category labels
10. **Education:** school bold on the left, degree right-aligned on the same line
11. **No terminal periods** on any bullet, summary line or skills line
12. **Cold applications through job boards:** keep it simple so the parsing software reads it the way a person would
    - single column
    - no tables
    - standard section headings
    - no text in headers or footers
    - abbreviations spelled out once

**Prompt**

```
Build it in my own template .docx, not a made-up layout, and only move it to Google Docs afterwards if that's where it's going. Format it to my house style from my rules file. That's the body size and margins from my rules file, my name and the section headings in my accent colour with a thin rule under each heading, every heading set to keep with the next line, role title and dates in bold on one line, company and location in italics on the next, email and LinkedIn as live links and the phone as plain text, no location in the header, no periods at the end of bullets, en dashes only in date ranges and no em dashes. If it's a cold application through a job board also keep it single column with no tables and nothing in the header or footer. Then check the version that's going out, not the working copy.
```

You're done when the version that's going out matches your house style.

---

## Step 9: Build, save and check before sending

**Build:** edit the .docx made from your template, then check the version that's going out (the PDF, or the Google Doc if that's where it lives), not the editor view.

**Pre-send checks**

1. One page, checked in the format that's going out
2. Every heading keeps with the next line, so none is stranded at the foot of a page
3. No em dashes, and en dashes only in date ranges
4. Numbers match your canonical table, and look-alike numbers (users vs signups) are never swapped
5. Nothing from the "never write" list
6. Every ★ bullet has your sign-off on the wording, and no ★ shows on the page
7. No client or partner names you're not allowed to share, and no vendor names you've decided to keep off
8. No repeated opening verbs in adjacent bullets, across role boundaries too
9. No terminal periods, no first person, no experience bullet over 2 lines
10. Summary scaffolding untouched, labels and nouns only, and it still has the summary shape from Step 5
11. Header is consistent: name, then one contact line
12. Font no smaller than the minimum in your rules file, and any overflow fixed in order: spacing, then wording, then the weakest bullet
13. Every `[__]` blank still waiting for a number is still highlighted
14. Saved as .docx + .pdf in the company folder under your naming convention, with any older version in `version history/`. In Google Docs, edit the one doc in place instead
15. New bullets added back to the bank, and new facts to your story bank, the same day
16. You see it before it's uploaded or sent
17. After uploading to an application form, check the attached file name and re-check the form. Resume parsers re-fill fields: I've seen long answers emptied and a location field filled from the resume's location line
18. Note which resume went (standard or tailored) so you can compare reply rates later
19. When a recruiter asks for it by message, write the note, attach the PDF and send them together

**Prompt**

```
Before I send it run every pre-send check and tell me which ones passed and which didn't: one page in the format that's going out, nothing below my minimum font size, no ★ on the page, every [__] blank still highlighted, no heading stranded at the bottom of a page, no em dashes, numbers matching my canonical table, nothing from my never-write list, no client names, no repeated opening verbs, no periods or first person, and the summary scaffolding unchanged. Then save the .docx and .pdf to the company folder with the right file name, move any older version to version history, add any new bullets to my bank, and show me the PDF. Don't upload or send anything until I say so.
```

You're done when every check passes and you've seen the PDF.

---

## If your draft lives in Google Docs

This comes up most when you're working on someone else's resume and want to leave them questions.

1. **Build in the .docx first,** then convert it (see Step 8)
2. **Edit in place.** Claude edits that one doc instead of making new copies. Docs already keeps the version history
3. **Recheck highlighted blanks after every edit.** Editing text in Google Docs can strip the highlight from a `[__]` blank that's waiting for a number, and then it's easy to miss
4. **Questions go in as comments,** anchored to the line they're about. One overall comment on the name first, then one per fix
5. **Read the comments back afterwards** and check every anchor landed on the right text. They can land on the wrong line if the page scrolls while you're typing
6. **Check imported docs** for stray rules or empty bullets under the headings

---

## Mistakes I keep catching

1. **Rewriting the summary scaffolding** instead of only the labels and nouns
2. **Reordering while making a swap.** Ask for one swap and get a reorder too. Reorders should be proposed separately
3. **The same opening verb back to back,** often across a role boundary
4. **A stranded heading** at the foot of a page
5. **AI-sounding trailing clauses.** And when one gets fixed on one version, it's often still sitting in the others
6. **Number drift.** A figure from one role creeping into another, or an old master with numbers that contradict the current one
7. **Terminal periods** creeping back
8. **Weak openers** like Caught and Scored
9. **Pointer clauses** that only refer back to something earlier in the bullet
10. **Too much mechanism** that belongs in the interview
11. **Inherited false claims.** A wrong line in one document gets copied into the next ones before anyone checks it
12. **Trusting a filename** to tell you what's inside
13. **Reusing a tailored base without re-weighting it** for the new post
14. **New bullets that lead with the activity** instead of the outcome
15. **Claiming what the post lists but you haven't done**
16. **Tailoring before checking the fit**

---

Something didn't work? [Open an issue](https://github.com/Lily-Tewolde/ai-guides/issues) and tell me what happened.

Made by [Lily Tewolde](https://github.com/Lily-Tewolde). Find me on TikTok at [@lilytewolde](https://www.tiktok.com/@lilytewolde) and on Instagram at [@promptesss](https://www.instagram.com/promptesss).
