# Tab Slideshow Chrome Extension

**Tab Slideshow** is a customizable Chrome extension that automatically cycles through tabs and refreshes inactive ones using a configurable GitHub URL source. Ideal for kiosk displays, dashboards, and productivity tools.

---

## 🚀 Features

- 🔄 **Auto-Rotation** of tabs at a user-defined interval
- 🕓 **Auto-Refresh** of non-active tabs on a timer
- 🌐 **Startup URLs** loaded from a public GitHub raw JSON file
- 🖥️ Launches in **fullscreen or maximized** mode
- 🧠 Remembers all settings using Chrome sync storage
- 🟢 Optional **auto-start** on Chrome launch
- ✅ Validates JSON format before launching
- 🎛️ Dynamic popup interface with real-time status

---

## 🔧 Installation

1. Install the Extension:
2. Setup a publicly available .json file like [example-url-file.json](https://github.com/dudeguy999/Tab-Slideshow/blob/main/example-url-file.json)
3. If the file is a Github file. Ensure to copy the link to the Raw file for this to work. The publicly available file should be a json file. Ensure the refresh time differs by an odd number with the rotate time. 

## 📒 Notes

## 🖼️ My Use Case

In my use case. I setup the following:
1. A Windows 11 non-domain computer connected to a TV. (I always had issues with AutoLogon so opted to remove the computer for the domain)
2. Remove Password from user account, ensure the computer logs in without sign-in
3. Setup a Task Sequence that opens Google Chrome on Startup with this command: '"C:\Program Files\Google\Chrome\Application\chrome.exe" --hide-crash-restore-bubble'
4. Setup the publicly available JSON in preferably github. Add your URLs in the format as previously mentioned.
5. Setup the Tab Slideshow Extension with the link to the JSON and the other options.
6. Should be good to go! 
