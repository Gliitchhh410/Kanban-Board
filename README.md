# Kanban Board

A simple, interactive Kanban Board built with vanilla JavaScript, HTML, and CSS. This project allows users to manage tasks efficiently with drag-and-drop functionality and local storage persistence.

🔗 **Live Demo**: https://kaanbaan-board.netlify.app/

## 🚀 Features

- **Drag and Drop**: Smoothly move tasks between columns (e.g., To Do, In Progress, Done).
- **Task Management**:
  - **Create**: Add new tasks dynamically.
  - **Edit**: Update task details inline or via a modal.
  - **Delete**: Remove tasks that are no longer needed.
- **Data Persistence**: Uses **Local Storage** to save your board state, so you don't lose progress on refresh.
- **Import/Export**: Download your tasks and columns as a JSON file to your PC for backup, or upload a JSON file to restore your board.
- **Dynamic Rendering**: The board updates instantly without reloading the page.
- **Responsive Design**: Works on different screen sizes.

## 🛠️ Technologies Used

- **HTML5**: Structure of the board and columns.
- **CSS3**: Styling, layout (Flexbox/Grid), and responsive adjustments.
- **JavaScript (ES6)**: Core logic for drag-and-drop, event handling, and state management.

## 📂 Project Structure

```bash
Kanban-Board/
├── index.html      # Main HTML file
├── style.css       # Styles and layout
├── script.js       # Application logic (drag & drop, local storage)
├── tasks.md        # Project planning/todo list
└── README.md       # Project documentation
```

## 🏁 Getting Started

To run this project locally, you don't need any complex build tools or servers.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Gliitchhh410/Kanban-Board.git
    ```

2.  **Navigate to the project folder:**
    ```bash
    cd Kanban-Board
