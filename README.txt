Open PowerShell (Windows 10) or Terminal (Windows 11)
Drag GhoulDetector.ps1 onto the window, press enter.

Press the Play button (Capture / Ctrl + E) to Start/Stop capturing events.
Press the Eraser button (Clear / Ctrl + X) to clear the list.

Ideally you should only be capturing during the match loading screen. Killer gets loaded during the last portion of the progress bar.

==============================

If you see a few entries (such as 0-10), it is very likely NOT a Ghoul.
If you see a LOT of entries (such as 30-50), it is very likely a Ghoul.

DC if you want, you have a short window, so I'd have this tool ready and Task Manager ready to end task if it's going off. Make sure to pause capturing outside of lobby countdown/loading screen, as this tool will eat up RAM otherwise as it captures everything your computer does.

==============================

If you get an error similar to "File GhoulDetector.ps1 cannot be loaded. The file GhoulDetector.ps1 is not digitally signed." You can run the below (without the backtick ` symbols), dragging the GhoulDetector.ps1 file where it says to do it.

`Unblock-File -Path (DRAG-GHOUL-DETECTOR-FILE-HERE)`