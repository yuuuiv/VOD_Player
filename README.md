# VOD_Player

A simple Video-on-Demand (VOD) player built with Video.js for streaming HLS videos.

## Features

- Full-screen video playback optimized for various devices
- Keyboard shortcuts: Space (play/pause), Left/Right arrows (rewind/fast-forward 5 seconds), S (screenshot)
- Touch gestures on mobile: Swipe left (rewind), swipe right (fast-forward)
- Screenshot functionality with camera icon button in the control bar
- Progress memory: Remembers last playback position using localStorage
- Responsive design with no scrollbars or borders

## Usage

1. Open any HTML file in the `roselia/` directory (e.g., `250215.html`) in a web browser.
2. The video will load and play automatically (autoplay is disabled for VOD).
3. Use the controls or shortcuts to interact with the video.

## Requirements

- A modern web browser with JavaScript enabled
- Internet connection for streaming videos

## Technologies Used

- [Video.js](https://videojs.com/) - HTML5 video player
- HLS streaming support via videojs-http-streaming