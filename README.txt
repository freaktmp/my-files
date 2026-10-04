GREECE ANNUAL CALENDAR  /  ΗΜΕΡΟΛΟΓΙΟ ΑΡΓΙΩΝ ΕΛΛΑΔΑΣ
=====================================================

WHAT YOU HAVE
  GreeceCalendar.exe   the program (about 46 KB, nothing to install)
  GreeceCalendar.cs    the source code
  build.bat            rebuilds the .exe on your own PC if you ever need to

HOW TO USE
  1. Put the folder anywhere you like (Documents, a USB stick...).
  2. Double-click GreeceCalendar.exe.
  3. The first time, Windows may show a blue "Windows protected your PC"
     screen. This is normal for small programs from individuals.
     Click "More info", then "Run anyway".

  If the .exe does not start, or Windows refuses it, do this instead:
  double-click build.bat. It builds a fresh GreeceCalendar.exe on your PC
  using a tool that is already inside Windows (nothing gets installed).
  Wait for "Done!", then double-click the new GreeceCalendar.exe.

YOUR DATA
  Everything is saved automatically, and instantly, in a file called
  greece-calendar-data.json that appears next to the .exe.
  - Copy that file to move your data to another PC (put it next to the .exe).
  - If the folder is not writable, the file goes to
    %AppData%\GreeceCalendar\ instead.
  - Export / Import also read and write this same format, and it is the same
    format the web version uses, so you can move data between them.

IMPORTING A FILE (it will ask you what to do)
  Click Import, choose a .json file, then answer the question:
    Yes    = ADD  - keeps everything you already have and adds what is in
                    the file (new leave days, personal holidays, switched-off
                    holidays). Importing the same file twice adds nothing twice.
                    Your working-days setting is left alone. This is the safe choice.
    No     = REPLACE - your current data is replaced by the file.
                    A backup of what you had is saved first as
                    greece-calendar-data.backup.json (next to the data file).
    Cancel = do nothing.
  Example: you already have 2021-2025 and you import a file that has only
  2026 -> choose Yes, and all six years are kept.

THE CONTROLS
  Year        pick any year from 2000 to 2050
  Size        smaller / bigger window contents (100% = fits the window)
  EN / ΕΛ     switch the whole program between English and Greek
  Theme       light or dark
  Disk icon   save now (it also saves by itself after every change)
  Click a day on the calendar     mark / unmark it as a leave day (green)
  Click a holiday in the list     switch it off for that year only (greyed out)
  Right-click one of your own holidays in the list to remove it
  Working-day buttons             choose which weekdays you work

TO UNINSTALL
  Delete the folder. Nothing else was installed.
