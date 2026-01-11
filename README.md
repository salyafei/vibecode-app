# VibeCode Personal

A personal AI coding assistant powered by Claude (Opus 4 & Sonnet 4). Your own private vibecode.dev alternative with zero subscription fees - just pay for what you use with the Anthropic API.

## Features

- **Dual Model Support**: Switch between Claude Opus 4 (most capable) and Claude Sonnet 4 (fast & efficient)
- **Beautiful Dark UI**: Modern, professional interface with syntax highlighting
- **Code Syntax Highlighting**: Automatic highlighting for 180+ programming languages
- **Markdown Rendering**: Full markdown support with tables, lists, blockquotes
- **File Attachments**: Attach code files for context-aware assistance
- **Conversation History**: Persists during your session
- **Usage Statistics**: Track your token usage and costs
- **One-Click Copy**: Copy code snippets with a single click
- **Fully Local**: Your API key stays in your browser, never stored on any server

## Quick Start

### Option 1: Open Directly (Recommended)
1. Download or clone this repository
2. Open `index.html` in your browser
3. Enter your Anthropic API key
4. Start coding!

### Option 2: GitHub Pages
1. Go to repository Settings > Pages
2. Set source to "Deploy from a branch"
3. Select `main` branch and `/ (root)` folder
4. Access at `https://yourusername.github.io/vibecode-app/`

### Option 3: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

## Getting Your API Key

1. Go to [console.anthropic.com](https://console.anthropic.com/)
2. Sign up or log in
3. Navigate to API Keys
4. Create a new API key
5. Copy and paste into VibeCode Personal

## Models

| Model | Best For | Speed | Cost |
|-------|----------|-------|------|
| **Claude Sonnet 4** | Daily coding tasks, quick questions, code reviews | Fast | Lower |
| **Claude Opus 4** | Complex architecture, difficult bugs, deep analysis | Slower | Higher |

## Cost Savings

By using the API directly instead of a subscription:
- **Pay per use**: Only pay for what you actually use
- **No monthly minimum**: Perfect for occasional use
- **Full control**: Choose the right model for each task

### Typical Costs (as of 2025)
- Sonnet 4: ~$3 per 1M input tokens, ~$15 per 1M output tokens
- Opus 4: ~$15 per 1M input tokens, ~$75 per 1M output tokens

A typical coding session might use 50K-200K tokens, costing $0.15-$3.00.

## Settings

Access settings via the gear icon:

- **Temperature**: Controls creativity (0 = focused, 1 = creative)
- **Max Tokens**: Maximum response length (up to 32K)
- **Export**: Download your conversation as JSON
- **Clear Data**: Remove all saved data including API key

## Privacy & Security

- API key stored only in your browser's localStorage
- No data sent to any server except Anthropic's API
- All processing happens client-side
- Repository is private - only you can access it

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Enter` | Send message |
| `Shift + Enter` | New line |
| `Escape` | Close settings modal |

## File Support

Attach files with the 📎 button. Supported formats:
- JavaScript/TypeScript (`.js`, `.jsx`, `.ts`, `.tsx`)
- Python (`.py`)
- Java (`.java`)
- C/C++ (`.c`, `.cpp`, `.h`)
- Go (`.go`)
- Rust (`.rs`)
- Ruby (`.rb`)
- PHP (`.php`)
- Swift (`.swift`)
- Kotlin (`.kt`)
- SQL (`.sql`)
- Shell (`.sh`, `.bash`)
- Web (`.html`, `.css`)
- Data (`.json`, `.yml`, `.yaml`, `.xml`)
- Docs (`.md`, `.txt`)

## License

MIT License - Use freely for personal purposes.

---

Built for personal use. Not affiliated with Anthropic or vibecode.dev.
