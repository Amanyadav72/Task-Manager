# Task Manager

A simple and efficient web-based Task Manager built with Flask.  
This application allows users to add tasks with deadlines, mark them as complete, and delete them. All tasks are stored locally in a JSON file for easy management.

---

## Features

- **Add Tasks:** Create new tasks with a description and deadline.
- **View Tasks:** See all tasks in a clean, tabular format.
- **Mark as Complete:** Mark tasks as done when finished.
- **Delete Tasks:** Remove tasks you no longer need.
- **Persistent Storage:** Tasks are saved in a local JSON file.
- **Simple UI:** Clean and responsive interface using HTML and CSS.

---

## Screenshots

> _Add screenshots of your app here if desired._

---

## Getting Started

### Prerequisites

- Python 3.x
- Flask

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/task_manager.git
    cd task_manager
    ```

2. **Install dependencies:**
    ```bash
    pip install flask
    ```

### Running the Application

1. **Start the Flask server:**
    ```bash
    python app.py
    ```

2. **Open your browser and go to:**
    ```
    http://localhost:5000
    ```

---

## Project Structure

```
task_manager/
│
├── app.py
├── tasks.json           # (created automatically)
├── templates/
│   ├── index.html
│   └── layout.html
├── static/
│   └── style.css
└── .git/
```

- **app.py**: Main Flask application file.
- **tasks.json**: Stores all tasks (created automatically).
- **templates/**: Contains HTML templates for the app.
- **static/**: Contains static files like CSS.
- **.git/**: Git repository folder.

---

## Customization

- **Styling:** Modify `static/style.css` to change the look and feel.
- **Templates:** Edit HTML files in the `templates` folder for layout changes.

---

## API Endpoints

- `/`  
  Displays all tasks.

- `/add`  
  Adds a new task (POST method).

- `/complete/<task_id>`  
  Marks a task as complete.

- `/delete/<task_id>`  
  Deletes a task.

---

## License

This project is licensed under the MIT License.

---

## Author

Developed by [Your Name].  
Feel free to contribute or suggest improvements!

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

**Enjoy managing your tasks
