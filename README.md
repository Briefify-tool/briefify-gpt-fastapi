# Briefify - YouTube Video Summarizer

**Briefify** is a Chrome extension that provides concise summaries of YouTube videos, leveraging the power of GPT via an API. Currently, the extension is not published on the Chrome Web Store, so you will need to clone the repository and manually install the extension.

## Demo Video
[Watch the demo video here](https://youtu.be/15rDwxD_QXE)

## Installation Guide

### 1. Clone the Repository
First, you'll need to clone the repository to your local machine.

```bash
git clone https://github.com/Briefify-tool/briefify-gpt-fastapi.git
```
### 2. Create and Update the .env File
Before you can use the extension, you need to create a .env file in the root directory of the cloned repository and add your API key.

In the root of the cloned repository, create a new file named .env.
Open the .env file and add the following line:

```bash
API_KEY=your_openai_api_key_here
```

Replace your_openai_api_key_here with your actual OpenAI API key.

### 3. Pack the Extension Locally
Chrome extensions need to be packed before they can be installed in the browser.

Open Chrome and navigate to chrome://extensions/.
Enable Developer mode by toggling the switch in the top right corner.
Click on Load unpacked.
Browse to the location of the cloned repository and select the folder.
The extension should now appear in your Chrome extensions list, and you can start using it.

### 4. How to Use
After installing the extension, you'll see the Briefify icon in your Chrome toolbar.
Go to any YouTube video.
Click on the Briefify icon to get a summary of the video.

### 5. Contributing
If you want to contribute to this project:

Fork the repository.
Create a new branch.
Make your changes.
Submit a pull request.

