# Screen Recorder Web Application

A powerful and user-friendly web-based screen recording application that enables users to capture their screen content with flexibility. Choose between recording your entire monitor, specific application windows, or browser tabs with audio support. Built with vanilla JavaScript and HTML5, this tool runs entirely in your browser - no server uploads required. The entire application is contained in a single HTML file, making it fast, secure, and privacy-friendly since all processing happens locally on your device.

![Screen Recorder Demo](images/screenrecorder.gif)


🔴 [Try Live Demo](https://dylansallred.github.io/Screen-Recorder/Screen-Recorder.html)

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
  - Real-time file size display
  - Preview toggle during recording

- **Quality Settings**
  - Ultra quality (12-20 Mbps)
  - High quality (8-12 Mbps)
  - Medium quality (4-8 Mbps)
  - Low quality (2-4 Mbps)
  - Lowest quality (1-2 Mbps)

- **Format Options**
  - WebM (with automatic duration fix)
  - MP4 (automatically selected for Safari)

- **Playback Features**
  - Built-in video player
  - Advanced playback controls
    - Play/Pause
    - Seek bar with drag support
    - Time display
    - Duration display

- **Recording Management**
  - Save recordings with custom names
  - Comprehensive recording history
    - Filename
    - Recording type indicator
    - Date and time
    - File size
    - Recording duration
  - Download recordings
  - Delete individual recordings
  - Delete all recordings
  - Storage usage indicator
  - Collapsible history panel

- **Storage Features**
  - IndexedDB storage for recordings
  - Storage usage monitoring
  - Visual storage capacity indicator
  - Automatic storage quota management

- **Browser Compatibility**
  - Automatic format selection for Safari
  - Browser-specific optimizations
  - Fallback options for unsupported features

## Technical Requirements

- Modern web browser with support for:
  - `MediaRecorder` API
  - `getUserMedia` API
  - `IndexedDB`
  - ES6+ JavaScript
  - Screen Capture API

## Keyboard Shortcuts

- `Ctrl + R`: Start recording
- `Ctrl + S`: Stop recording
- `Space`: Pause/Resume recording (when recording is active)

## Browser Compatibility

- Google Chrome (recommended)
- Microsoft Edge
- Firefox
- Opera
- Safari (limited support with automatic MP4 format selection)

Note: Safari has limited support for some screen recording features. For best results on macOS, we recommend using Chrome or Firefox.

## Installation

1. Clone the repository:
