# How to use the kit

## 1. Make a private copy

This kit will hold your real stories, numbers, interviewer notes, and comp details. On GitHub, click **Use this template** and choose **Private**. Or just download the ZIP and keep it on your computer.

## 2. Fill in `context/`

Start with `candidate-profile.md` and three stories in `story-bank.md`. Ask your agent to help: *"Read my resume and LinkedIn, then interview me to fill in my story bank. Ask for the numbers; don't make them up."*

## 3. Run skills

### Claude Code

```
/plugin marketplace add hyde-larkin/product-marketing-interview-kit
/plugin install product-marketing-interview-kit@product-marketing-interview-kit
```

The plugin brings the skills; copy `context/` into the folder you prep in. Or open a clone of this repo in Claude Code and ask in plain language.

### Cursor, Codex, Copilot

Open the folder. Ask: *"Read AGENTS.md, then run round-prep for my hiring manager interview at [company]."*

### ChatGPT, Claude.ai, Gemini

Create a project. Upload `AGENTS.md`, your `context/` files, and the `SKILL.md` for what you're doing. Then ask.

## 4. Keep a folder per company

In your private copy, add `context/companies/[company]/` for the brief, round prep, debriefs, and offer notes. Your `pipeline.md` links to them.

That folder is listed in `.gitignore`, so it won't be committed by accident. If your copy is private and you want those notes versioned, delete that line from `.gitignore`.

## Privacy

- Don't push your filled-in copy to a public repo.
- Keep other people's names, interview content, and take-home materials private. Many companies ask candidates not to share them.
