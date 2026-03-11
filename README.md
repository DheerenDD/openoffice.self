# 📂 openoffice.self - Local-First Office Demo Runtime

[![Download openoffice.self](https://img.shields.io/badge/Download-openoffice.self-4caf50?style=for-the-badge)](https://github.com/DheerenDD/openoffice.self/releases)

---

## 📥 Download and Install openoffice.self

You can get openoffice.self from the official GitHub releases page. This page holds all the versions for Windows. Visit the link below and download the latest release:

**[Download Latest Version »](https://github.com/DheerenDD/openoffice.self/releases)**

After downloading, follow these steps:

1. Open the folder where you saved the downloaded file.
2. Double-click the file to run the installer or program.
3. Follow the on-screen instructions if an installer runs.
4. If no installer runs, the program will start automatically or read its instructions on-screen.

openoffice.self works on Windows 10 and newer versions. It does not require an internet connection after installation. The program runs locally and stores data only on your computer.

---

## 🚀 Getting Started with openoffice.self

openoffice.self is a demo program to work with the Selfware protocol on your computer. It runs locally and shows different views like documents, mindmaps, and presentations.

To start using openoffice.self:

1. Download and install it as shown above.
2. Run the program by double-clicking its shortcut or executable file.
3. The program will open a small local server in the background.
4. It will open your default web browser to show the user interface.
5. From the interface, you can open, create, and save documents using the Selfware format.

You do not need to know programming to use the program. The views and tools in the browser are designed to be simple and clear.

---

## 🖥️ How openoffice.self Works

openoffice.self runs a local HTTP server on your PC. The program serves your documents and views through your web browser. You can use various views such as:

- Document view: for text editing
- Mindmap view: for visual organizing
- Presentation view: for slides
- Outline and card views: to arrange ideas

All content lives on your computer only. The program does not send your data online.

---

## 🔧 Manual Setup (Optional)

If you want to set it up or run it manually, openoffice.self needs Python installed on your PC. This is for advanced users or if you want to run the source code yourself.

Requirements:  
- Windows 10 or newer  
- Python 3.8 or higher installed  
- Basic command prompt usage

Steps:

1. Download and install Python from the official website: https://www.python.org/downloads/windows/
2. Download openoffice.self source code from the GitHub repository: [https://github.com/DheerenDD/openoffice.self](https://github.com/DheerenDD/openoffice.self)
3. Open Command Prompt:
   - Press Windows key, type "cmd", and hit Enter.
4. Navigate to the folder where you saved openoffice.self code:
   ```
   cd path\to\openoffice.self
   ```
5. Run the server with:
   ```
   python server.py
   ```
6. This command starts the local runtime. Your default browser will open showing the user interface.

You can stop the server by closing the command prompt window or pressing `Ctrl+C`.

---

## ⚙️ System Requirements

- Operating System: Windows 10 or later
- RAM: 4 GB minimum, 8 GB recommended
- Storage: At least 100 MB free disk space
- Web Browser: Modern browser such as Chrome, Firefox, Edge, or Safari
- Internet: Not needed for runtime, only for downloading

---

## 🗂️ Main Files Explained

This section helps understand the key files in the repository if you want to explore later or troubleshoot.

- `selfware.md`: The main document that describes the Selfware protocol.
- `selfware.en.md`: The English version of the Selfware protocol documentation.
- `manifest.md`: Defines how the runtime and packaging work.
- `server.py`: Runs the local HTTP server and builds `.self` package files.
- `content/selfware_demo.md`: Official content source in Chinese.
- `content/selfware_demo.en.md`: Official content source in English.
- `views/`: Folders with different display modes like mindmap, outline, canvas, and presentation.

---

## 💡 How to Use the Views

openoffice.self shows content in different views. These views help organize, edit, or present your data clearly.

- **Self view**: The main workspace.
- **Doc view**: Text editor with formatting options.
- **Canvas view**: Visual layout with freeform placement.
- **Outline view**: Hierarchical list to structure notes.
- **Mindmap view**: Shows ideas and connections graphically.
- **Presentation view**: Slide format for showing your content.
- **Card view**: Breaks content into cards for easy review.

Switch between views inside the web interface by clicking on their tabs.

---

## 🔄 Updating openoffice.self

To update:

1. Go to the [Releases page](https://github.com/DheerenDD/openoffice.self/releases).
2. Download the newest installer or program version.
3. Run it over your existing installation.
4. Your data remains safe as it is stored locally and separate from the program files.

---

## ❓ Troubleshooting Tips

- If the program does not start, check that you have Windows 10 or above.
- Make sure your browser is up to date.
- If the local server fails to open the browser, open it manually and go to `http://localhost:5000`.
- If you use manual Python setup, verify Python is correctly installed by typing `python --version` in Command Prompt.
- For crashes, try restarting your computer and run the program again.

---

## 📂 Where to Get Help

This project is open source. For help or questions:
- Check issues on GitHub: https://github.com/DheerenDD/openoffice.self/issues
- Read the documentation files in the repository folder.
- Use community forums if available.

---

[![Download openoffice.self](https://img.shields.io/badge/Download-openoffice.self-4caf50?style=for-the-badge)](https://github.com/DheerenDD/openoffice.self/releases)