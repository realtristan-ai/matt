# Tristan Simpson

So yea, A LOT of new updates, optimizations, and projects. Worked on these over the weekend in my spare time :)

## analyze.ai

Automatic Prompt Engineering Tool.

**Video preview:** https://streamable.com/n5qbnl

**Since last preview:**
- Improved UI
- App now creates embeddings for over 20 high-quality prompts from multiple startups including: Vercel, v0, Dia, Cluely, etc.
  - Finds the top 3 most similar examples (from above ^) to the user-inputted prompt.
  - Generates a high quality prompt with a list of possible improvements.
  - Recursively apply improvements to get the best possible prompt!

_And more!_

**Tech Stack:**
- Python3
- FastAPI
- SQLite
- OpenAI GPT4
- HTML, CSS, & JavaScript
  

**Screenshots:**

![image](https://github.com/user-attachments/assets/a96b6e01-972e-487e-9935-1e9cea4866ef)



## resume.ai

Automated resume analysis & scoring dashboard.

**Video preview:** https://streamable.com/mieb3f

**Since last preview:**
- Improved UI
- Reduced score volatility. I tested 100+ applications with the same input and for every time, I got the same score :)

_And more!_

**Tech Stack:**
- Next.js + React + tRPC
- TypeScript
- Tailwind CSS + Shadcn
- Prisma + Postgresql
- OpenAI GPT4


**Screenshots:**

![image](https://github.com/user-attachments/assets/a8747fd2-d4e4-46df-a1e4-0c249fdd083b)


## pr.ai

Automated GitHub PR Analysis & Summarizer + Dashboard.

**Video Preview:** https://streamable.com/frkkmc

**About the app:**
- Intuitive dashboard to see all summarized PRs (using webhooks + PostgreSQL db)
- Easily set the webhook for repositories (repositories page, no need to manually go into GitHub and set it)
- Automatically summarizes the PR.
  - Explicitly defines the new/removed features.
  - Provides recommended bug, vulnerability, security, and style fixes.
  - Sends a comment in the PR with everything!

_And more!_

**Tech Stack:**
- Next.js + React + tRPC
- TypeScript
- Tailwind CSS + Shadcn
- Prisma + Postgresql
- OpenAI GPT4
- GitHub Webhooks


**Screenshots:**

![image](https://github.com/user-attachments/assets/878d0c08-4829-4892-bb02-0686f5777719)
![image](https://github.com/user-attachments/assets/81b59069-2c64-4ce4-8185-0db16ff1bfa3)

