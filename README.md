# Screen Recorder Web Application

A powerful and user-friendly web-based screen recording application that enables users to capture their screen content with flexibility. Choose between recording your entire monitor, specific application windows, or browser tabs with audio support. Built with vanilla JavaScript and HTML5, this tool runs entirely in your browser - no server uploads required. The entire application is contained in a single HTML file, making it fast, secure, and privacy-friendly since all processing happens locally on your device.

![Screen Recorder Demo](images/screenrecorder.gif)


🔴 [Try Live Demo](https://dylansallred.github.io/Screen-Recorder/screenrecorder.html)

## Features

- **Multiple Recording Options**
  - Full screen recording
  - Application window recording
  - Browser tab recording
  - System audio capture

- **Recording Controls**
  - Start/Stop recording
  - Show/Hide preview
  - Recording timer
  - File size indicator

- **Quality Settings**
  - High quality (3 Mbps)
  - Medium quality (1.5 Mbps)
  - Low quality (800 Kbps)

- **Format Options**
  - WebM
  - MP4

- **Playback Features**
  - Built-in video player
  - Playback controls (play/pause)
  - Seek bar
  - Time display

- **Recording Management**
  - Save recordings with custom names
  - Recording history
  - Delete individual recordings
  - Delete all recordings
  - Display recording details (size, type, date)

## Technical Requirements

- Modern web browser with support for:
  - `MediaRecorder` API
  - `getUserMedia` API
  - `IndexedDB`
  - ES6+ JavaScript

## Keyboard Shortcuts

- `Ctrl + R`: Start recording
- `Ctrl + S`: Stop recording
- `Space`: Pause/Resume recording (when recording is active)

## Browser Compatibility

- Google Chrome (recommended)
- Microsoft Edge
- Firefox
- Opera

Note: Safari has limited support for some screen recording features.

## Installation

1. Clone the repository:
