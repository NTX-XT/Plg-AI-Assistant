# AI Assistant JavaScript Plugin for Nintex

## Plugin Information

| JavaScript Element Name | Version | Date       | Evaluation Link |
| ----------------------- | ------- | ---------- | --------------- |
| ai-assistant            | 1.0     | 2023-08-24 | ai-assistant.js |

## Registering the Plugin

**Note**: Nintex does not recommend using this plugin in production environments as the URL may change or be updated to a newer version. For production use, download the plugin (zip file) and upload the JavaScript files to a web server accessible from the internet. An easy deployment method is to use a GitHub repository and a CDN to serve the file to Nintex Automation Cloud.

1. **URL to Control .js File**: `https://plugins.ntxgallery.com/assets/Plugins/ai-assistant/ai-assistant/ai-assistant.js`
2. **Element Name**: `ai-assistant`
3. **Description** (optional): AI Assistant

## About the AI Assistant

The control allows entering a prompt, which is interpreted by CHAT-GPT. A response is then provided. You can specify a System Prompt or Persona to tailor the response and set the context.

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

!AI Assistant Image 1
!AI Assistant Image 2
!AI Assistant Image 3
!AI Assistant Image 4
