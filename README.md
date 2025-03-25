# Kanban To-Do List

A simple web-based Kanban To-Do List that allows you to manage your tasks across three columns: **To Do**, **Currently Doing**, and **Done**. The application supports drag-and-drop functionality, task editing, deleting, and manual export/import of your tasks via JSON files. It uses `localStorage` to persist data between sessions.

## Features

- **Three Columns:** Organize tasks into "To Do", "Currently Doing", and "Done".
- **Drag-and-Drop:** Easily move tasks between columns.
- **Task Management:** Create new tasks, edit existing ones, and delete tasks.
- **Data Persistence:** Tasks are automatically saved in your browser's `localStorage`.
- **Export/Import:** Download your tasks as a JSON file and upload them to restore your work.
- **Clear All:** A button to clear all tasks (and remove them from `localStorage`).
- **External CSS:** All styles are written in a separate `styles.css` file.

## Getting Started

### Prerequisites

All you need is a modern web browser (Chrome, Firefox, Edge, etc.) to run the application.

### Installation

1. Clone or download the repository files.
2. Ensure you have the following files in the same directory:
   - `index.html`
   - `styles.css`
   - `README.md`

### Running the Application

Simply open the `index.html` file in your web browser. You should see the Kanban board with the input area at the top and the three columns below.

## Usage

- **Add a Task:** Type your task into the input field at the top and press `Enter`. The new task will appear in the **To Do** column.
- **Edit a Task:** Click the **Edit** button on a task, update the text in the prompt, and click OK.
- **Delete a Task:** Click the **Delete** button on the task you want to remove.
- **Drag-and-Drop:** Click and drag tasks to move them between columns.
- **Download Tasks:** Click the **Download Tasks** button to export your tasks as a JSON file.
- **Upload Tasks:** Click the **Upload Tasks** button, then choose a previously downloaded JSON file to load your tasks.
- **Clear All:** Click the **Clear All** button to remove all tasks from the board and clear `localStorage`.

## Customization

You can easily modify the look and feel of the application by editing the `styles.css` file.

## Contributing

Feel free to fork this project and create pull requests with enhancements or bug fixes.

## Acknowledgments

- Built with plain HTML, CSS, and JavaScript.
- Inspired by the simplicity of Kanban boards for task management.
