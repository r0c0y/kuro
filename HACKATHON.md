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

Project: **Kuro**, an offline maintainer assistant. When a pull request changes code, Kuro finds the documentation sentences that the change made incorrect (renamed flags, changed defaults, removed options) and suggests a fix. All AI work is done by Gemma 4 running locally on the laptop. No cloud AI is used.

## AI models used

| Model | Runtime | Role in the product | Why this model |
|---|---|---|---|
| `gemma4:e2b` | Ollama, local | Core AI: judges whether a documentation sentence is now incorrect given a specific code change, explains why, and writes the corrected sentence | Required by the Gemma track. The e2b size is the recommended choice for laptops with limited memory (ours is 8 GB), and it runs fully offline |

No other AI model is used by the product, locally or in the cloud.

## AI coding assistants

- Claude Code (Claude Opus 5.5)
