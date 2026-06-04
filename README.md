# Obsidian AI Skills Pack

A portable collection of 15 Agent Skills for Gemini CLI and Claude Code, optimized for building a "Second Brain" in Obsidian.

## 🛠 Skills Included

| Skill | Purpose |
| :--- | :--- |
| **wiki** | Vault scaffolding and management |
| **autoresearch** | Autonomous research and synthesis |
| **wiki-ingest** | Extract knowledge from URLs/Files |
| **wiki-query** | Answer questions from your vault |
| **save** | File chats as wiki notes |
| **canvas** | Visual board management |
| **think** | Deep systematic thinking loop |
| **defuddle** | Clean web pages before ingest |
| **obsidian-bases** | Database views reference |
| **obsidian-markdown** | Syntax reference |

## 🚀 Installation

### Option 1: Using Gemini CLI (Recommended)
1. Clone this repository.
2. Run the following command from the root of the repo:
   ```bash
   gemini skills install . --scope user --consent
   ```

### Option 2: Manual Link
Link the folders to your global Gemini skills directory:
```bash
mkdir -p ~/.gemini/skills/
cp -r * ~/.gemini/skills/
```

## 📖 Usage
Once installed, trigger any skill in your chat:
- `/wiki` to set up a vault
- `/autoresearch "topic"`
- `ingest https://example.com`
- `/save`
