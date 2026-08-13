# GitHub Profile Settings (paste manually)

These fields live in GitHub UI, not in the repo: https://github.com/settings/profile

## Bio (160 char limit)

GitHub cuts bios at 160 characters. Your full string is 164, so use this trimmed version:

```
Software Engineer | AI Agents & LLM Apps | RAG Pipelines | LLM API Integration | Agent Orchestration | LangChain | LangGraph | FastAPI | Vector DBs
```

(147 characters)

## Other fields

| Field | Value |
|---|---|
| Name | MD Safiqul Islam |
| Email (public) | safiqultuhin055@gmail.com |
| Website | https://safiqulislam.com |
| Company | *(optional)* |
| Location | *(optional)* |

Tick **"Display email on profile"** so `safiqultuhin055@gmail.com` shows publicly.

---

# Push this repo

The profile README only renders if the repo name **exactly** matches your username: `Safiqultuhin055`.

```bash
cd "C:/Users/Fabulouscode/Projects/Safiqultuhin055"

# 1. authenticate once (interactive)
gh auth login

# 2. create the special profile repo and push
gh repo create Safiqultuhin055 --public --source=. --remote=origin --push
```

If the repo `Safiqultuhin055` already exists on GitHub:

```bash
git remote add origin https://github.com/Safiqultuhin055/Safiqultuhin055.git
git branch -M main
git push -u origin main
```

Then open https://github.com/Safiqultuhin055 — banner + About + Skills render on the profile front page.
