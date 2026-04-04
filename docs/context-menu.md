# Contextual Interaction & Menus

The strength of Gemini CLI in Sublime Text lies in its ability to understand your code context.

## Right-Click Context Menus

You can interact with Gemini from anywhere in the editor using the context menu:

### 1. Chat with Gemini agent (File Context)
- Right-click inside any file or on a file in the Sidebar.
- The plugin automatically adds an `@filename` reference to the chat.
- This sends the file content as context to Gemini.
- **Selection Support**: If you select code before right-clicking, it adds a precise reference like `@filename#L10-20`.

### 2. Set Gemini Working Space
- Right-click on a **Folder** in the Sidebar.
- This sets the working directory for the Gemini agent.
- When Gemini lists files or searches the project, it will start from this directory.

## Tab Menu
Right-clicking a file tab also provides the **Chat with Gemini agent** option to quickly include that file in your discussion.

## Manual @-mentions
In the chat view, you can manually type `@` followed by a filename to reference specific files. The plugin will resolve these references and provide the relevant content to the AI agent.

By using these menu features, you can precisely control what the AI "sees," ensuring more accurate and relevant responses.
