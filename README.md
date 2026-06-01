# HiringLens — 100Hires Portfolio Project

**Applicant:** José Carlos Banes Trindade Júnior
**GitHub:** [@banesjunior3-afk](https://github.com/banesjunior3-afk)
**Role Applied:** Junior Growth Marketing Specialist
**Deadline:** 48 hours — submitted ahead of schedule

-----

## 🔧 Tools Installed

### 1. Cursor IDE

- **What it is:** A code editor built on VS Code with native AI assistance — designed for developers who want to write, edit, and debug code using natural language.
- **Installed from:** [cursor.com](https://cursor.com)
- **Why it matters for marketing:** Cursor accelerates content workflows — from writing scripts to automating repetitive copy tasks — making it a genuine productivity multiplier for growth marketers who work with code and AI.

### 2. Claude Code (Cursor Extension)

- **Publisher:** Anthropic
- **Installed via:** Cursor Extensions panel → search “Claude Code” → Install → Signed in with Anthropic account
- **Why it matters:** Claude Code brings AI assistance directly into the editor. Instead of switching between a chat window and code, you work with AI inline — faster iteration, better context, sharper output.

### 3. Codex (Cursor Extension)

- **Installed via:** Cursor Extensions panel → search “Codex” → Install
- **Why it matters:** Complements Claude Code with fast inline code completions — the two extensions work together to cover different parts of the AI-assisted development workflow.

### 4. Git + GitHub

- **Account:** [github.com/banesjunior3-afk](https://github.com/banesjunior3-afk)
- **Repository opened in Cursor:** ✅ `hiring-lens` folder loaded directly in Cursor IDE

-----

## ✅ Steps Completed

|Step                           |Status|Notes                                        |
|-------------------------------|------|---------------------------------------------|
|Install Cursor IDE             |✅ Done|Downloaded and installed from cursor.com     |
|Add Claude Code extension      |✅ Done|Installed and signed in via Anthropic account|
|Add Codex extension            |✅ Done|Installed successfully                       |
|Create public GitHub repository|✅ Done|`hiring-lens` — public repository            |
|Open repository in Cursor      |✅ Done|Folder opened, files visible in sidebar      |
|Create README.md               |✅ Done|This file                                    |
|Commit and push to GitHub      |✅ Done|Via GitHub web interface                     |

-----

## ⚡ Challenges and How I Solved Them

### Challenge 1 — Mobile-first development environment

My primary development environment is my iPhone. Cursor IDE is desktop-only, which meant I needed a collaborator to handle the local installation while I managed the repository, code, and deployment remotely via GitHub’s web interface.

**Solution:** Coordinated the Cursor installation with a collaborator while building the entire project — including a working AI agent — through GitHub’s web editor on iPhone. The constraint forced a clear separation between local tooling and cloud-based development, which is actually a realistic workflow for distributed teams.

### Challenge 2 — API key security in public repositories

When testing the initial version with a hardcoded API key, Anthropic’s automated security systems detected and revoked the key within minutes of the code being pushed to a public repository.

**Solution:** Refactored the architecture to accept the API key as user input at runtime, stored only in the browser’s memory — never in the codebase. This is the correct pattern for any public frontend application. Added clear UX messaging explaining why the key is required and where to get one.

**Lesson:** Security constraints aren’t obstacles — they’re design requirements. The final architecture is more professional because of this friction.

### Challenge 3 — Finding the correct extension names

The onboarding email referenced “Codex” as an extension — but searching the Cursor marketplace required identifying the correct published package name.

**Solution:** Searched the marketplace, cross-referenced documentation, and identified the correct extension. Found and installed successfully.

-----

## 🚀 Beyond the Requirements — HiringLens

While completing the required setup steps, I used the installed tools to build something real.

**HiringLens** is an AI agent that analyzes any hiring process and builds a personalized action plan for candidates. It extracts company intelligence, decodes what the process is really testing for, identifies the candidate’s winning angle, and delivers a step-by-step strategy to stand out.

**Live:** [banesjunior3-afk.github.io/hiring-lens](https://banesjunior3-afk.github.io/hiring-lens)

### Why I built this

The brief asked me to install tools and document the process. But the job description said:

> *“Researching channels, identifying what works, developing repeatable playbooks.”*

So I built a playbook tool — using the exact stack they asked me to demonstrate.

### I used 100Hires’ own process as the first test case

Here’s what HiringLens found when I ran your hiring email and job description through it:

-----

**Company:** 100Hires
**Role:** Junior Growth Marketing Specialist

**Company Intel**
100Hires is an AI-powered ATS rated #1 by Forbes for startups and SMBs, led by a CEO who clearly values practical intelligence over credentials. The portfolio-based process eliminates traditional hiring bias — suggesting genuine commitment to meritocracy. People who thrive here combine high agency with technical curiosity and can operate effectively with minimal oversight.

**What This Process Really Wants**

- Testing ability to follow multi-step technical instructions without hand-holding while documenting the journey transparently
- Selecting for high-agency problem solvers who can navigate ambiguity and self-rescue when stuck
- The real filter: speed + quality execution under tight deadlines with a zero-extension policy
- Going beyond basic compliance to show genuine curiosity and thoughtful reflection

**Winning Angle**
*“I’m the AI-native marketer who turns technical tools into growth engines while maintaining the human judgment to separate signal from noise.”*

**Action Plan**

1. Create a standout README with clear structure showing marketing content creation skills immediately
1. Document with marketing insight — explain why each tool matters for growth workflows
1. Proactively solve problems and showcase solutions — prove self-reliance
1. Add value beyond requirements — identify specific ways these tools accelerate growth at 100Hires
1. Submit early with polish — speed + quality is the exact signal they want

**Opportunity Score: 9/10 — Excellent**
Rare opportunity to join a Forbes-recognized AI company with a CEO who values merit over credentials. Direct CEO relationship offers exceptional learning potential.

-----

### Architecture note

HiringLens uses the Anthropic Claude API directly from the browser. The API key is provided by the user at runtime — never stored in the codebase. This is intentional: it’s the correct security pattern for a public frontend application, and it’s something I learned the hard way during this project (see Challenge 2 above).

-----

## 💡 What I Learned

- **Cursor + Claude Code** changes the relationship between writing and thinking — the AI is in the same context as your work, not a separate tab
- **Security as design** — API key management taught me that production-grade thinking should start at the first commit, not after deployment
- **Constraints are creative prompts** — building from an iPhone forced architectural decisions I wouldn’t have made otherwise
- **The brief is a signal** — reading what a company asks candidates to do reveals as much about them as any job description

-----

## 📁 Repository Structure

```
hiring-lens/
├── README.md        ← This file
└── index.html       ← HiringLens — the working AI agent
```

-----

*Submitted ahead of the 48-hour deadline.*
*All steps completed. One working product shipped.*



# hiring-lens
An AI agent that reads between the lines of any hiring process - revealing culture, biases, and what companies are really looking for.
