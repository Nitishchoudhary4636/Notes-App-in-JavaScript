# Note-Taking Web App

This project is a simple and responsive note-taking web application built using HTML, CSS, and JavaScript. It allows users to create, update, and delete notes, storing them locally in the browser using `localStorage`.

## Features

- **Add New Notes**: Users can create a new note by clicking on the "Add new note" box.
- **Edit Existing Notes**: Users can update notes, which will save their changes in `localStorage`.
- **Delete Notes**: Users can delete a note, with a confirmation prompt before removal.
- **Responsive Design**: The app is designed to work on various screen sizes.

## Project Structure

- **HTML**: Basic structure of the application, including a popup for adding and editing notes.
- **CSS**: Styling and responsive design.
- **JavaScript**: Core logic for creating, updating, and deleting notes, as well as managing `localStorage`.

## How It Works

1. **Adding Notes**:
   - Click on "Add new note" to open the popup.
   - Fill in the title and description fields.
   - Click "Add Note" to save the note in `localStorage`.

2. **Updating Notes**:
   - Click on the three-dot icon on a note, and select "Edit" to open the note in the popup.
   - Update the title or description, then save to update the note in `localStorage`.

3. **Deleting Notes**:
   - Click on the three-dot icon on a note, and select "Delete" to remove it.
   - Confirm deletion when prompted.

4. **LocalStorage**:
   - Notes are stored in `localStorage`, allowing data to persist even when the page is refreshed or closed.
   - Notes are displayed automatically from `localStorage` when the app is loaded.

## Files Included

- **index.html**: Main HTML file that contains the structure of the application.
- **style.css**: Styles for the layout, colors, fonts, and responsiveness.
- **script.js**: JavaScript file that handles adding, updating, deleting, and displaying notes.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/note-taking-app.git
   ```
   
2. Open `index.html` in your browser to view and use the app.

## Screenshots

### Main View
Displays all saved notes with options to edit or delete.

### Popup
A modal popup for adding a new note or updating an existing note.

## Technologies Used

- HTML
- CSS
- JavaScript
- LocalStorage (for data persistence)
