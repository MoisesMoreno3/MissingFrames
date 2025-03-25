This script helps visual effects artists and compositors quickly detect missing frames in an image sequence directly inside Nuke’s Script Editor. It also identifies temporary .tmp files, which may indicate failed renders.

🔹 Features
✅ Detects missing frames in a sequence
✅ Works with any frame padding format (%04d, ####, ######, etc.)
✅ Supports all file types (.exr, .dpx, .png, .mov, etc.)
✅ Identifies .tmp files in the render folder
✅ Fast and efficient – No unnecessary file system scans

🔹 How to Use (Script Editor Version)
Step 1: Open Nuke
Launch NukeX or Nuke Indie.

Step 2: Select a Read Node
Click on the Read node you want to check for missing frames.

Step 3: Open the Script Editor
Open Nuke’s Script Editor (Alt + F11 / Cmd + F11).

Step 4: Copy & Paste the Script

Step 5: Run the Script

Press Ctrl + Enter (Windows/Linux) or Cmd + Enter (Mac) to execute the script.

A popup window will display missing frames and detected .tmp files.
