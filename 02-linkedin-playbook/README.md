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

Claude reads your profile, works through the 5 steps and the extras, and writes everything out for you to change yourself. It never edits or posts anything on your profile. If you ran the [Resume Audit](../04-resume-audit/) first, it starts from your new resume.

Not using the file? Copy the [master prompt](#the-master-prompt), fill in the brackets and paste it into Claude. Want more control? Go step by step below, so you can review and tweak each part as you go. All three get you to the same place.

### Doing this for someone else

When I ran this on a friend's profile, everything came back written about my friend instead of to them, and they're the one who has to make the changes. So when it's someone else's profile:

- **Write it to them, in your voice.** Second person, like "I picked this headline for you" or "delete these three roles". No AI-looking labels or numbered tags
- **Make change, keep and delete clear.** Mark what to change, leave everything else alone, and cross out what comes off
- **Say you're not an expert in their field.** Open or close with it: it's mostly formatting and a strong direction, so they should adjust anything that seems off
- **Give them a visual mock of the finished profile.** An HTML page laid out like their profile, with your notes beside each section and a switch to hide them, so they can see it the way a recruiter would. Send it as a file, never as a page published online
- **Keep employer and client work out** of Featured and posts unless the employer says it's okay
- **Set Open to Work to Recruiters only while they're still employed,** and tell them why. LinkedIn tries to hide it from their own company's recruiters, but it can't promise it
- **Keep their details private.** They stay in their own folder, never go into a public repo, an issue or a shared doc without them knowing, and any example you share about what you learned is made up

## What you need

- Claude (any plan)
- The Claude desktop app with Cowork, if you're using the file (Claude Code works too)
- The [`linkedin-playbook.md`](linkedin-playbook.md) file from this folder, if you're using it
- Your resume
- A link to your LinkedIn profile, or screenshots of it: header, About, every role, education, projects, skills and Featured. Claude reads the live profile when it can open it in your browser, and the screenshots are the fallback
- 2 to 3 real job posts for the role you want. Claude pulls your keywords from them, so they match what companies are actually asking for

Run all 5 prompts in **one** Claude conversation, not five separate chats. Steps 2 to 5 say "above" because they build on the resume, profile and job posts you share in Step 1.

---

## Step 1. Get searchable with your headline and titles

Your headline is the most important field on your whole profile. It's what LinkedIn ranks you on in search. Write it as your role, three keywords, then your best credential, all under 100 characters. While you're in there, fix every job title to match what recruiters actually type. If yours says Growth Lead or IC4 but recruiters are searching Marketing Manager, you don't exist in their results.

**Why it matters:** LinkedIn's search weights your headline more than any other field. A creative title that doesn't match a real search term means your profile never shows up, no matter how strong the rest of it is.

**What to do**

- Rewrite your headline: `[Your Role] + 3 keywords + your best credential`, under 100 characters. LinkedIn lets you use 220, but only about the first 100 show in search and on mobile, so keep the important part up front
- Use your target role, the way recruiters search it
- Only use a credential you actually hold, like a licence or certification you've earned. If you don't have one yet, leave that part off
- Swap any internal, advisory or creative job title for the standard title recruiters search

**Prompt**

```text
You're a LinkedIn SEO and recruiter-search expert. I'm targeting the role of [YOUR TARGET ROLE, e.g. Marketing Manager]. Here's my resume: [PASTE RESUME]. Here's my current LinkedIn profile, as a link or screenshots: [LINK OR SCREENSHOTS]. Here are 2-3 real job posts for this role: [PASTE JOB POSTS].

1. Give me 5 headline options, each under 100 characters, in this exact format:
Role | Keyword · Keyword · Keyword | Credential
Use the keywords that show up in these job posts and that a recruiter would actually search to find someone in my field. No buzzwords, no metrics. Only use a credential I actually hold.

2. Review every job title on my profile. Flag any that are vague, internal, or "creative" (like Marketing Ninja or Customer Happiness Hero) and tell me the standard title recruiters actually search for instead.
```

You're done when your headline is under 100 characters and every job title is one a recruiter would search.

---

## Step 2. Turn your About and experience into a story, with no metrics

This one's going to feel wrong, but trust me. Your About section is a story, not a summary. No bullet points, no metrics. Write it like you're explaining your career to someone at dinner who actually asked. Same for every role. Then take every metric off your profile and save the numbers for your resume and interviews. A recruiter scans you in about seven seconds, and a story with the right keywords is easier to take in than a wall of stats.

**Why it matters:** Bullet-point profiles full of metrics read like a copy of your resume. Recruiters scan for keywords and credibility.

**What to do**

- Rewrite your About as a story in 4 to 6 short paragraphs:
  - an opening hook
  - your career thread
  - your current work
  - one line on what you want next
- Rewrite each job as one short paragraph, then Focus Areas:
  - Each one is the skill a recruiter searches, then the specifics in brackets
  - The wording comes from the job posts' requirements and responsibilities, and only where it's work you've actually done
  - 4 to 12 per role, depending on how much that role matters for where you're going
  - Anything the posts ask for that you haven't done goes on a separate "add only if true" list, never on your profile
- Remove every number from every section, even ones that aren't results, like a team size in a project description. The dates on your entries are fine

My Focus Areas carry a lot more context than a keyword list. Example, made up:

- Event logistics (vendor contracts, venue sourcing, run-of-show planning)
- Budget tracking (spend reports, invoice reconciliation, cost forecasts)

**Prompt**

```text
Using my resume and LinkedIn profile above, and targeting [YOUR TARGET ROLE], rewrite two things:

1. My About section as a STORY, not a summary. 4 to 6 short paragraphs:
- An opening hook
- The thread connecting my career
- What I do now and how I think about the work
- One line on what I'm open to next
No bullet points, no metrics. Weave in the keywords a recruiter searches for, but keep it sounding like a real person talking.

2. Each of my job descriptions as one short narrative paragraph (what I owned and how I worked), followed by 4 to 12 Focus Areas, depending on how much the role matters for where I'm going. Write each one as the skill a recruiter searches, then the specifics in brackets, like "Event logistics (vendor contracts, venue sourcing, run-of-show planning)". Take the wording from the requirements and responsibilities in the job posts above, but only where it's work I've actually done. Put anything the posts ask for that I haven't confirmed on a separate "add only if true" list for me, not on the profile. No numbers anywhere, not even a team size. Write for a recruiter scanning for 7 seconds.
```

You're done when your About reads like a story, every role has its Focus Areas, and there are no numbers left anywhere on your profile.

---

## If you're early in your career

When I ran this on a friend's early career profile, I had to decide on my own what to do with Projects, Education, Licenses and Honors, because the 5 steps don't cover them. LinkedIn also doesn't let you move sections around, so the Projects section always sits low on the page. Here's what I'd do:

1. **Experience is for real jobs.** Decide whether unrelated roles, like seasonal or part-time work, stay or go. School projects never go in Experience
2. **One Education entry per degree you actually earned.** No description or Focus Areas. An earlier program that didn't lead to the degree comes off, and your About tells that story instead
3. **Projects stay in the Projects section.** Link each one to your school with "Associated with", tag the skills you used, and add media once you have it
4. **Featured is how a project gets seen first,** since the Projects section can't be moved up
5. **Licenses & certifications.** Add any you hold. Recruiters filter by them
6. **Honors & awards.** Look up what each award is first. Keep the ones that are rare, competitive or in your field. Cut general scholarships for entry-level roles
7. **Your About matches the level you're aiming for.** Lead with the work you do now and what your background adds. Use school work as evidence, not as a chapter in school-to-job order

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
- Add 5 target job titles
- Turn on Remote if you want it
- Set visibility to Recruiters only if you're still employed. LinkedIn tries to hide it from your own company's recruiters, but it can't promise it

**Prompt**

```text
For someone targeting [YOUR TARGET ROLE] in [YOUR INDUSTRY], using my resume, profile and the job posts above, tell me:

1. The exact 5 skills I should add as my Top skills on LinkedIn, ranked by how often each one shows up across the job posts. You can't see LinkedIn's search data, so say that's where the ranking comes from. Pick what the posts ask for, not what sounds most impressive.

2. For every experience, education and project entry on my profile, the exact skills to tag on it, using the names recruiters search. Only skills I actually used in that role or project.

3. Which skills in my Skills section to remove because they don't fit this role, or because I've never used them. Keep all the software and tools I've actually used.

4. The 5 job titles I should enter in LinkedIn's Open to Work settings to appear in the most relevant recruiter searches, plus whether I should turn on Remote and which employment types to select.
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

**Prompt**

```text
I'm targeting [YOUR TARGET ROLE] and want to start posting on LinkedIn. Give me 9 post ideas (3 weeks, 3 posts each) based on my real experience above.

Mix these three formats across the 9 posts:
- A lesson I've learned from real work experience
- A behind-the-scenes look at how I actually approach my work
- A simple tip or framework from my field

For each post:
- Give me a scroll-stopping first line
- Keep it specific to my actual work and field
- No generic career advice
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

- **Location is a city,** not just a country. Recruiters filter by city
- **Get the verification badge,** with a work email or ID
- **Add media to your entries,** like a link, PDF or video on the role or project it belongs to
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

- **Same job titles and dates** on both, every time
- **Same skills and tools, both ways.** If your About or Skills mention software that isn't on your resume, or the other way around, decide which one changes
- **Same story, told two ways.** LinkedIn can be longer and more conversational than your resume
- **The numbers stay on your resume** (see Step 2)

**Prompt**

```text
Compare my resume to my LinkedIn above. List every place where a job title, company name or date doesn't match exactly, and tell me which one to change so they line up. Then list every skill or tool that's on one but not the other, in both directions, and let me decide which side changes. Don't rewrite anything else.
```

You're done when your photo and banner are up, your location is a city, you've asked for at least one recommendation, and your titles and dates match your resume.

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
My strongest credential: [CERTIFICATION, NOTABLE EMPLOYER, OR ACHIEVEMENT]
My technical or domain skills: [LIST THE TOOLS AND SKILLS YOU ACTUALLY USE]
My biggest results, for your context only, not for LinkedIn: [LIST 3-5 METRICS YOU WILL SAVE FOR INTERVIEWS]

STEP 3 - WHAT TO PRODUCE
1. HEADLINE (5 options)
Format: [Role] | [Keyword] · [Keyword] · [Keyword] | [Credential]
Under 100 characters. No metrics.

2. TITLE AUDIT
Flag titles that don't match real recruiter search terms. Suggest the functional replacement for each.

3. ABOUT SECTION
Story-driven, 4 to 6 paragraphs, no metrics, no bullets. Structure: Hook, Career thread, Current work, What I want next.

4. ALL EXPERIENCE ROLES
Each role: one narrative paragraph, then 4 to 12 Focus Areas depending on how much the role matters for my target. Each Focus Area is the skill a recruiter searches, then the specifics in brackets, worded from the job posts and only for work I've actually done, like "Event logistics (vendor contracts, venue sourcing, run-of-show planning)". No numbers of any kind. Anything the posts ask for that I haven't confirmed goes on a separate "add only if true" list, not the profile.

5. SKILLS
Top 5 to pin, ranked by how often each one shows up across the job posts (you can't see LinkedIn's search data, so say so). Then the exact skills to tag on every experience, education and project entry, only ones I used there, and which skills to remove from my Skills section. Keep all the software and tools I've actually used, and remove any I haven't.

6. OPEN TO WORK SETTINGS
5 titles to enter, location types, employment types.

7. FEATURED SECTION IDEAS
3 ideas I can create in under 2 hours. Ranked by impact.

8. 9 POST IDEAS (3 weeks of content)
3 per week: lesson learned, behind the scenes, tip or framework. One scroll-stopping first line per post.

CONSTRAINTS
No generic career advice. No metrics anywhere in LinkedIn copy. Write for a recruiter scanning for 7 seconds.
```

### What to fill in

Be as specific as you can, so Claude has more to work with.

| Bracket | What to put |
|---|---|
| `[YOUR TARGET ROLE]` | The role you want most, as recruiters search it, not an internal label. E.g. Marketing Manager, Project Manager, Account Executive, Software Engineer |
| `[PASTE JOB POSTS]` | 2 to 3 real job posts for your target role. Copy the full text, not just the link |
| `[YOUR TARGET INDUSTRIES]` | Where you want to work. E.g. SaaS startups, healthcare tech, financial services, consumer apps |
| `[STARTUP / ENTERPRISE / BOTH]` | Helps Claude pick the right tone and keywords |
| `[CERTIFICATION / EMPLOYER]` | Your strongest credibility anchor: a well-known employer, a certification or something you shipped |
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

Something didn't work? [Open an issue](https://github.com/Lily-Tewolde/ai-guides/issues/new?template=something-didnt-work.yml) and tell me what happened.

Made by [Lily Tewolde](https://github.com/Lily-Tewolde). Find me on TikTok at [@lilytewolde](https://www.tiktok.com/@lilytewolde) and on Instagram at [@promptesss](https://www.instagram.com/promptesss).
