# 🚀 Agents Setup for macOS (Apple M2 Pro)

> This guide is for macOS users who cannot install Anaconda/Conda due to system restrictions. It uses **Miniforge**, a lightweight open-source alternative, to run `conda` commands seamlessly.

---

## Prerequisites

- macOS (Apple Silicon, e.g., M1/M2/M2 Pro)  
- Homebrew installed ([Install Homebrew](https://brew.sh/))  

---

## Setup Instructions

1. **Clone the Repository**

```bash
git clone git@github.com-personal:yasir-ysq/agents.git
cd agents
```

2. Create .env file in root folder 'agents' and enter API keys
```bash
touch .env
```
Then, add the following to the .env file:
```bash
OPENAI_API_KEY=sk-proj-lots_of_characters_here
GOOGLE_API_KEY=xxxx
ANTHROPIC_API_KEY=xxxx
DEEPSEEK_API_KEY=xxxx
```

3. Update UV Package manager, since I installed UV using brew, these are the steps to update it:
```bash
brew update  
brew upgrade uv
```

4. Install miniforge. Since Anaconda was blocked, I used open source alternate called miniforge. Miniforge lets you run conda commands!

```bash
brew install miniforge
```
