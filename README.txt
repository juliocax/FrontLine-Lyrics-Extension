========================================================================
                         FRONTLINE LYRICS
========================================================================
Version: 0.0.1
Tech Stack: Python (Flask), JavaScript, Chrome Extension (MV3)
License: Open Source
------------------------------------------------------------------------

1. INTRODUCTION
FrontLine Lyrics is an open-source tool that brings live, synchronized 
lyrics straight to your browser. It automatically identifies the song 
currently playing on your computer's audio and displays its lyrics in 
a floating, draggable overlay.

2. KEY FEATURES
* Automatic Recognition: Identifies music via system audio loopback.
* Synchronized Lyrics: Fetches time-synced lyrics from LRCLib.
* Floating UI: A draggable overlay injected via Shadow DOM (won't 
  interfere with the website's original layout).
* Manual Control: Built-in search and fine-tuning sync options.
* Privacy-First: No audio data is saved or transmitted. It only uses 
  an anonymous digital fingerprint for song recognition.

3. INSTALLATION & USAGE GUIDE

STEP 1: Installing the Server (Backend)
1. Locate the "FrontLineLyrics.exe" file in this folder.
2. Double-click to run the application.
3. WINDOWS ALERT: Since this is an independent app, Windows SmartScreen 
   might show a "Windows protected your PC" warning. Click "More info" 
   and then click "Run anyway".
4. Check the System Tray (near the clock). You should see the FrontLine 
   Lyrics icon there, meaning the server is running successfully!

STEP 2: Installing the Browser Extension
The extension must be loaded manually (Developer Mode):
1. In Chrome/Edge, go to the Extensions page (chrome://extensions).
2. Toggle "Developer mode" ON in the top-right corner.
3. Click "Load unpacked".
4. Select the extension folder that came with this package.
5. TIP: Click the "puzzle piece" icon and Pin FrontLine Lyrics for 
   easy access.

STEP 3: How to Use
1. Open any standard website (e.g., google.com, youtube.com).
2. Click the extension icon and accept the initial privacy prompt.
3. Play a song on your PC and click the "Listen" button in the panel.
4. The lyrics overlay will appear! You can drag it anywhere or press 
   Alt+M to hide the control panel.

4. TROUBLESHOOTING & FAQ

- "Server Offline": Make sure FrontLineLyrics.exe is actually running.
- "Lyrics not found": If the song is very obscure, use the "Search 
  Lyrics" button to find it manually.
- Out of Sync: Use the "Manual Sync" button and click the exact line 
  being sung to adjust the timing instantly.
- Extension won't open: The extension only works on live websites. 
  It cannot run on empty tabs or browser settings pages.

------------------------------------------------------------------------
Developed by Júlio César Albuquerque Xavier.
========================================================================