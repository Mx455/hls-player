# hls-player

Here is the complete list of all features available in your HLS TV Player web app:

🎥 HLS Video Player

Supports HLS (M3U8) streams using HLS.js.
Auto-play the loaded stream.
Play/Pause button with the spacebar shortcut.
Full-Screen mode support (button or F key).
Picture-in-Picture (PiP) (browser-native support).

🌐 URL Management & Sharing

Load video via URL (?stream=URL): If a user opens the link with an M3U8 stream, it starts playing automatically.
Dynamic URL update whenever a new stream is loaded.
QR Code generation for easy stream link sharing.

📋 Channel List

Predefined list of channels with test M3U8 streams.
Click on a channel to update the video player with the selected stream.

💾 Customization & Saving

Custom link input: Users can paste their own M3U8 link and play it.
Save favorite channels using localStorage (for quick reloading of preferred links).
Remote control (future possibility to interact from multiple devices in the same session).

🖥️ User Interface & Controls

Dark Mode by default, with a black background and white text.
Control buttons for:
Load a link (Load).
Save a link (Save).
Activate Full-Screen mode (Fullscreen).
Generate a QR Code (QR Code).
Keyboard Shortcuts (Hotkeys):
F → Toggle Full-Screen.
Space → Play/Pause.
Arrow Up/Down → (Potential volume control implementation).
