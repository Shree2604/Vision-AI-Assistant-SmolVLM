<div align="center">

# 🤖 VisionAI Camera Assistant

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![WebGPU](https://img.shields.io/badge/WebGPU-Ready-blue.svg)](https://developer.chrome.com/docs/web-platform/webgpu/)
[![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-SmolVLM--500M-orange)](https://github.com/HuggingFaceTB/SmolVLM-500M-Instruct)

<h2>✨ Your camera can now see and understand the world! ✨</h2>

<p align="center">
  <img src="https://img.shields.io/badge/Developed_with_❤️_by-Shreeraj_Mummdivarapu-red?style=for-the-badge&logo=love">
</p>

[LinkedIn](https://www.linkedin.com/in/m-shreeraj) • [GitHub Issues](https://github.com/issues) • [Report Bug](https://github.com/issues/new)

</div>

## 🔍 What is VisionAI Camera Assistant?

<div style="display: flex; align-items: center;">

<div>

VisionAI transforms your ordinary camera into an intelligent AI assistant that can see and understand the world around you! Simply point your camera at anything and ask questions:

- 🌟 **"What am I looking at?"**  
- 🔍 **"How many people are in this room?"**
- 🌈 **"What colors do you see?"**
- 📊 **"Describe everything in this scene"**

Powered by cutting-edge vision-language AI models, VisionAI provides instant answers - **all running directly in your browser with no data sent to external servers!**
</div>

</div>

## 🎬 Live Demo


<div align="center">
  <a href="https://youtu.be/qTJRImG_BQ0" target="_blank">
    <img src="https://img.youtube.com/vi/qTJRImG_BQ0/0.jpg" alt="Watch the demo video" width="80%">
  </a>
  <br/>
  📺 Click the image above to watch the live demo on YouTube.
</div>


## ✨ Key Features

<table>
  <tr>
    <td width="50%">
      <h3>📸 Real-time Visual Analysis</h3>
      <p>Point your camera at anything and get instant insights through natural language questions and answers</p>
    </td>
    <td width="50%">
      <h3>🔒 100% Privacy Guaranteed</h3>
      <p>All processing happens entirely in your browser - no images or data ever leave your device</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🧠 Powered by Advanced AI</h3>
      <p>Utilizes HuggingFace's SmolVLM model, optimized to run efficiently on your device</p>
    </td>
    <td width="50%">
      <h3>🚀 Zero Setup Required</h3>
      <p>No installations, accounts, or complicated setup - just open and start using</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>📱 Works Everywhere</h3>
      <p>Responsive design works on desktops, laptops, tablets and mobile devices</p>
    </td>
    <td width="50%">
      <h3>⚡ Adjustable Performance</h3>
      <p>Control update frequency to balance between performance and responsiveness</p>
    </td>
  </tr>
</table>

## 🚀 Quick Start Guide

1. **Open the application** in a WebGPU-compatible browser (Chrome/Edge 113+)
2. **Grant camera access** when prompted
3. **Type your question** about what the camera sees
4. **Click "Start Analysis"** and watch the AI respond in real-time!
5. **Adjust update frequency** to balance between performance and responsiveness
6. **Click "Stop Analysis"** when you're done to see a thank you page

## 💻 Important: Localhost Required

**Note:** For security reasons, this application is configured to run ONLY on localhost. Direct file access won't work for camera functionality.

### Setting Up Localhost Server

#### Option 1: Using Python (Recommended)

```bash
# Navigate to the project folder
cd path/to/folder

# Start server on port 8000 (Python 3)
python -m http.server 8000

# If using Python 2
python -m SimpleHTTPServer 8000
```

#### Option 2: Using Node.js

```bash
# Navigate to the project folder
cd path/to/folder

# Install http-server globally (one-time setup)
npm install -g http-server

# Start the server
http-server -p 8000
```

##### Fixing PowerShell Execution Policy Error

If you get an error about "running scripts is disabled on this system", you need to adjust the PowerShell execution policy. Here's how to fix it:

**Method 1: For the current PowerShell session only**
```powershell
# Run this in PowerShell as Administrator
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

# Then run http-server again
http-server -p 8000
```

**Method 2: Use cmd.exe instead**
```cmd
# Open Command Prompt (cmd.exe) and run
npx http-server -p 8000
```

**Method 3: Use the full path**
```bash
# Find where http-server is installed and use the direct path
node C:\Users\SHREERAJ M\AppData\Roaming\npm\node_modules\http-server\bin\http-server -p 8000
```

#### Option 3: Using VS Code Live Server

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### After Starting the Server

1. Open your browser and go to: **[http://localhost:8000](http://localhost:8000)**
2. When prompted, **allow camera access**
3. Follow the on-screen instructions

## 🌟 Try asking...

- "What objects are visible?"
- "Is there a person in the frame?"
- "What colors do you see?"
- "Describe this scene"
- "Are there any animals?"

## 🤔 How It Works

1. **WebGPU Technology**: Leverages modern browser capabilities to run AI directly on your device
2. **SmolVLM Model**: A powerful vision-language model optimized for efficient browser execution
3. **Camera Integration**: Captures frames from your device camera in real-time
4. **AI Processing**: Analyzes the visual content and responds to your questions
5. **Privacy Preservation**: All processing happens locally - no data ever leaves your device

## 📜 License

Released under the [MIT License](LICENSE).
