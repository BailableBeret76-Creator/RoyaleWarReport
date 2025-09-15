Complete README.md for RoyaleWarReport
# RoyaleWarReport

**Description:**  
RoyaleWarReport is a dark-themed Python GUI for tracking Clash Royale clan war performance, generating reports, and analyzing player attacks and scores. Perfect for clan leaders and co-leaders to monitor war stats efficiently.

---

## Features
- Paste raw war data from Clash Royale directly into the app.
- Live filtering for:
  - Players meeting requirements ✅
  - Players failing requirements ❌
  - Players using boat attacks 🛶
- Adjustable war settings: minimum war score & max attacks (decks used).
- Scrollable GUI with a large output box for easy reading.
- Save reports as text files for record-keeping.
- Optional: convert to a standalone Windows executable (.exe).

---

## Installation

### 1. Install Python
1. Download the latest Python 3.x from [python.org](https://www.python.org/downloads/).  
2. During installation, **check “Add Python to PATH”**.  
3. Verify installation in Command Prompt:
```cmd
python --version
pip --version

2. Install Dependencies

Open Command Prompt and run:

pip install ttkbootstrap

Usage
1. Run the script

Open Command Prompt.

Navigate to your project folder:

cd C:\ClashTracker


Run the Python GUI:

python wartracker_gui.py

2. Use the GUI

Paste raw war data into the input box.

Adjust war requirements:

Minimum War Score → minimum score for keeping players

Max Attacks (Decks) → number of attacks required

Toggle filters:

Keep ✅

Failed ❌

Boat Attack 🛶

The report updates live as you type.

Save the report by clicking 💾 Save Report as TXT.

Optional: Build a Standalone EXE

Install PyInstaller:

pip install pyinstaller


Navigate to your project folder:

cd C:\ClashTracker


Build the EXE:

pyinstaller --onefile --windowed wartracker_gui.py


The EXE will be located in:

C:\ClashTracker\dist\wartracker_gui.exe


Double-click the EXE to run on any Windows machine without Python.

Optional: Add a custom icon:

pyinstaller --onefile --windowed --icon=icon.ico wartracker_gui.py


Rename the EXE:

pyinstaller --onefile --windowed --name RoyaleWarReport wartracker_gui.py

File Structure

Your project folder should look like this:

C:\ClashTracker
│   wartracker_gui.py
│   README.md
│   requirements.txt

Notes & Tips

Make sure raw war data is copied exactly as displayed in Clash Royale.

Use the scrollable output box to view all players.

Adjust filters to quickly identify players who do not meet requirements.

Reports are saved in .txt format for easy sharing or record-keeping.

For large clans, scroll through the output box for full visibility.