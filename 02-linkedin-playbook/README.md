# The 5-Step LinkedIn Playbook

*Updated Nov 2026*

I made this to go with my LinkedIn optimization video. It walks through the same 5 steps, each with a copy-paste Claude prompt, so that:

- recruiters can find you
- you rank higher in LinkedIn search
- more profile views turn into interviews

## At a glance

| | |
|---|---|
| **Difficulty** | Easy, no coding |
| **Time** | One sitting for Steps 1 to 4, then 2 to 3 posts a week |
| **You'll end up with** | A headline, About section, job titles, skills and Featured section recruiters can find, plus 3 weeks of post ideas |

| Step | What you do | Key action |
|---|---|---|
| [1](#step-1-get-searchable-with-your-headline-and-titles) | Headline and titles | Fix search ranking |
| [2](#step-2-turn-your-about-and-experience-into-a-story-with-no-metrics) | About and experience | Story + keywords |
| [3](#step-3-get-into-the-recruiter-filters-with-your-skills-and-open-to-work) | Skills and Open to Work | Get into recruiter filters |
| [4](#step-4-prove-you-ship-with-your-featured-section) | Featured section | Prove you ship |
| [5](#step-5-post-about-your-work) | Post about your work | The step that compounds |
| [Extras](#extras-to-finish-your-profile) | Photo, banner, location, recommendations | Round it out |

## Start here

Download [`linkedin-playbook.md`](linkedin-playbook.md), put it in your job search folder, then paste this into Claude:

```text
Read the LinkedIn Playbook file and update my LinkedIn for [TARGET ROLE]. Here's my profile [LINK OR SCREENSHOTS], my resume and 2 to 3 job posts: [PASTE JOB POSTS]
```

Claude reads your profile, works through the 5 steps and the extras, and writes everything out for you to change yourself. It never edits or posts anything on your profile. If you ran the [Resume Audit](../04-resume-audit/) first, it starts from your new resume and also reads your Bullet Bank.md. Anything it writes from a line still marked ★ waits for your OK, the same as on your resume.

Not using the file? Copy the [master prompt](#the-master-prompt), fill in the brackets and paste it into Claude. Want more control? Go step by step below, so you can review and tweak each part as you go. All three get you to the same place.

### Doing this for someone else

When I ran this on a friend's profile, everything came back written about my friend instead of to them, and they're the one who has to make the changes. So when it's someone else's profile:

- **Write it to them, in your voice.** Second person, like "I picked this headline for you" or "delete these three roles". No AI-looking labels or numbered tags
- **Make change, keep and delete clear.** Mark what to change, leave everything else alone, and cross out what comes off
- **Open or close with a note.** Tell them to adjust anything that seems off. If you're not an expert in their field, say so, and that it's mostly formatting and a strong direction. Claude asks you rather than guessing
- **If you can't answer for them, don't stop.** Give your pick for a choice and leave a `[__]` blank for a fact, mark both for them to check, and carry on
- **Give them a visual mock of the finished profile.** An HTML page laid out like their profile, with your notes beside each section and a switch to hide them, so they can see it the way a recruiter would. Send it as a file, never as a page published online
- **Keep employer and client work out** of Featured and posts unless the employer says it's okay. Client names, photos, documents and anything that isn't public count. What they learned and how they work, with no client named, doesn't. Mark any idea that needs the OK, and tell them to ask their manager first
- **Set Open to Work to Recruiters only while they're still employed,** and tell them why. LinkedIn tries to hide it from their own company's recruiters, but it can't promise it
- **The check is for you.** Claude's list of which checks passed comes after the handoff, addressed to you, so it never gets passed on to them
- **Keep their details private.** They stay in their own folder, never go into a public repo, an issue or a shared doc without them knowing, and any example you share about what you learned is made up

## What you need

- Claude (any plan)
- The Claude desktop app with Cowork, if you're using the file (Claude Code works too)
- The [`linkedin-playbook.md`](linkedin-playbook.md) file from this folder, if you're using it
- Your resume, plus your Bullet Bank.md if you ran the Resume Audit first
- A link to your LinkedIn profile, or screenshots of it: header, About, every role, education, projects, skills and Featured. Claude reads the live profile when it can open it in your browser, and the screenshots are the fallback
- 2 to 3 real job posts for the role you want. Claude pulls your keywords from them, so they match what companies are actually asking for
- A few facts later steps need, so Claude asks once: the city you live in or are moving to, whether you're still employed, whether unrelated roles like seasonal work should stay and their months, remote and employment types for Open to Work, whether your employer is OK with your work being shown, every language you speak and your level, what each award is, each certification's issuing organization and whether it's still in progress, why any role came off your resume if your Decision Log doesn't say, and, if it's someone else's profile, whether you work in their field

Run all 5 prompts in **one** Claude conversation, not five separate chats. Steps 2 to 5 say "above" because they build on the resume, profile and job posts you share in Step 1.

---

## Step 1. Get searchable with your headline and titles

Your headline is the most important field on your whole profile. It's what LinkedIn ranks you on in search. Write it as your role, three keywords, then your best credential, all under 100 characters. While you're in there, fix every job title to match what recruiters actually type. If yours says Growth Lead or IC4 but recruiters are searching Marketing Manager, you don't exist in their results.

**Why it matters:** LinkedIn's search weights your headline more than any other field. A creative title that doesn't match a real search term means your profile never shows up, no matter how strong the rest of it is.

**What to do**

- Rewrite your headline: `[Your Role] + 3 keywords + your best credential`, under 100 characters. LinkedIn lets you use 220, but only about the first 100 show in search and on mobile, so keep the important part up front
- Use your target role, the way recruiters search it
- Only use a credential that's real: a licence or certification you hold, a well-known employer or something you shipped. Never a degree, and never a certification you're still working on. If you don't have one yet, leave that part off, and vary the role the way recruiters search it so the options really differ
- Never go over 100 characters. If it runs over, shorten the credential to the form people search, then drop to two keywords, like `Event Coordinator | Vendor Logistics · Run-of-Show | Food Safety Certified`
- Swap any internal, advisory or creative job title for the standard title recruiters search

**Prompt**

```text
You're a LinkedIn SEO and recruiter-search expert. I'm targeting the role of [YOUR TARGET ROLE, e.g. Marketing Manager]. Here's my resume: [PASTE RESUME]. Here's my current LinkedIn profile, as a link or screenshots: [LINK OR SCREENSHOTS]. Here are 2-3 real job posts for this role: [PASTE JOB POSTS].

1. Give me 5 headline options, each under 100 characters, in this exact format:
Role | Keyword · Keyword · Keyword | Credential
Use the keywords that show up in these job posts and that a recruiter would actually search to find someone in my field. No buzzwords, no metrics. Only use a licence or certification I hold, a well-known employer or something I shipped, never a degree or one I'm still working on. If I have none, leave it off and vary the role so the options really differ. If one runs over 100 characters, shorten the credential, then drop to two keywords.

2. Review every job title on my profile. Flag any that are vague, internal, or "creative" (like Marketing Ninja or Customer Happiness Hero) and tell me the standard title recruiters actually search for instead.
```

You're done when your headline is under 100 characters and every job title is one a recruiter would search.

---

## Step 2. Turn your About and experience into a story, with no metrics

This one's going to feel wrong, but trust me. Your About section is a story, not a summary. No bullet points, no metrics. Write it like you're explaining your career to someone at dinner who actually asked. Same for every role. Then take every metric off your profile and save the numbers for your resume and interviews. A recruiter scans you in about seven seconds, and a story with the right keywords is easier to take in than a wall of stats.

**Why it matters:** Bullet-point profiles full of metrics read like a copy of your resume. Recruiters scan for keywords and credibility.

**What to do**

- Rewrite your About as a story in 4 to 6 short paragraphs:
  - an opening hook, from real work you've done
  - your career thread
  - your current work and how you work
  - one line on what you want next
- Early in your career? Open on the work you do now, then your thread, then how you work
- Keep every line of your About to what you've said or done. If Claude would be guessing, like why you changed paths or what you enjoy, it goes on the "add only if true" list for you to confirm
- Rewrite each job and project as one short paragraph, then Focus Areas:
  - Each one is the skill a recruiter searches, then the specifics in brackets
  - The wording comes from the job posts' requirements and responsibilities, and only where it's work you've actually done
  - 4 to 12 for a role that matters for where you're going, depending on how much
  - 0 to 3 for a role far from it that you keep with a description, like seasonal work or a box office job before an events career, in the words someone hiring for that work would search
  - 2 to 4 for a project
  - None for an unrelated role you keep with no description
  - Never pad to hit a number. If you've only done three things in a role, three is right, and Claude tells you why it stopped there
  - Claude says which roles it counted as far from your target, so you can check
  - Anything the posts ask for that you haven't done goes on a separate "add only if true" list, never on your profile
- Remove every number from your profile and posts, even ones that aren't results. The examples are made up:
  - a team size in a project description counts
  - spelled-out numbers and ordinals count, so "1st Place" becomes "Winner" and "2nd Place" becomes "Runner-up"
  - job post wording loses its numbers when you reuse it, so "respond within one business day" becomes "fast client replies"
  - the dates on your entries are fine, and so is a licence or certification's official name, even with a number in it
  - media like a PDF, video or screenshot keeps its numbers, since it's the proof. Just don't quote them in the words around it

My Focus Areas carry a lot more context than a keyword list. Example, made up:

- Event logistics (vendor contracts, venue sourcing, run-of-show planning)
- Budget tracking (spend reports, invoice reconciliation, cost forecasts)

A school project gets the same, after its own short paragraph, like "Event logistics (venue booking, vendor schedule, run-of-show)".

And an About line, made up: not "I've always loved bringing people together", which nobody said, but "On an event day I'm the one with the run-of-show, making sure every vendor arrives when they should."

**Prompt**

```text
Using my resume and LinkedIn profile above, and targeting [YOUR TARGET ROLE], rewrite two things:

1. My About section as a STORY, not a summary. 4 to 6 short paragraphs:
- An opening hook, from real work I've done
- The thread connecting my career
- What I do now and how I work
- One line on what I'm open to next
If I'm early in my career, open on the work I do now, then the thread, then how I work. Only use what I've told you or what's on my resume and profile. Anything you'd be guessing, like why I changed paths or what I enjoy, goes on a separate "add only if true" list for me to confirm. No bullet points, no metrics. Weave in the keywords a recruiter searches for, but keep it sounding like a real person talking.

2. Each of my jobs and projects as one short narrative paragraph (what I owned and how I worked), followed by Focus Areas: 4 to 12 for a role that matters for where I'm going, 0 to 3 for a role far from it, 2 to 4 for a project, and none for an unrelated role I keep with no description. Write each one as the skill a recruiter searches, then the specifics in brackets, like "Event logistics (vendor contracts, venue sourcing, run-of-show planning)". Take the wording from the requirements and responsibilities in the job posts above, but only where it's work I've actually done. For a role far from my target, use the words someone hiring for that work would search instead, and tell me which roles you counted as far. Never pad to hit a number. If a role has fewer than its range, use fewer and tell me why. Put anything the posts ask for that I haven't confirmed on the "add only if true" list too, not on the profile. No numbers anywhere, not even a team size, a spelled-out number, an ordinal like "1st", or a number in job post wording you reuse. The dates on my entries are fine, and so is a certification's official name. Media I attach, like a PDF or screenshot, keeps its own numbers, so don't tell me to blur them, just don't quote them. Write for a recruiter scanning for 7 seconds.
```

You're done when your About reads like a story, every role and project has its Focus Areas, and there are no numbers left in anything written on your profile, apart from your entry dates.

---

## If you're early in your career

When I ran this on a friend's early career profile, I had to decide on my own what to do with Projects, Education, Licenses and Honors, because the 5 steps don't cover them. LinkedIn also doesn't let you move sections around, so the Projects section always sits low on the page. Here's what I'd do:

1. **Experience is for real jobs.** Decide whether unrelated roles, like seasonal or part-time work, stay or go. If you're not sure, keep them with no description. School projects never go in Experience
2. **One Education entry per degree you actually earned.** No description or Focus Areas. An earlier program that didn't lead to the degree comes off, and your About can mention it instead. Why you switched goes in only if you've said
3. **Projects stay in the Projects section.** Give each one a short paragraph and 2 to 4 Focus Areas, like a job (see Step 2). Link each one to your school with "Associated with", tag the skills you used, and add media once you have it
4. **Featured is how a project gets seen first,** since the Projects section can't be moved up
5. **Licenses & certifications.** Add any you hold, with the issuing organization. Recruiters filter by them. One you're still working on stays off until you've earned it, and your About can say you're working toward it
6. **Honors & awards.** Look up what each award is first, or say what it was for. Keep the ones that are rare, competitive or in your field. Dean's List, general scholarships and other general honours are your call, the same as on your resume, though I'd cut general scholarships for entry-level roles. This is broader than the Resume Audit's test on purpose, since LinkedIn has room
7. **Your About matches the level you're aiming for.** Open on the work you do now, then your thread, then how you work. Use school work as evidence, not as a chapter in school-to-job order

---

## Step 3. Get into the recruiter filters with your skills and Open to Work

This is the behind-the-scenes one nobody talks about. LinkedIn lets you tag five Top skills at the bottom of your About section, and recruiters filter by skills when they search. So pick the five they're actually typing, not the ones that sound impressive. Then turn on Open to Work, add your five target titles and set it to recruiters only if you're still employed. If you leave a box empty, you won't show up in the searches that use it.

**Why it matters:** LinkedIn Recruiter filters by skills and job titles. If yours don't match what a recruiter is filtering for, you won't show up, even if you're a perfect fit.

**What to do**

- Add 5 Top skills to your About section (click the pencil on About), using the ones recruiters in your field filter by most
- Put those same 5 first in your Skills section too, since only the first few show without clicking
- Tag the exact skills on every experience, education and project entry, using the names recruiters actually search. "+4 skills" isn't something you can act on, so get the list for each one
- Add each skill by typing it in and picking LinkedIn's exact match from the dropdown. If it doesn't come up, pick the closest suggestion
- Only tag skills you actually used in that role or project
- Prune your Skills section. Remove the skills that don't fit your target role, but keep all the software and tools you've actually used. Anything you've never used comes off
- Turn on Open to Work
- Add 5 target job titles. If your job posts give fewer, add close ones recruiters search, and Claude marks which ones are its picks
- Set Remote and the employment types you want. Don't leave them blank
- Set visibility to Recruiters only if you're still employed. LinkedIn tries to hide it from your own company's recruiters, but it can't promise it

**Prompt**

```text
For someone targeting [YOUR TARGET ROLE] in [YOUR INDUSTRY], using my resume, profile and the job posts above, tell me:

1. The exact 5 skills I should add as my Top skills on LinkedIn, ranked by how often each one shows up across the job posts. You can't see LinkedIn's search data, so say that's where the ranking comes from. Count each skill once per post, group synonyms under the name recruiters search, and in a tie put must-haves first. Skip any skill I don't have. Pick what the posts ask for, not what sounds most impressive.

2. For every experience, education and project entry on my profile, the exact skills to tag on it, using the names recruiters search. Only skills I actually used in that role or project.

3. Which skills in my Skills section to remove because they don't fit this role, or because I've never used them. Keep all the software and tools I've actually used.

4. The 5 job titles I should enter in LinkedIn's Open to Work settings to appear in the most relevant recruiter searches, plus whether I should turn on Remote and which employment types to select. If the posts give fewer than 5 titles, add close ones recruiters search and say which are your picks.
```

You're done when your About has 5 Top skills, every entry has its skills tagged, and Open to Work has 5 titles and is set to Recruiters only if you're still employed.

---

## Step 4. Prove you ship with your Featured section

This is the first thing a recruiter clicks after your headline, and almost everyone leaves it empty. Don't. Put one thing here that proves you do the work, like:

- a quick video walking through something you built
- a post that did well
- a live tool
- a portfolio link

One strong piece is enough.

**Why it matters:** Featured is where profile views turn into messages or drop off. An empty one says there's nothing to point to.

**What to do**

- Add at least one Featured item that shows something real you built or shipped
- Keep employer and client work out of Featured and your posts unless your employer says it's okay
- Best: a 2 to 3 minute video walking through a live product, tool or project
- Also good: a strong post in your field, a live tool anyone can use, or a portfolio or case study link

**Prompt**

```text
I want to fill my LinkedIn Featured section to prove I actually do the work for [YOUR TARGET ROLE]. Based on my background above, give me 3 specific Featured ideas I could realistically create in under 2 hours each, ranked by how much they'd impress a recruiter.

For each idea:
- Tell me exactly what it should contain
- Explain why it works as a credibility signal
- Tell me how to create it (what tool, format, or platform to use)
```

You're done when your Featured section has at least one thing you built or shipped.

---

## Step 5. Post about your work

Don't skip this one. Post about your actual work two to three times a week. This is the step that compounds. It took my search appearances from around 40 a week to over 200 in a month, and it's how recruiters start showing up in your inbox.

**Why it matters:** Posting regularly about your field lifts your search appearances and shows both the algorithm and recruiters that you know your stuff.

**What to do**

- Post 2 to 3 times a week about your real work, not generic career advice
- Use Claude to plan 3 weeks of posts from your actual experience
- Every first line comes from your real work. If Claude would have to guess, like why you changed paths, it uses your real work instead and asks you
- No numbers in your posts either, first lines included, so a made-up "My first 3 months running vendor check-in" becomes "What running vendor check-in taught me". A screenshot or PDF you attach keeps its own
- Keep employer and client work out unless your employer says it's okay. Client names, photos, documents and anything that isn't public count. What you learned and how you work, with no client named, is fine
- If an idea needs your employer's OK, ask your manager first

**Prompt**

```text
I'm targeting [YOUR TARGET ROLE] and want to start posting on LinkedIn. Give me 9 post ideas (3 weeks, 3 posts each) based on my real experience above.

Mix these three formats across the 9 posts:
- A lesson I've learned from real work experience
- A behind-the-scenes look at how I actually approach my work
- A simple tip or framework from my field

For each post:
- Give me a scroll-stopping first line, built only from what I've told you or what's on my resume. If it would need a guess, like why I changed paths, use my real work instead and ask me
- No numbers in the text, first line included, spelled out or as ordinals
- Keep it specific to my actual work and field
- No generic career advice
- Keep employer and client work out (client names, photos, documents, anything not public) unless my employer says it's OK. Mark any idea that needs that OK with "ask your manager first"
```

You're done when you have 9 post ideas and your first post is up.

---

## Extras to finish your profile

These aren't part of the 5 steps, but they round out your profile. I adapted them from Param Choudhary's [linkedin-profile-optimizer](https://github.com/Paramchoudhary/ResumeSkills/tree/main/skills/linkedin-profile-optimizer) skill (MIT).

### Photo and banner

It's the first thing people see on your profile, before they read anything.

- **Photo:** a clear headshot where your face fills most of the frame. Good light, a plain or on-brand background, and dressed the way you would for work in your field
- **Banner:** 1584 × 396 pixels. Use it to say what you do, or keep it simple and on brand. Skip anything busy that fights with your photo

### Profile basics recruiters filter by

When I compared a friend's profile with mine, most of the gaps weren't in the 5 steps at all. They were basics like these:

- **Location is a city,** not just a country: the one you live in, or the one you're moving to. Recruiters filter by city
- **Get the verification badge,** with a work email or ID
- **Add media to your entries,** like a link, PDF or video on the role or project it belongs to. It keeps its numbers, but don't quote them in the words around it
- **Languages:** add every one you speak, at your real level
- **Connections:** grow them at your current company, your school and the companies you're applying to

### Recommendations

A few recommendations from people who actually worked with you go a long way. Aim for 5 to 10 over time.

- **Who to ask:** former managers, teammates you worked closely with, and clients
- **Give one first.** People are way more likely to write one back
- **Make it easy.** Tell them the project or skill you'd love them to mention
- **Time it right.** Ask right after you've wrapped something good together

**Prompt**

```text
Write a short, friendly LinkedIn message asking [NAME] for a recommendation. We worked together at [COMPANY] on [PROJECT]. I'm targeting [YOUR TARGET ROLE], so I'd love them to mention [1 TO 2 SKILLS OR MOMENTS]. Keep it casual, under 80 words, and don't make it sound like a template.
```

### Keep your resume and LinkedIn in sync

A recruiter will have both open. If they don't match, that's a question you didn't want them asking.

- **Same job titles and dates** on both, every time. LinkedIn needs a month and year, so seasonal work like "Summers 2023 – 2024" goes in as its first and last months, with Seasonal as the employment type. That's not a mismatch
- **A role your resume cut only to fit the page or one post can stay on LinkedIn,** with the same title, company and dates as your standard resume. That's not a mismatch either
- **Same skills and tools, both ways.** If your About or Skills mention software that isn't on your resume, or the other way around, decide which one changes, or keep both as they are. Basic tools like Word, Google Docs or Excel can be on LinkedIn without being on your resume
- **Same story, told two ways.** LinkedIn can be longer and more conversational than your resume
- **The numbers stay on your resume** (see Step 2)

**Prompt**

```text
Compare my resume to my LinkedIn above. List every place where a job title, company name or date doesn't match exactly, and tell me which one to change so they line up. Seasonal work entered as its first and last months, with Seasonal as the employment type, counts as a match, and so does a role my resume cut only to fit the page or one post that I keep on LinkedIn with the same title, company and dates as my standard resume. Then list every skill or tool that's on one but not the other, in both directions, except basic tools like Word, Google Docs or Excel, which can be on LinkedIn only. For each one, let me decide which side changes, or keep both as they are. Don't rewrite anything else.
```

You're done when your photo and banner are up, your location is a city, you've asked for at least one recommendation, and your titles and dates match your resume, except where they differ on purpose.

---

## The master prompt

Fill in every bracket, attach your resume and your profile link or screenshots, and paste it into Claude.

```text
You're a LinkedIn growth strategist and recruiter-search expert.

Optimize my LinkedIn profile so that:
1. Recruiters searching for [YOUR TARGET ROLE] find me in search
2. My profile ranks higher in LinkedIn search results
3. My profile converts views into recruiter messages and interviews

STEP 1 - MY INPUTS
Here's my resume: [PASTE RESUME TEXT OR ATTACH PDF]
Here's my LinkedIn, as a link or screenshots: [LINK, OR ATTACH: header, about, every role, education, projects, skills, featured]
Here are 2-3 real job posts for my target role: [PASTE JOB POSTS]

STEP 2 - TARGETING
I'm targeting this role: [YOUR TARGET ROLE] (e.g. Marketing Manager, Project Manager, Account Executive)
Industries I'm targeting: [LIST YOUR TARGET INDUSTRIES]
Company type: [STARTUP / ENTERPRISE / BOTH]
My strongest credential: [LICENCE OR CERTIFICATION I HOLD, NOTABLE EMPLOYER, OR SOMETHING I SHIPPED, NOT A DEGREE OR ONE IN PROGRESS]
Facts for later steps: [CITY I LIVE IN OR AM MOVING TO, WHETHER I'M STILL EMPLOYED, REMOTE AND EMPLOYMENT TYPES, WHETHER MY EMPLOYER IS OK WITH MY WORK BEING SHOWN, LANGUAGES AND LEVELS]
My technical or domain skills: [LIST THE TOOLS AND SKILLS YOU ACTUALLY USE]
My biggest results, for your context only, not for LinkedIn: [LIST 3-5 METRICS YOU WILL SAVE FOR INTERVIEWS]

STEP 3 - WHAT TO PRODUCE
1. HEADLINE (5 options)
Format: [Role] | [Keyword] · [Keyword] · [Keyword] | [Credential]
Under 100 characters, never over. If one runs long, shorten the credential, then drop to two keywords. No metrics. The credential has to be real, never a degree or a certification I'm still working on. If I don't have one, leave it off and vary the role so the options really differ.

2. TITLE AUDIT
Flag titles that don't match real recruiter search terms. Suggest the functional replacement for each.

3. ABOUT SECTION
Story-driven, 4 to 6 paragraphs, no metrics, no bullets. Structure: Hook from my real work, Career thread, Current work and how I work, What I want next. If I'm early in my career, open on the work I do now, then the thread, then how I work. Only use what I've told you or what's on my resume and profile. Anything you'd be guessing, like why I changed paths, goes on the "add only if true" list.

4. ALL EXPERIENCE ROLES AND PROJECTS
Each role or project: one narrative paragraph, then Focus Areas. 4 to 12 for a role that matters for my target, 0 to 3 for a role far from it, 2 to 4 for a project, and none for an unrelated role I keep with no description. Never pad to hit a number. If a role has fewer than its range, use fewer and tell me why. Each Focus Area is the skill a recruiter searches, then the specifics in brackets, worded from the job posts and only for work I've actually done, like "Event logistics (vendor contracts, venue sourcing, run-of-show planning)". For a role far from my target, use the words someone hiring for that work would search, and tell me which roles you counted as far. No numbers of any kind, including spelled-out numbers, ordinals and numbers in job post wording you reuse. A certification keeps its official name, and media I attach keeps its own numbers. Anything the posts ask for that I haven't confirmed goes on a separate "add only if true" list, not the profile.

5. SKILLS
Top 5 to pin, ranked by how often each one shows up across the job posts, counting once per post, with synonyms grouped and must-haves first in a tie, skipping any skill I don't have (you can't see LinkedIn's search data, so say so). Then the exact skills to tag on every experience, education and project entry, only ones I used there, and which skills to remove from my Skills section. Keep all the software and tools I've actually used, and remove any I haven't.

6. OPEN TO WORK SETTINGS
5 titles to enter, with your picks marked if the posts give fewer. Location types and employment types, never blank.

7. FEATURED SECTION IDEAS
3 ideas I can create in under 2 hours. Ranked by impact. No employer or client work unless my employer says it's OK.

8. 9 POST IDEAS (3 weeks of content)
3 per week: lesson learned, behind the scenes, tip or framework. One scroll-stopping first line per post, built only from what I've told you or what's on my resume. If one would need a guess, like why I changed paths, use my real work instead and ask me. No numbers in any post. No employer or client work, like client names, photos, documents or anything that isn't public, unless my employer says it's OK. Mark any idea that needs that OK with "ask your manager first".

9. PROFILE BASICS
Location set to my city, every language at my real level, and Open to Work set to Recruiters only if I'm still employed.

CONSTRAINTS
No generic career advice. No numbers anywhere in LinkedIn copy or posts, spelled out or as ordinals, except entry dates. Media I attach keeps its own, but don't quote it. Write for a recruiter scanning for 7 seconds.
```

### What to fill in

Be as specific as you can, so Claude has more to work with.

| Bracket | What to put |
|---|---|
| `[YOUR TARGET ROLE]` | The role you want most, as recruiters search it, not an internal label. E.g. Marketing Manager, Project Manager, Account Executive, Software Engineer |
| `[PASTE JOB POSTS]` | 2 to 3 real job posts for your target role. Copy the full text, not just the link |
| `[YOUR TARGET INDUSTRIES]` | Where you want to work. E.g. SaaS startups, healthcare tech, financial services, consumer apps |
| `[STARTUP / ENTERPRISE / BOTH]` | Helps Claude pick the right tone and keywords |
| `[CERTIFICATION / EMPLOYER]` | Your strongest credibility anchor: a licence or certification you hold, a well-known employer or something you shipped. Not a degree, and not a certification you're still working on |
| `[CITY ... LANGUAGES AND LEVELS]` | The city you live in or are moving to, whether you're still employed, the remote and employment types you want, whether your employer is OK with your work being shown, and every language you speak at your level |
| `[TOOLS AND SKILLS YOU USE]` | Every tool and skill you could talk about in an interview |
| `[3-5 METRICS]` | Your real numbers, for context only. They won't show up on LinkedIn, but they help Claude understand your level |

## Tips and watch outs

💡 **Keep it all in one chat.** Steps 2 to 5 build on what you shared in Step 1. A new chat means starting over.

💡 **Step 3's Top 5 works on its own.** You can ask for it without your resume for a quick answer. The skills for each entry need your profile, so keep that part in the same chat.

💡 **Share more detail for better ideas.** Featured and post ideas land much better when Claude knows your actual background.

⚠️ **Don't skip the job posts.** Claude can't see LinkedIn's search data, so the job posts you paste are what make its keyword picks real.

⚠️ **No numbers on LinkedIn.** Save your metrics for your resume and interviews. Give them to Claude for context only.

⚠️ **Looking for Creator Mode?** LinkedIn retired it in 2024. Everyone has the Follow button now, so posting does the work.

---

Something didn't work? [Open an issue](https://github.com/Lily-Tewolde/ai-guides/issues) and tell me what happened.

Made by [Lily Tewolde](https://github.com/Lily-Tewolde). Find me on TikTok at [@lilytewolde](https://www.tiktok.com/@lilytewolde) and on Instagram at [@promptesss](https://www.instagram.com/promptesss).
