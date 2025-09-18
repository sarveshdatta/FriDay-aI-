# Friday - Personal Voice Assistant

**Friday** is a Python-based voice assistant that allows you to control your system, open apps, websites, and manage settings like Wi-Fi, Bluetooth, and brightness — all with natural voice commands. Think of it as your personal desktop assistant!

---

## Features

* Open installed applications (e.g., Discord, VS Code, Terminal, Firefox, Chrome, Files, etc.)
* Launch popular websites directly (e.g., ChatGPT, YouTube, LinkedIn, Amazon, WhatsApp)
* Search Google for unknown commands
* Close applications
* Control system settings:

  * Turn Wi-Fi and Bluetooth on/off
  * Adjust screen brightness
* Voice feedback using a natural text-to-speech engine
* Easy to extend with custom commands

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/sarveshdatta/FriDay-aI-.git
```

2. **Install dependencies**

```bash
pip install speechrecognition pyttsx3
sudo apt install espeak ffmpeg libespeak1 portaudio19-dev python3-pyaudio
```

3. **Run Friday**

```bash
python3 friday.py
```

> Make sure your microphone is working and your system has Python 3 installed.

---

## Usage

* Say commands like:

  * `"Open discord"` → opens Discord
  * `"Close firefox"` → closes Firefox
  * `"Wi-Fi on"` → turns Wi-Fi on
  * `"Brightness 50%"` → sets brightness to 50%
  * `"Open chatgpt"` → opens ChatGPT in Chrome

* To exit: `"quit"`, `"exit"`, or `"goodbye"`

---

## Notes

* Supports English (India) accent by default (`en-IN`).
* Designed for Linux systems using GNOME or similar environments.
* Can be extended by adding more apps and websites in the `app_commands` and `special_websites` dictionaries.

---

## Contribution

Feel free to fork the project and add more functionality like media control, system monitoring, or AI integrations!

