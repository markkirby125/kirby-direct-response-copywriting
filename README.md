# Kirby Direct Response Copywriting Skill

*This skill is part of the [Kirby Skills Collection](https://github.com/markkirby125/kirby-skills-collection).*

An AI agent skill that enforces a rigorous 17-step direct-response copywriting framework (based on the Sabri Suby / King Kong $7.8B methodology). 

This skill prevents AI tools from writing generic, sterile, "branded" fluff. When active, it forces the LLM to use proven structural formulas for headlines, deploy the Feature-Advantage-Stress (FAS) framework, and follow a strict chronologically optimized sales narrative for landing pages, VSLs, and emails.

## 🚀 Installation & Magic Prompt

Want your AI agent to learn and enforce this direct response protocol? You don't need to manually copy and paste text. 

Simply copy the **Magic Prompt** below and paste it into your favorite AI coding tool (Cursor, Windsurf, Claude Code, GitHub Copilot). Your AI will read this repository, figure out how its specific rules engine works, and install the skill for you automatically!

### 🪄 The Magic Prompt
Copy and paste this directly to your AI:

```markdown
@agent Please install the Kirby Direct Response Copywriting skill into this workspace.
1. Read the `SKILL.md` file from this repository: https://github.com/markkirby125/kirby-direct-response-copywriting
2. Identify the correct rules system for our current environment (e.g., `.cursor/rules/` for Cursor, `.windsurfrules` for Windsurf, `.clinerules` for Cline, or `~/.agents/skills/` for Antigravity).
3. Save the contents of `SKILL.md` into the appropriate local rules file or directory.
4. Confirm when the installation is complete.
```

---

## 🛠 Manual Installation Guide

If you prefer to install this skill manually, follow the instructions for your specific tool below:

### 🔹 Cursor
Cursor uses Markdown Driven Context (MDC) stored in a local `.cursor/rules` folder.
1. Create a folder in your project root called `.cursor/rules/`
2. Download `SKILL.md` and rename it to `kirby-direct-response.mdc`.
3. Place it in the `.cursor/rules/` folder.
4. The agent will automatically trigger the rules when you discuss copywriting or sales pages.

### 🔹 Windsurf (Codeium) / Cline
These tools use project-level rule files.
1. Download `SKILL.md`.
2. In your project root, open your `.windsurfrules` or `.clinerules` file and append the contents of `SKILL.md`.
3. Alternatively, save it as `/docs/kirby-direct-response.md` and instruct your `.windsurfrules` to read it before writing copy.

### 🔹 Antigravity / Claude Code (Native)
This skill was originally designed for the `~/.agents/skills/` global directory.
1. Open your terminal.
2. Clone this repository directly into your skills folder:
   ```bash
   git clone https://github.com/markkirby125/kirby-direct-response-copywriting ~/.agents/skills/kirby-direct-response-copywriting
   ```
3. Your agent will now natively understand the skill across all your workspaces!

## 📚 Core Frameworks Enforced

When this skill is active, the AI will utilize:
- **The 5 Universal Headline Formulas**
- **The 17-Step Secret Selling System** (Eyebrow -> Headline -> Agitation -> Mechanism -> FAS -> Godfather Offer -> Risk Reversal)
- **The "Halo Strategy"** for voice-of-customer market intelligence
- **The "Unslop" Protocol** (Strictly bans sterile AI tokens like *"delve"*, *"tapestry"*, and *"navigate the complexities"*)

## External Resources & Authority Links
- [Sabri Suby & King Kong Agency Methodologies](https://kingkong.co/)
- [Harvard Business Review: The Science of Persuasion](https://hbr.org/2001/10/harnessing-the-science-of-persuasion)
- [Nielsen Norman Group: B2B vs B2C Web Copywriting](https://www.nngroup.com/articles/b2b-vs-b2c/)
- [Ogilvy on Advertising (Foundational Frameworks)](https://en.wikipedia.org/wiki/Ogilvy_on_Advertising)
