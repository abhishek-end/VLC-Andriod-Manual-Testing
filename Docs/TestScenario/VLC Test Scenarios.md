| | | | | | |
|-|-|-|-|-|-|
|Field|Details| | | | |
|REFERENCE|FRS (Functional Requirement Specification)| | | | |
|DOCUMENT NAME|VLC Android App – Test Scenarios| | | | |
|CREATED BY|Abhishek| | | | |
|CREATION DATE|03/08/2025| | | | |
|REVIEWED BY| | | | | |
|APPROVAL DATE| | | | | |
|VERSION|1| | | | |
| | | | | | |
| | | | | | |
|Scenario ID|Module|Scenario Description|Preconditions|Test Type|Priority|
| | | | | | |
|TS_01|Installation & Launch|Verify that VLC successfully installs on different Android devices.|Device with a compatible OS version.|Functional|High|
|TS_02|Installation & Launch|Verify that the app launches without crashing after installation.|Freshly installed app.|Functional|High|
|TS_03|Installation & Launch|Verify that VLC requests necessary permissions (storage, microphone) on first launch.|Freshly installed app.|Functional|High|
|TS_04|Installation & Launch|Verify that VLC updates correctly without losing user settings.|Older version installed.|Regression|Medium|
|TS_05|File Management|Verify that VLC detects and displays all media files from internal and external storage.|Media files available on the device.|Functional|High|
|TS_06|File Management|Verify that users can manually refresh the media library to detect new files.|New files added to storage.|Functional|Medium|
|TS_07|File Management|Verify that VLC allows users to create and delete folders within the app.|VLC app is installed.|Functional|Medium|
|TS_08|File Management|Verify that users can move media files between folders using VLC.|At least two folders exist.|Functional|Medium|
|TS_09|Audio/Video Controls|Verify that users can pause, resume, and stop media playback.|A media file is playing.|Functional|High|
|TS_10|Audio/Video Controls|Verify that VLC allows frame-by-frame playback for videos.|A video is playing.|Functional|Medium|
|TS_11|Audio/Video Controls|Verify that users can mute and unmute audio during playback.|A media file is playing.|Functional|Medium|
|TS_12|Audio/Video Controls|Verify that VLC automatically adjusts aspect ratio based on screen size.|A media file is playing.|UI/UX|Medium|
|TS_13|Background Playback|Verify that VLC continues playing audio when the app is minimized.|An audio file is playing.|Functional|High|
|TS_14|Background Playback|Verify that VLC supports Picture-in-Picture (PiP) mode.|A video is playing.|Functional|High|
|TS_15|Background Playback|Verify that PiP mode can be resized and closed properly.|PiP mode is active.|UI/UX|Medium|
|TS_16|Gesture & Touch Controls|Verify gesture controls for brightness and volume.|A video is playing.|UI/UX|Medium|
|TS_17|Gesture & Touch Controls|Verify that users can lock the screen controls to prevent accidental touches.|A video is playing.|Functional|Medium|
|TS_18|UI/UX|Check if the app supports dark mode.|Dark mode setting is available.|UI/UX|Low|
|TS_19|UI/UX|Verify equalizer settings and audio adjustments.|A media file is playing.|Functional|Medium|
|TS_20|UI/UX|Check if video thumbnails are correctly generated and displayed.|Media files are stored.|UI/UX|Medium|
|TS_21|UI/UX|Verify that subtitles are displayed with correct font size and position.|A subtitle file is loaded.|UI/UX|High|
|TS_22|Usability|Check if the app navigation is intuitive for a new user.|App is freshly installed.|Usability|High|
|TS_23|Usability|Verify that the bottom navigation bar icons are clear and identifiable.|App is open.|Usability|Medium|
|TS_24|Usability|Check if error messages and alerts are user-friendly and descriptive.|App encounters an error (e.g., file not found).|Usability|High|
|TS_25|Usability|Verify that video and audio controls are easily accessible during playback.|A media file is playing.|Usability|High|
|TS_26|Usability|Verify that users can easily enable or disable subtitles.|A subtitle file is available.|Usability|Medium|
|TS_27|Compatibility|Verify that VLC works on different Android versions (e.g., Android 9, 10, 11, 12).|Device with different OS versions.|Compatibility|High|
|TS_28|Compatibility|Verify that VLC adapts to different screen sizes and resolutions.|Devices with different screen sizes.|Compatibility|High|
|TS_29|Compatibility|Verify that VLC runs smoothly on both high-end and low-end devices.|Different devices available.|Compatibility|High|
|TS_30|Compatibility|Verify that VLC supports different device orientations (portrait & landscape).|Device screen is rotated.|Compatibility|Medium|
|TS_31|Compatibility|Verify that VLC properly handles Bluetooth audio output.|Bluetooth headphones connected.|Compatibility|Medium|
|TS_32|Compatibility|Verify that VLC properly handles wired earphones/headphones.|Wired earphones connected.|Compatibility|Medium|
