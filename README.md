# Skill Doorway Check

**A free safety check for any AI skill, plugin, GPT or prompt pack, before you install it.**
Drop in the skill exactly as you got it, zip file and all. It reads the skill (it never runs it), runs 8 checks, and gives you a 🟢 GREEN, 🟡 YELLOW or 🔴 RED light with the exact lines it found. No technical skills needed.

Current version: **1.0.3**

## Download

**[⬇ Download the latest version](../../releases/latest)**, then open **START-HERE_Skill-Doorway-Check.pdf**.

| File | For |
|---|---|
| `START-HERE_Skill-Doorway-Check.pdf` | Everyone: 2-minute setup and how to use it |
| `skill-doorway-check-v1.0.3.zip` | Claude (claude.ai and the Claude app). Don't unzip it |
| `Skill-Doorway-Check_Instructions_v1.0.3.txt` | ChatGPT, Gemini, Copilot, Grok or Perplexity |
| `Quick-Use-Card_Hidden-Doorways.html` | One-page reference card |

## Set it up once

**Claude:** in the left menu, click **Plugins**, then **Skills**, then **Add**, and drop in the zip.

**ChatGPT, Gemini, Copilot, Grok or Perplexity:**
1. Make a Project, GPT, Gem, agent or Space named "Skill Doorway Check".
2. Paste the whole `.txt` file into its instructions box.
3. Turn off web browsing, connected apps and memory. Leave file or data analysis **on** so it can open zip files.

## Use it every time

1. Open a new chat with nothing else in it.
2. Type `/skill-doorway-check` and say where the skill came from.
3. Drop in the skill exactly as you got it.

| Light | Meaning |
|---|---|
| 🟢 GREEN | OK to try. Start with fake data. |
| 🟡 YELLOW | Fix or test first. Do what the report says, then check again. |
| 🔴 RED | Don't install. If it's already installed, turn it off. |

It's a first screen, not a guarantee. If a skill will touch client or regulated data, get a full review from a qualified security professional.

## Is this the real file?

Check the fingerprint (SHA-256) before you use it. On Windows, in PowerShell: `Get-FileHash .\skill-doorway-check-v1.0.3.zip`

| File | SHA-256 |
|---|---|
| `skill-doorway-check-v1.0.3.zip` | `95abd668d97c2a44c75dc66e054494ca71951b2e38f30318509309c548884e1a` |
| `Skill-Doorway-Check_Instructions_v1.0.3.txt` | `8daf9b26c8712866a73295e53d9d3cac742c734a51c2659f0c81033c544a57c0` |

The `skill-doorway-check` folder in this repository is the readable source of the same skill.

## License

Free to use for your own practice. Please don't resell or republish it. See [LICENSE.md](LICENSE.md).

Copyright © 2026 Elliptic Systems Corporation · [EllipticSystems.com](https://ellipticsystems.com) · Securing Your AI-Enabled Workplace
