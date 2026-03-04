# GWC Workshop: AI as Your Portfolio Partner!
context

## Notes

## From Chatbot to Builder: How to "Vibe Code" Your Own AI Career Decision Engine

[cite_start]If you’ve been using AI primarily as a high-powered search engine or a document summarizer, you’re only scratching the surface of what’s possible[cite: 14, 47]. [cite_start]Currently, about 85% of people use AI strictly as a conversational chatbot[cite: 47]. [cite_start]But the real professional advantage lies in moving up the pyramid—from level one (chatting) to level three: building bespoke, small-batch software designed just for you[cite: 45, 46, 49].

[cite_start]In a recent workshop, we moved past the chat window and into **"vibe coding"**[cite: 33]. [cite_start]This is the process of building functional software by focusing on the "vibe" and the logic of the problem rather than manually writing the source code[cite: 34]. [cite_start]Our goal was to create a **Career Decision Engine**: a custom, locally-hosted web app that evaluates any job opportunity against your unique professional DNA[cite: 20, 94, 308].

> "Vibe coding is a way of building software without actually writing software code... I still do not know how to code. But I have developed a framework of how I, as a non-engineer, can effectively build things." [cite_start]— Bethany Crystal [cite: 34, 35, 36]

---

### The "Popit" Framework: Identifying AI-Shaped Problems
[cite_start]Before you open a code editor, you need a strategy[cite: 61]. [cite_start]The **Popit** framework helps you move from a tool-first mindset to a problem-first mindset[cite: 63, 64]:

* [cite_start]**P – Problem**: Define the hurdle[cite: 62]. [cite_start]Instead of asking "What tool should I use?", ask "What is the career choice I'm trying to clarify?"[cite: 63, 69].
* [cite_start]**O – Output**: Define exactly what the AI should give you[cite: 71, 72]. [cite_start]Do you want a 0–100 fit score, a rubric of non-negotiables, or a list of interview questions?[cite: 73, 74, 199].
* [cite_start]**P – Prompt**: These are the specific instructions that drive the AI[cite: 75, 76]. [cite_start]Interestingly, once you define the problem and output, the AI can often write a better prompt for itself than you can[cite: 77].
* [cite_start]**I – Input**: This is your **"Context Pack"**[cite: 78]. [cite_start]Every piece of digitized info you have—resumes, essays, or even a 20-year plan—is data the AI can use to understand you[cite: 79, 81].
* [cite_start]**T – Test**: AI rarely gets it perfect on the first try[cite: 84]. [cite_start]You must test the output against a real scenario to see if the logic holds up[cite: 84, 86, 240].

---

### Sprint 1: Building Your Context Pack
[cite_start]The AI is only as insightful as the data you provide[cite: 90, 114]. [cite_start]To start, create a folder on your computer and gather 3–5 files that define your professional identity[cite: 104, 105]:
* [cite_start]**Your Resume/CV**: To establish your hard skills and history[cite: 105].
* [cite_start]**A Personal Bio or LinkedIn PDF**: To give the AI a sense of your "voice" and narrative[cite: 22, 24].
* [cite_start]**A Career Goals Document**: This is crucial[cite: 116, 125]. [cite_start]Define your "North Star," your top 3 skills to build, and your "non-negotiables"[cite: 121, 122, 123].

---

### Sprint 2: Engineering the Logic
[cite_start]Using a tool like **Claude Code** or a text editor like **Cursor**, you can ask the AI to synthesize these files into a structured "Professional Profile"[cite: 132, 133, 160]. [cite_start]Once the AI understands your background, you put it into **Planning Mode**[cite: 193].

In this phase, we instructed the AI to build a logic engine that compares a job description to our goals and outputs:
1.  [cite_start]**A Weighted Fit Score**: Categories are weighted based on what matters most to you[cite: 199, 215].
2.  [cite_start]**Trade-off Analysis**: What are you giving up if you take this role?[cite: 200, 272].
3.  [cite_start]**The "Investigate" Flag**: If the job description is missing key info, the AI flags it for you to ask about[cite: 202, 234].

[cite_start]For example, we tested an external affairs role against the profile of **Nancy Drew**[cite: 189, 242]. [cite_start]The engine correctly flagged it as a poor fit (65/100) because her investigative skills didn't align with government affairs[cite: 267, 268, 270].

---

### Sprint 3: The Front-End "Small Batch" App
[cite_start]The final evolution is moving out of the command line and into a real interface[cite: 290, 307]. [cite_start]We asked the AI to build a local web app using **Node.js** and **Express**[cite: 331, 332]. [cite_start]By connecting an **API key**—stored safely in a `.env` file to protect your security—we turned a chat thread into a functional tool[cite: 336, 337, 393].

The result? [cite_start]A visual dashboard where you can paste a job link and get a visual analysis of how that role fits into your long-term career path[cite: 418, 437, 440].

---

### Points of Inspiration: The Maker Mindset
[cite_start]Moving from a consumer to a maker requires a psychological shift[cite: 38, 41]. Here are the key takeaways for anyone starting their AI journey:

* [cite_start]**You Don't Need Permission**: "I grew up in an era where software was sort of handed to us... The last 18 months, I've been rewiring my brain to think... I can design my own functioning app"[cite: 39, 41, 42].
* [cite_start]**The Power of "Small Batch"**: You don't need a million users to make something meaningful[cite: 43]. [cite_start]"Small batch software is one of the biggest wins of AI. We no longer need to wait for a SaaS tool to create an app for us"[cite: 305, 306].
* [cite_start]**The Reflexive Habit**: "Getting into the reflexive habit of working with AI to help you make decisions is probably the most important thing you could do for your career right now"[cite: 279, 280].
* [cite_start]**Stay Curious**: "Every time I build an app, it teaches me about how to build an app better"[cite: 413].

---

**Would you like me to generate the "Popit" starter prompt so you can build your own Career Decision Engine?**
