# 📚 myLibraryAssistant by mp3li

A macOS desktop companion (Windows and Linux coming soon) for Libby readers and listeners who want their loans saved locally with full metadata, covers, and clean organization. Built to keep everything on your device — no clouds, no subscriptions, just your audiobooks and eBooks. ✨
Designed as an alternative for people who love Calibre but want something that handles ebooks and audiobooks beautifully right out of the box. Or should I say, right out of the zip. Specifically made in mind for those who need to own their files for mp3 players and e-readers.

## 📦 Download
👉 Download the pre-release for macOS in the Releases section of this repo.

## 🧠 About
This repo hosts the compiled public build.
Source code and assets remain private. 

## ⚖️ License
© 2025 mp3li. All Rights Reserved.

## Description

Desktop app that connects to Libby using your “Copy to Another Device” code and lets you archive your borrowed audiobooks and eBooks locally with metadata, covers, and organized folders. Specifically made for people who want everything stored on their own device with clean structure and no cloud requirements. And for people who need to own their files for mp3 players and e-readers.

myLibraryAssistant lets you:

• Connect to Libby using the “Copy to Another Device” code  
• View all library cards, audiobooks, and eBooks in one place  
• Archive audiobooks into folders containing MP3 parts, metadata.json, and cover art  
• Archive eBooks by saving ACSM/EPUB/PDF files into organized “Title by Author (eBook)” folders  
• Import existing HAR or ACSM/EPUB files and process them instantly  
• Keep everything tidy inside your “myLibraryAssistant Archive” folder, which includes:
      • myAudiobooks
      • myeBooks
      • Book Files
      • HAR Files

Everything runs locally using your Chrome profile. Your Libby shelves stay exactly the same — this app only saves what you already borrowed.

## Features

• Connect to Libby using the eight-digit “Copy to Another Device” code

• Multi-card dashboard showing all current loans by library, with filtering

• Chrome windows open for each selected audiobook/eBook so you can manually save the needed HAR or ACSM/EPUB/PDF files

• Import HAR or Import ACSM/EPUB buttons for processing files you already have

• Metadata extraction for title, author, narrator, publisher, description, cover art, reading order, and more

• Organized output folders:
      • Title by Author (Audiobook) — MP3 parts, metadata.json, cover.jpg
      • Title by Author (eBook) — EPUB/PDF, metadata.json, cover.jpg

• “Add Metadata” rescans your archive folders and refreshes tags/covers

• Built-in help screen explaining the setup process and how to save HAR or ACSM files manually

## 🖥️ Requirements

• macOS with Python 3.11+ recommended  
• Google Chrome installed  
• All dependencies are listed in requirements.txt

### How to install requirements (macOS)
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 app.py

### Windows
(Not supported yet — coming soon.)

### Linux
(Not supported yet — coming soon.)

## How to use:

Instructions:

- How to run the app:
Activate your virtual environment (if using one) and run python3 app.py. The window titled “myLibraryAssistant by mp3li” opens with the splash/connect screen.

- How to connect to Libby:
On the device where you already use Libby, tap “Copy to Another Device,” choose “Are you connecting to Sonos speakers?”, and enter the eight-digit code into the app. Your library cards and loans appear. They refresh automatically.

- How to create/select an archive folder:
Click “Create/Select myLibraryAssistant Archive.” Choose or create a folder. The app generates myAudiobooks, myeBooks, Book Files, and HAR Files inside it. After setup, the button becomes “Open myLibraryAssistant Archive.”

- How to archive audiobooks:
Select one or more audiobooks, click Archive, and Chrome opens each Listen link. Save your HAR files into HAR Files. When finished, click Done and the app processes, downloads, tags, and organizes everything.

- How to archive eBooks:
Select your eBooks, click Archive, and Chrome opens each Libby download page. Save ACSM/EPUB/PDF files into Book Files. On Done, they are processed into myeBooks with covers and metadata.

- How to use Import buttons:
• Import HAR: Instantly process existing HAR files
• Import ACSM/EPUB/PDF: Instantly process eBooks you already downloaded

- How to refresh metadata:
Click “Add Metadata” to rescan audiobook/eBook folders and refresh anything newly added.

- How to log out:
Click Log Out to remove the saved Libby device code. Reconnect anytime.

- Note:
The app never deletes stored loan data. All JSON files are kept in myJsons so you can reference them anytime.

## Note from mp3li

Thank you so much for using myLibraryAssistant! I’m a full-time software development student and single parent, and I release these tools for free so listeners and readers (especially kids) can have screen-free reading and listening experiences. If there’s another companion app you’d like to see made for free, please let me know!

## Additional app screenshots

(Your screenshots go here.)
