# Note Taking App

A simple note-taking app that allows users to add, save, and delete notes. The app persists data using **localStorage**, so your notes will remain saved even when you refresh or close the browser.

## Features

- **Add Notes**: Create new notes by clicking the "Add Note" button.
- **Save Notes**: Automatically saves the note content to **localStorage** when the user clicks the save icon or focuses out of the textarea.
- **Delete Notes**: Remove a note by clicking the trash icon next to it.
- **Persistent Data**: Notes are saved in the browser’s localStorage, so they persist even after closing or refreshing the browser.

## How It Works

1. The user clicks the "Add Note" button to create a new note.
2. The user types in the textarea of the note and clicks the save icon or focuses out of the textarea to save the note.
3. To delete a note, the user clicks the trash icon.
4. The app automatically saves the notes to **localStorage** and loads them on page load.

## Setup Instructions

1. Clone or download the repository.
2. Open the `index.html` file in a web browser to start using the app.

## File Structure

```plaintext
├── index.html         # HTML file containing the structure of the note-taking app
├── style.css          # CSS file for styling the app
└── script.js          # JavaScript file that contains the logic for note handling
