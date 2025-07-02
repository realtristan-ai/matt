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
- SQLL Alchemy
- OpenAI GPT4
- HTML, CSS, & JavaScript
  

**Screenshots:**

<img width="1795" alt="461279267-c5c525f0-cd1b-4a1d-9a70-0aec6009aa9d" src="https://github.com/user-attachments/assets/bc77c971-9aaa-40f7-b13d-aa7f426d9ed8" />



## resume.ai

Automated resume analysis & scoring dashboard.

**Video preview:** https://streamable.com/mieb3f

**Since last preview:**
- Improved UI
- Reduced score volatility. I tested 100+ applications with the same input and for every time, I got the same score.
  - Used the `analyze.ai` tool above to refine the prompt :)
  - So no need for manual tuning

_And more!_

**Tech Stack:**
- Next.js + React + tRPC
- TypeScript
- Tailwind CSS + Shadcn
- Prisma + Postgresql
- OpenAI GPT4


**Screenshots:**

<img width="1797" alt="461281439-a95addbb-992e-4085-b115-050f98a8dc29" src="https://github.com/user-attachments/assets/0fc31a67-5949-4717-942f-89d602671f66" />



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

<img width="1798" alt="461281175-031efc2b-f04a-4aa6-80c9-a4b6c2aab99f" src="https://github.com/user-attachments/assets/77055826-f32e-4bd6-bd7b-2b37a2a78427" />
<img width="1786" alt="461281230-94e753c9-b378-4ae8-8176-54b1f7b646e1" src="https://github.com/user-attachments/assets/84414dc8-7695-4a00-bce8-50de7c9896ae" />


