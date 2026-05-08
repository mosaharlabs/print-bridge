TZ Label Bridge — USB Direct Print Gateway
==========================================

REQUIREMENTS
  - Windows 10 or later
  - Python 3.10 or later (https://www.python.org/downloads/)
    During install: check "Add Python to PATH"

FIRST-TIME SETUP
  1. Double-click start-bridge.bat
  2. It will install the required packages automatically (takes ~30 seconds)
  3. Keep the window open while printing

EVERY TIME AFTER THAT
  Just double-click start-bridge.bat

HOW IT WORKS
  The bridge runs a small local server on your computer.
  The web app detects it automatically and enables the
  "Print Direct (USB)" button for best print quality.

TO STOP
  Close the command window or press Ctrl+C inside it.

AUTO-START WITH WINDOWS (optional)
  Press Win+R, type: shell:startup
  Copy a shortcut of start-bridge.bat into that folder.
