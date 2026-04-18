# 🗂️ Resume Critique Assistant

> A structured AI-assisted tool for identifying what's holding your resume back and rebuilding it section by section. This tool only works with you doing the thinking, not the AI.

---

## 🧠 What This Is and Why I Worked On This

Most people ask AI to rewrite their resume and get back something that sounds polished but screams Ai did this. This tool works the exact same if you don't add friction to the process.

It runs a structured critique first, asks you targeted questions about your actual experience, and only then helps you rewrite. The focus of the MD is focused around one section at a time, with you in control. 

I worked on manual resumes for hundreds of jobs, customizing, rewriting, adjusting, and trying again. I did the game of following 50 recruiters on linked in and reading all their posts to help structure my resume for "success" there are multiple repeated patterns that all recruiters follow this was the main "resource" used to build this tool. The unspoken truth about getting a job is both sides use Ai tools but there is a negative outlook when the applicant uses it and it's an accepted truth that recruiters have to use it.


> **The AI is the editor. You are the author. Your input is what makes this work.**

---

## ⚙️ How It Works

The tool follows a strict 4-step process and should not skip ahead:

| Step | Name | What Happens |
|------|------|--------------|
| 1 | **Critique** | A full honest breakdown of what's weak, vague, or getting you filtered out before a human reads your resume |
| 2 | **Context Gathering** | Targeted questions about your target roles, what you can share, and whether you can put numbers to anything vague |
| 3 | **Accomplishment Mining** *(if needed)* | If your resume is light on strong bullets, it probes for work you've undersold or left off — most people have more than they think |
| 4 | **Collaborative Rewrite** | Section by section, you review every draft and push back before anything is finalized |

---

## 🚀 How to Use It

This tool is designed for **[Claude](https://claude.ai)** (claude.ai). It may function in other models but results are not guaranteed. I have tested it with Gemma 4 26B the results are similar if you want a completely free option.

### Easy Setup — 4 steps

**1. Open [claude.ai](https://claude.ai) and start a new conversation**

**2. Open `Resume_Critique_Assistant_Instructions.md` from this repo and copy the full contents**

**3. Paste it as your first message**

**4. Immediately follow it with your resume and this prompt:**

```
Here is my resume. Please critique it.

[paste your resume here]
```

That's it. The tool takes over from there.
---
## 🗂️ Recommended Setup — Use It as a Claude Project

While you can paste the instructions into any Claude conversation, the best experience
is setting it up as a **Claude Project**. This keeps each resumes critique in
its own conversation, with the instructions always loaded in the background.
The biggest benefit is that project memory builds over time. Simply put the more you use it,
the less you have to re-explain your background, target roles, and preferences
at the start of each session.

### Step 1 — Go to Projects and create a new one

<img width="964" height="483" alt="Screenshot 2026-04-14 164759" src="https://github.com/user-attachments/assets/db6aa681-38b9-469f-9f17-f47f3b918a86" />

### Step 2 — Add the instructions to your project

Click **Instructions** on the right panel and paste the full contents of
`Resume_Critique_Assistant_Instructions.md` there. (You can also place an actual MD file in the files section, the instructions has worked better for myself)

<img width="972" height="835" alt="Screenshot 2026-04-14 165126" src="https://github.com/user-attachments/assets/2b3701f2-79bc-451a-9222-2010de859e3f" />

### Step 3 — Start a new chat for each resume

Every new conversation inside the project automatically has the instructions loaded.
Start a fresh chat per person to keep critiques clean and separate.

<img width="939" height="873" alt="Screenshot 2026-04-18 122413" src="https://github.com/user-attachments/assets/f8540d34-d905-42f5-b9a2-65a7a42ae60c" />

### Step 4 — Find it anytime under Projects in the sidebar

<img width="581" height="165" alt="image" src="https://github.com/user-attachments/assets/07af3a51-1ae3-45d5-9311-298718c287b3" />


> **Note:** Projects are available on Claude's paid plans. If you're on the free tier,
> the manual paste method in the section above works just fine.

---

## 📋 What to Expect

- ⏸️ **It will not rewrite your resume immediately.** It critiques first, asks questions second, rewrites third. This is intentional. The goal is to get you thinking about what you want.
- 🔢 **It will ask about numbers.** Team sizes, metrics, timeframes. Having rough estimates ready before you start will speed things up.
- 🔁 **It will push back on vague answers.** That's the point. Be honest with yourself if the model thinks it's vauge it might be.
- ✅ **It will ask you to push back on its drafts.** Do it. The rewrites only get better when you do.

---

## 🚫 What It Won't Do

- Guess at your experience or fill gaps with invented detail
- Tell you something is good when it isn't
- Rewrite everything at once and hand it back as final
- Replace your judgment, every section requires your sign-off
- Be careful: Models also have zero respect for NDAs, be careful how it pushes

---

## 💡 Tips for Best Results
>**The Most Important Part** everything else needs to be understood to use these tips. Have fun with this!

- Know roughly what roles you're targeting before you start, it will be asking you.
- Have ballpark numbers ready (team size, output volume, timeframes) even if they aren't exact. Metrics first resumes have been king for about 5 years and is especially important for leadership roles
- Be honest about what you actually did vs. what your team did, Ai assisted resumes can already have hallucinations be careful attributing false info it can affect multiple sections
- Don't skip the pushback step — the first draft is a starting point, not a finish line. It took me three new chats (having new context windows) of constant back and forth to feel comfortable with a result
- **If you have a specific role in mind, paste the job description into the conversation**
  before the rewrite step — the tool will tailor the language and keywords to match
- **Periodically remind the model to ask you questions before rewriting anything** —
  on longer sessions AI models can drift toward generating output instead of gathering
  context. A quick "make sure you're asking me questions, not guessing" keeps it on track
---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `Resume_Critique_Assistant_Instructions.md` | The full prompt — paste this into Claude to activate the tool |
| `README.md` | This file |

---

## ⚠️ A Note on AI Limitations

This tool guides the process — it does not do the work for you. The quality of your rewritten resume depends entirely on the honesty and detail you bring to the conversation. AI cannot verify your experience, invent your accomplishments, or make judgment calls about your career on your behalf. Most importantly the MD has backing down written in, if you feel strongly about keeping or removing something **DO IT**

**A resume built with this tool is only as strong as the human behind it.**


