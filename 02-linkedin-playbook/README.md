# The 5-Step LinkedIn Playbook

*Updated Nov 2026*

I made this to go with my LinkedIn optimization video. It walks through the same 5 steps, each with a copy-paste Claude prompt, so recruiters can find you, you rank higher in LinkedIn search, and more profile views turn into interviews.

## At a glance

| | |
|---|---|
| **Difficulty** | Easy, no coding |
| **Time** | One sitting for Steps 1 to 4, then 2 to 3 posts a week |
| **You'll end up with** | A headline, About section, job titles, skills and Featured section recruiters can find, plus 3 weeks of post ideas |

| Step | What you do | Key action |
|---|---|---|
| [1](#step-1-headline-and-titles-get-searchable) | Headline and titles | Fix search ranking |
| [2](#step-2-about-and-experience-make-it-a-story-kill-the-metrics) | About and experience | Story + keywords |
| [3](#step-3-skills-and-open-to-work-get-into-the-recruiter-filters) | Skills and Open to Work | Get into recruiter filters |
| [4](#step-4-featured-section-prove-you-ship) | Featured section | Prove you ship |
| [5](#step-5-post-about-your-work-the-one-that-compounds) | Post about your work | The step that compounds |

## Start here

Want the whole thing in one go? Copy the [master prompt](#the-master-prompt), fill in the brackets and paste it into Claude. Want more control? Go step by step below, so you can review and tweak each part as you go. Both get you to the same place.

## What you need

- Claude (any plan)
- Your resume
- Screenshots of your LinkedIn profile: header, About, every role, skills and Featured
- 2 to 3 real job posts for the role you want. Claude pulls your keywords from them, so they match what companies are actually asking for

Run all 5 prompts in **one** Claude conversation, not five separate chats. Steps 2 to 5 say "above" because they build on the resume, screenshots and job posts you share in Step 1.

---

## Step 1. Headline and titles: get searchable

Your headline is the most important field on your whole profile. It's what LinkedIn ranks you on in search. Write it as your role, three keywords, then your best credential, all under 100 characters. While you're in there, fix every job title to match what recruiters actually type. If yours says Growth Lead or IC4 but recruiters are searching Marketing Manager, you don't exist in their results.

**Why it matters:** LinkedIn's search weights your headline more than any other field. A creative title that doesn't match a real search term means your profile never shows up, no matter how strong the rest of it is.

**What to do**

- Rewrite your headline: `[Your Role] + 3 keywords + your best credential`, under 100 characters. LinkedIn lets you use 220, but only about the first 100 show in search and on mobile, so keep the important part up front
- Swap any internal, advisory or creative job title for the standard title recruiters search

**Prompt**

```text
You are a LinkedIn SEO and recruiter-search expert. I am targeting the role of [YOUR TARGET ROLE, e.g. Marketing Manager]. Here is my resume: [PASTE RESUME]. Here are screenshots of my current LinkedIn profile: [ATTACH SCREENSHOTS]. Here are 2-3 real job posts for this role: [PASTE JOB POSTS].

1. Give me 5 headline options, each under 100 characters, in this exact format:
Role | Keyword · Keyword · Keyword | Credential
Use the keywords that show up in these job posts and that a recruiter would actually search to find someone in my field. No buzzwords, no metrics.

2. Review every job title on my profile. Flag any that are vague, internal, or "creative" (like Marketing Ninja or Customer Happiness Hero) and tell me the standard title recruiters actually search for instead.
```

You're done when your headline is under 100 characters and every job title is one a recruiter would search.

---

## Step 2. About and experience: make it a story, kill the metrics

This one's going to feel wrong, but trust me. Your About section is a story, not a summary. No bullet points, no metrics. Write it like you're explaining your career to someone at dinner who actually asked. Same for every role. Then take every metric off your profile and save the numbers for your resume and interviews. A recruiter scans you in about seven seconds, and a story with the right keywords beats a wall of stats every time.

**Why it matters:** Bullet-point profiles full of metrics read like a copy of your resume. Recruiters scan for keywords and credibility, not spreadsheets.

**What to do**

- Rewrite your About as a story in 4 to 6 short paragraphs: an opening hook, your career thread, your current work, and one line on what you want next
- Rewrite each job as one short paragraph, then 3 to 5 Focus Areas bullets full of searchable keywords
- Remove every metric from every section

**Prompt**

```text
Using my resume and LinkedIn screenshots above, and targeting [YOUR TARGET ROLE], rewrite two things:

1. My About section as a STORY, not a summary. 4 to 6 short paragraphs:
- An opening hook
- The thread connecting my career
- What I do now and how I think about the work
- One line on what I am open to next
No bullet points, no metrics. Weave in the keywords a recruiter searches for, but keep it sounding like a real person talking.

2. Each of my job descriptions as one short narrative paragraph (what I owned and how I worked), followed by 3 to 5 Focus Areas bullets that are each full of searchable keywords. No metrics anywhere. Write for a recruiter scanning for 7 seconds.
```

You're done when your About reads like a story and there are no numbers left anywhere on your profile.

---

## Step 3. Skills and Open to Work: get into the recruiter filters

This is the behind-the-scenes one nobody talks about. LinkedIn lets you tag five Top skills at the bottom of your About section, and recruiters filter by skills when they search. So pick the five they're actually typing, not the ones that sound impressive. Then turn on Open to Work, add your five target titles and set it to recruiters only. Every box you leave empty is a search you're invisible in.

**Why it matters:** LinkedIn Recruiter filters by skills and job titles. If yours don't match what a recruiter is filtering for, you won't show up, even if you're a perfect fit.

**What to do**

- Add 5 Top skills to your About section (click the pencil on About), using the ones recruiters in your field filter by most
- Put those same 5 first in your Skills section too, since only the first few show without clicking
- Turn on Open to Work
- Add 5 target job titles, turn on Remote if you want it, and set visibility to Recruiters only

**Prompt**

```text
For someone targeting [YOUR TARGET ROLE] in [YOUR INDUSTRY], tell me:

1. The exact 5 skills I should add as my Top skills on LinkedIn, ranked by how often recruiters actually search them for this role. Base it on the job posts above and the words recruiters actually use, not what sounds most impressive.

2. The 5 job titles I should enter in LinkedIn's Open to Work settings to appear in the most relevant recruiter searches, plus whether I should turn on Remote and which employment types to select.
```

You're done when your About has 5 Top skills, and Open to Work has 5 titles and is set to Recruiters only.

---

## Step 4. Featured section: prove you ship

This is the first thing a recruiter clicks after your headline, and almost everyone leaves it empty. Don't. Put one thing here that proves you do the work: a quick video walking through something you built, a post that did well, a live tool or a portfolio link. One strong piece here does more than ten perfect bullet points.

**Why it matters:** Featured is where profile views turn into messages or drop off. An empty one says there's nothing to point to.

**What to do**

- Add at least one Featured item that shows something real you built or shipped
- Best: a 2 to 3 minute video walking through a live product, tool or project
- Also good: a strong post in your field, a live tool anyone can use, or a portfolio or case study link

**Prompt**

```text
I want to fill my LinkedIn Featured section to prove I actually do the work for [YOUR TARGET ROLE]. Based on my background above, give me 3 specific Featured ideas I could realistically create in under 2 hours each, ranked by how much they would impress a recruiter.

For each idea:
- Tell me exactly what it should contain
- Explain why it works as a credibility signal
- Tell me how to create it (what tool, format, or platform to use)
```

You're done when your Featured section has at least one thing you built or shipped.

---

## Step 5. Post about your work: the one that compounds

If you take one thing from this, take this one. Post about your actual work two to three times a week. This is the step that compounds. It took my search appearances from around 40 a week to over 200 in a month, and it's the difference between applying into the void and recruiters showing up in your inbox.

**Why it matters:** Posting regularly about your field lifts your search appearances and shows both the algorithm and recruiters that you know your stuff.

**What to do**

- Post 2 to 3 times a week about your real work, not generic career advice
- Use Claude to plan 3 weeks of posts from your actual experience

**Prompt**

```text
I am targeting [YOUR TARGET ROLE] and want to start posting on LinkedIn. Give me 9 post ideas (3 weeks, 3 posts each) based on my real experience above.

Mix these three formats across the 9 posts:
- A lesson I have learned from real work experience
- A behind-the-scenes look at how I actually approach my work
- A simple tip or framework from my field

For each post:
- Give me a scroll-stopping first line
- Keep it specific to my actual work and field
- No generic career advice
```

You're done when you have 9 post ideas and your first post is up.

---

## The master prompt

Fill in every bracket, attach your resume and screenshots, and paste it into Claude.

```text
You are a LinkedIn growth strategist and recruiter-search expert.

Optimize my LinkedIn profile so that:
1. Recruiters searching for [YOUR TARGET ROLE] find me in search
2. My profile ranks higher in LinkedIn search results
3. My profile converts views into recruiter messages and interviews

STEP 1 - MY INPUTS
Here is my resume: [PASTE RESUME TEXT OR ATTACH PDF]
Here are screenshots of my LinkedIn: [ATTACH: header, about, every role, skills, featured]
Here are 2-3 real job posts for my target role: [PASTE JOB POSTS]

STEP 2 - TARGETING
I am targeting this role: [YOUR TARGET ROLE] (e.g. Marketing Manager, Project Manager, Account Executive)
Industries I am targeting: [LIST YOUR TARGET INDUSTRIES]
Company type: [STARTUP / ENTERPRISE / BOTH]
My strongest credential: [CERTIFICATION, NOTABLE EMPLOYER, OR ACHIEVEMENT]
My technical or domain skills: [LIST THE TOOLS AND SKILLS YOU ACTUALLY USE]
My biggest results, for your context only, not for LinkedIn: [LIST 3-5 METRICS YOU WILL SAVE FOR INTERVIEWS]

STEP 3 - WHAT TO PRODUCE
1. HEADLINE (5 options)
Format: [Role] | [Keyword] · [Keyword] · [Keyword] | [Credential]
Under 100 characters. No metrics.

2. TITLE AUDIT
Flag titles that do not match real recruiter search terms. Suggest the functional replacement for each.

3. ABOUT SECTION
Story-driven, 4 to 6 paragraphs, no metrics, no bullets. Structure: Hook, Career thread, Current work, What I want next.

4. ALL EXPERIENCE ROLES
Each role: one narrative paragraph then Focus Areas bullets. No metrics. Every bullet is a keyword cluster.

5. TOP 5 SKILLS TO PIN
Ranked by how often they show up in the job posts and in recruiter searches for my target role.

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

The more specific you are, the better the output.

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

💡 **Step 3 works on its own.** You can run it without your resume for a quick answer. For a more personal result, keep it in the same chat.

💡 **More detail, better ideas.** Featured and post ideas land much better when Claude knows your actual background.

⚠️ **Don't skip the job posts.** Claude can't see LinkedIn's search data, so the job posts you paste are what make its keyword picks real.

⚠️ **No numbers on LinkedIn.** Save your metrics for your resume and interviews. Give them to Claude for context only.

⚠️ **Looking for Creator Mode?** LinkedIn retired it in 2024. Everyone has the Follow button now, so posting does the work.

---

Something didn't work? [Open an issue](https://github.com/Lily-Tewolde/ai-guides/issues) and tell me what happened.

Made by [Lily Tewolde](https://github.com/Lily-Tewolde). Find me on TikTok at [@lilytewolde](https://www.tiktok.com/@lilytewolde) and on Instagram at [@promptesss](https://www.instagram.com/promptesss).
