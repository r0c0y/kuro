# HACKATHON.md

**Event:** Hacktoberfest 2026: Hack Day Sonipat (Newton School of Technology, Rishihood University)

## Team

**Team name:** Team 07

| Name | GitHub |
|---|---|
| Priyanshu Tomar | [@r0c0y](https://github.com/r0c0y) |

Solo participant.

## Selected problem statement

**Problem 08: Build Anything with Gemma 4 (Local AI Innovation Challenge, Gemma track)**

Project: **Kuro**, your homie that runs fully offline on your own laptop. Kuro is a local AI assistant powered by Gemma 4: everything it understands and everything it generates comes from Gemma running on the laptop, with no cloud AI. The exact feature set is being finalised during the hackathon and will be documented in this file and the README through pull requests.

## AI models used

| Model | Runtime | Role in the product | Why this model |
|---|---|---|---|
| `gemma4:e2b` | Ollama, local | Core AI: all of Kuro's AI work (understanding the user's input and generating its responses) runs on this model | Required by the Gemma track. The e2b size is the recommended choice for laptops with limited memory (ours is 8 GB), and it runs fully offline |

No other AI model is used by the product, locally or in the cloud.

## AI coding assistants

- Claude Code (Claude Opus 5.5)
