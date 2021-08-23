# Create-New-File-In-Finder
Provides an Automator App to create a new empty file in Finder

![E6bbZtaXsAoYMz4](https://user-images.githubusercontent.com/11684330/127069032-cadeea3d-90f6-416c-a88b-8fea723dfd47.jpeg)

# Setup

1. Download the zipped file [`New Text File.zip`](https://github.com/mischa-hildebrand/Create-New-File-In-Finder/raw/main/New%20Text%20File.zip) and unzip it.
2. Open the file `new_file_icon.png` in Preview and copy the image (Command+C).
3. Right-click the file icon of `New Text File.app` and click "Get Info".
4. Select the app icon in the upper-left corner and paste the new icon (Command+V).

   <img width="151" alt="replace_icon_flow" src="https://user-images.githubusercontent.com/11684330/130421376-e3900321-1b11-4fd8-9d31-cfe21efe56b1.png">

5. Command+drag the `New Text File.app` icon to your Finder window's toolbar.

   <img width="336" alt="add_icon_to_toolbar_flow" src="https://user-images.githubusercontent.com/11684330/130421866-21acb3e4-f805-4d94-a01a-9b180de52574.png">


✅ Done!

# Usage

1. Tap the "New Text File" icon in your Finder toolbar.
2. A prompt shows up to enter the filename (including the file extension). The default is `README.md`.
3. When you confirm with "OK", a new empty file with the specified name is created in your current folder loation.

✅ Done!

# Important

The app file was created with Automator and is not signed. For that reason, macOS won't let you open the app by default.

![Screen Shot 2021-08-23 at 11 19 38](https://user-images.githubusercontent.com/11684330/130422933-aae4c9bd-8e3b-4f43-90da-c41eeb649e1d.png)

When you get a security warning after trying to create a new file for the first time, open System Preferences ▶︎ Security & Privacy and click `Open Anyway`.

<img width="726" alt="security_permission" src="https://user-images.githubusercontent.com/11684330/130422698-ef3e33e2-3abd-4a14-bb1f-168cc360e15f.png">

