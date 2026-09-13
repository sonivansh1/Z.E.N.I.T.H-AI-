# Dynamic Island OS (Zenith AI)

Dynamic Island OS is a powerful, autonomous Windows system assistant that brings the elegant, non-intrusive "Dynamic Island" interface to your desktop. Powered by **Zenith**—an advanced AI routing engine—it acts as a virtual brain for your PC. 

It lives silently at the top of your screen, automatically expanding when media plays, when you receive system notifications, or when you need assistance. You can command it via text or voice, and it has deep administrator-level knowledge of your computer's files, apps, and hardware.

---

## 🌟 Key Features

*   **Deep Hardware Control:** Adjust volume, brightness, and toggle system settings (Wi-Fi, Bluetooth, Airplane Mode, Battery Saver) directly via voice or text.
*   **System Telemetry:** Ask Zenith what is eating up your RAM, and command it to force-close misbehaving applications. Keep track of CPU, GPU, and Battery stats on the fly.
*   **Context-Aware Clipboard:** Copy a massive block of text from any website or document, trigger the Island, and simply ask it to "Summarize what I just copied" or "Translate my clipboard".
*   **Workflow Orchestration:** Command the AI to open installed apps, search the web, or navigate directly to specific websites.
*   **File System Management:** Ask Zenith to create text or code files on your Desktop from your voice dictation, or have it create and delete directories for you.
*   **Automated UI:** The Island smoothly tracks your mouse, expanding fluidly into a command console. It even automatically detects when you play music or videos (Spotify, YouTube, etc.) and elegantly splits into a media visualizer!

---

## 🚀 Installation & Setup Guide

### Step 1: Extract the Application
Since the AI requires heavy processing libraries to function, the application is bundled inside a folder.
1. Download and extract the `DynamicIsland` folder to your computer.
2. Inside the folder, locate the `DynamicIsland.exe` file.
3. *(Optional)* Right-click `DynamicIsland.exe`, select **Show more options > Send to > Desktop (create shortcut)** for easy access.

### Step 2: Get Your AI Brain (API Key)
To allow the AI to think and process your commands, you need a free Groq API key.
1. Go to [console.groq.com](https://console.groq.com) and create a free account.
2. Click on **API Keys** in the left menu and generate a new key. Copy it to your clipboard.

### Step 3: Connect the AI
1. Double-click `DynamicIsland.exe` to launch the application. The Island will appear at the top of your screen.
2. Because it is your first time running the app, it will generate a hidden configuration file on your computer.
3. Open your File Explorer and navigate to your user profile folder (e.g., `C:\Users\YourName`).
4. Find the file named `.dynamic_island_settings.json` and open it with Notepad.
5. Find the line that says `"groq_api_key": ""` and paste your API key inside the quotes. It should look like this:
   `"groq_api_key": "gsk_your_api_key_here"`
6. Save the file and restart Dynamic Island.

### Step 4: You're Ready!
Hover your mouse over the Island to expand it! You can click the microphone icon to speak naturally to Zenith, or type commands directly into the text box.

**Try asking:**
*   *"What is eating up my RAM right now?"*
*   *"Search the web for the weather in Tokyo."*
*   *"Set my volume to 50% and minimize all my windows."*
