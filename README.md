TimeStash, a Chrome extension, elevates your YouTube video-watching experience. 
It enables users to effortlessly create and organize bookmarks, complete with custom notes, at precise timestamps within YouTube videos.

## Table of Contents
- Features
- Getting Started
- Prerequisites
- Installation
- Usage
- Understanding the Code
- Resources
- Contributing
- License
- Support

## Features

1. Generate bookmarks with attached notes
2. Access and organize your saved bookmarks effortlessly
3. Seamlessly navigate to precise timestamps
4. Modify existing bookmarks
5. Remove bookmarks with ease

## Getting Started
Follow these steps to set up the application on your local machine.

## Prerequisites

- Google Chrome Browser

## Installation
1.  Clone this repository into your local machine.
```
https://github.com/MNitin-Reddy/TimeStash-YTBookmarker.git
```
2. Open Google Chrome.
3. Go to `chrome://extensions/`.
4. Enable "Developer mode" in the top-right corner.
5. Click "Load unpacked extension" and choose the folder where you saved the cloned repository.

The extension should now appear in your Chrome toolbar.

## Usage

1. Open a YouTube video.
2. Click the TimeStash icon below the video to create a bookmark.
3. Access your saved bookmarks by clicking the TimeStash icon in your Chrome toolbar.
4. Customize your experience by adding/editing notes, navigating to specific timestamps, and deleting single or all bookmarks.

## Understanding the Code

In this section, the main logic of the extension in the `popup.js` script is explained.

- `showEditModal`: Displays the edit modal for editing the bookmark text.
- `saveEditedNote`: Saves the edited bookmark text.
- `showFullNote`: Displays the full note when the truncated note is clicked.
- `addNewBookmark`: Adds a new bookmark element to the list of bookmarks.
- `viewBookmarks`: Displays all saved bookmarks for the current video.
- `onPlay`: Jumps to the timestamp of the clicked bookmark.
- `onEdit`: Opens the edit modal for the clicked bookmark.
- `onDelete`: Deletes the clicked bookmark.
- `onDeleteAll`: Deletes all bookmarks for the current video.
- `setBookmarkAttributes`: Sets the attributes and event listeners for bookmark controls.

## Resources

- [Chrome Developer Documentation](https://developer.chrome.com/docs/extensions/mv3/)
