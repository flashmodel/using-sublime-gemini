# How to Install Gemini CLI

To get started, you need to install both the Gemini CLI tool and the Sublime Text package.

## Step 1: Install Gemini CLI (Command Line)

The plugin depends on the globally installed `@google/gemini-cli`. Ensure you have Node.js installed, then run:

```bash
npm install -g @google/gemini-cli
```

> **Note**: Version `0.34.0` or higher is recommended for full compatibility.

## Step 2: Install the Sublime Text Plugin

### Option A: Via Package Control (Recommended)

1. Open the Command Palette (`Cmd+Shift+P` on macOS, `Ctrl+Shift+P` on Windows/Linux).
2. Type `Package Control: Install Package` and press Enter.
3. Search for `GeminiCLI` and install it.

### Option B: Manual Installation

1. In Sublime Text, go to `Preferences -> Browse Packages...`.
2. Clone the repository into the opened folder:
   ```bash
   git clone https://github.com/flashmodel/gemini-st GeminiCLI
   ```
3. Restart Sublime Text.

## Step 3: Authentication

You must authenticate before using the agent:

1. **CLI Login**: Run `gemini` in your terminal and type `/auth` to login via your Google account.
2. **API Key**: 
   - Get an API Key from [Google AI Studio](https://aistudio.google.com/).
   - In Sublime Text, go to `Preferences -> Package Settings -> GeminiCLI -> Settings`.
   - Set `"api_key": "YOUR_KEY_HERE"`.

Once authenticated, you are ready to go!
