<img width="150" height="150" alt="myAudiobookBinderIcon" src="https://github.com/user-attachments/assets/8e836418-ad15-4d14-b31e-84be7e38b018" />


![appscreen1](https://github.com/user-attachments/assets/39a1f2fa-7986-4b1c-a86c-60069a93e3f4)

# 🎧 myAudiobookBinder by mp3li

A simple macOS app for binding audiobooks and metadata — aesthetic, local, and private. Made for iPod and mp3 player lovers in mind. 💿

## 📦 Download
👉 [Download the latest macOS build](./myAudiobookBinder-mac.zip)

## 🧠 About
This repo hosts the compiled public build.  
Source code and assets remain private.

## ⚖️ License
© 2025 mp3li. All Rights Reserved.

## Description

Desktop app to combine multiple MP3 files into a single audiobook with metadata and optional cover art. Specifically made for iPod/mp3 player purposes, I couldn't find one for free with these specific features. Supports output formats `m4b`, `m4a`, and `mp3`. I included the other output formats specifically for picky and even pickier mp3 players. Includes a ton of options for adding metadata and sorting options for tracks and the ability to add and crop cover art. Packaged into an .app that runs on macOS. Windows and Linux versions coming soon. 

## Features
• Import multiple .mp3 files at once

• Import your own cover art 

• Auto imports the cover art already embedded into the imported .mp3's, and you can delete it to add a new one if you want

• Crop cover art automatically to a square or rectangle, or click and drag to create your own cropped selection

• Adds your input book info as metadata for media managers like iTunes, and also for mp3 players

• Adds these metadata/input fields:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Book title
    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Book author
    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• If the book is part of a series or not

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Title of series, if it's in a series

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Which number in the series the book is

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• How many books in series

• Sorting options for your imported .mp3 files:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Move up selected track

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Move down selected track

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• A-Z

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Z-A

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Date added (for situations where the filenames make no sense but they were downloaded in the right order)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Can process unlimited audiobooks at the same time - click the '+' button to open a new window

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• File names are saved in this format: (Title) by (Author) while maintaining separate title and author metadata, for organizational purposes

<details>
<summary><h2>🖥️ Requirements</h2></summary>

## Requirements
- Python 3.10+ recommended.
- Dependencies: see `requirements.txt`.

## How to install requirements:
#### On macOS
- `python3 -m venv .venv`
- `source .venv/bin/activate`
- `pip install -r requirements.txt`
- `python3 myAppThings/Scripts/app.py`

#### On Windows
- `py -3 -m venv .venv`
- `.venv\Scripts\activate`
- `pip install -r requirements.txt`
- `python myAppThings\Scripts\app.py`

#### On Linux
- `python3 -m venv .venv`
- `source .venv/bin/activate`
- `pip install -r requirements.txt`
- `python3 myAppThings/Scripts/app.py`

</details>

## How to use:

**Instructions:**

- __How to run app:__ Double click the myAudiobookBinder by mp3li app icon.

- __How to start:__ Start by either inputting the information about the audiobook, or by importing the audio files, whichever you want to do first.
  
- __How to input audio files:__ Click the Import Audio Files button, then the large white area where it says click here to add files, and a window will pop up allowing you to select your files. Select all of your files at the same time by either shift clicking or click and dragging a selection.
  
- __How to add audiobook info:__ Fill out/type the information about the audiobook: title, author, if its part of a series, which book number of the series its in, how many books are in the series, and the series name.
  
- __Note:__ The saved files will be saved in this format: (Title) by (Author) for example, Harry Potter by JK Rowling. The metadata will maintain the actual book title and author title seperatley, but the file name will be (Title) by (Author) format.
  
- __How to add cover art:__ Click import cover art, and then double click the large white area to open the selection window to choose your cover art.
  
- __How to crop cover art:__ Select either square or rectangle on the right side buttons, and then either drag the auto created selection or, it may be easier to click and drag to create your own cropped selection. Moving the auto created selection is a bit buggy and will be fixed soon. You can also delete the art with the trash button, and then add new art. Also, if your chosen starter mp3 files already had art, it will be added to the cover art screen but you can delete it and add your own if you'd like.

- __How to choose file type:__ Click the drop down for the format type and select either m4b, m4a, or mp3. M4b is standard and reccomended for most uses. m4a is for some picky mp3 players such as the Innioasis Y1. mp3 is for even pickier mp3 players that only play mp3 files.
  
- __How to sort audio files:__ Use the buttons on the right side in the audio importing window to sort your audio files. Options include A-Z, Z-A, by date added, and you can also select files and move them manually up or down with the arrow buttons, and delete specific files manually with the trash icon button.
  
- __How to create/process more than one audiobook at a time:__ Click the plus sign + button to open an additional window for creating another audiobook file. There is no limit on how many you can process at the same time! Also, when the file finishes, click the plus + sign to create another file if you'd like to make more.
  
- __How to bind your mp3s and create your audiobook file:__ Click the Bind! button to create your file. The duration depends on how long the files are/how many files you have selected. The bottom left of the screen  displays which file it is currently processing, with a loading bar underneath. For example: Loading... 1 out of 20.
  

**Note:**

Thank you so much for using my app! This is my first app; I'm genuinely so glad you're here. I'm a software developer student, and I currently cannot charge for any of my work or I risk losing access to having my tution covered completely. My education is what enables me to make apps like this, and this is just the beginning. I hope you enjoy my free apps, and that in a few years once I can charge for even cooler things, you'll be a first user then, too.

If theres any other apps you would like to see made for free please let me know! 

## Additional app screenshots: 
![screen2](https://github.com/user-attachments/assets/7af170b6-6e69-4b16-ba22-16444f7659af)

![screen4](https://github.com/user-attachments/assets/b2c6a470-73e8-4f5d-b71e-6fac9553052c)

![screen3](https://github.com/user-attachments/assets/2db0f4fb-1b1d-47bd-a8fc-daf7f25e4d13)

![apploadingscreen](https://github.com/user-attachments/assets/55a6b126-3e27-4378-bf96-8322fb6dcb95)






