# AI Assistant JavaScript Plugin for Nintex

## Registering the Plugin

**Note**: Nintex does not recommend using this plugin in production environments as the URL may change or be updated to a newer version. For production use, download the plugin (zip file) and upload the JavaScript files to a web server accessible from the internet. An easy deployment method is to use a GitHub repository and a CDN to serve the file to Nintex Automation Cloud.

1. **URL to Control .js File**: `(https://cdn.jsdelivr.net/gh/NTX-XT/Plg-AI-Assistant@main/ai-assistant.js)`
2. **Element Name**: `ai-assistant`
3. **Description** (optional): AI Assistant

## About the AI Assistant

The control allows entering a prompt, which CHAT-GPT interprets. A response is then provided. You can specify a System Prompt or Persona to tailor the response and set the context.

## Design Time Properties

- **OpenAI API Key** (Required): Sign up and get an API Key at OpenAI Platform.
- **AI System Prompt or Persona**: Example, "you are an expert in..."
- **AI Prompt**
- **AI Model**: Options include `gpt-4`, `gpt-4-32k`, `gpt-3.5 turbo`, `gpt-3.5-turbo-16k`.
- **Allow User to Change Role**

## Properties Manipulable with Rules

- **AI Role**
- **AI Prompt**

## Gallery

![Alt](https://ntxtemplatestorage.blob.core.windows.net/assets/Plugins/ai-assistant/thumbnail_image004.jpg)
![ALT](https://ntxtemplatestorage.blob.core.windows.net/assets/Plugins/ai-assistant/thumbnail_image005.jpg)
![ALT](https://ntxtemplatestorage.blob.core.windows.net/assets/Plugins/ai-assistant/thumbnail_image006.jpg)
![Alt](https://ntxtemplatestorage.blob.core.windows.net/assets/Plugins/ai-assistant/thumbnail_image007.jpg)
