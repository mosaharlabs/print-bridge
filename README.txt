Mosahar Print Bridge — USB Direct Print Gateway
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

CHOOSING A PRINTER (v1.2.0+)
  In the web app's "Print Barcodes (V4)" screen, pick your label
  printer from the dropdown next to "Print Direct (USB)". The bridge
  sends the job to exactly that printer.

TROUBLESHOOTING — "File saved to Documents" instead of printing
  This means the job went to a PDF/file printer, not the label
  printer. Either:
    - In V4, select the correct thermal printer in the dropdown, OR
    - Set your label printer as the Windows DEFAULT printer
      (Settings > Bluetooth & devices > Printers > turn OFF
       "Let Windows manage my default printer" > pick the label
       printer > Set as default).

TO STOP
  Close the command window or press Ctrl+C inside it.

AUTO-START WITH WINDOWS (optional)
  Press Win+R, type: shell:startup
  Copy a shortcut of start-bridge.bat into that folder.
