# 📝 Task Manager CLI

Welcome to **Task Manager CLI**, your simple yet effective command-line companion for staying organized! Whether you're juggling multiple projects or just trying to keep track of your daily to-dos, this tool has got you covered—all from the comfort of your terminal.

## 🎯 Project Overview

**Task Manager CLI** is a lightweight, console-based application built in C that lets you manage your tasks with ease. Add tasks, mark them as completed, or delete them when done—all with straightforward commands. Plus, your tasks are saved to a file, so they're always there when you need them.

## 🚀 Features

- **Add Tasks:** Quickly create tasks with a title and description.
- **List Tasks:** View all your tasks, along with their status (pending/completed).
- **Edit Tasks:** Update the title or description of existing tasks.
- **Complete Tasks:** Mark tasks as completed once you’ve finished them.
- **Delete Tasks:** Remove tasks that are no longer needed.
- **Data Persistence:** Tasks are saved to a file, ensuring they persist between sessions.

## 💻 Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/task-manager-cli.git
   cd task-manager-cli
2. **Compile the program:**
   ```bash
   gcc -o task_manager main.c task_manager.c file_manager.c
3. **Run the application:**
   ```bash
   ./task_manager
4. **Use the following commands:**

- `add` Add a new task.
- `list` - List all tasks.
- `edit` <task_number> Edit a specific task.
- `done` <task_number> Mark a task as completed.
- `delete` <task_number> Delete a specific task.

## 📂 Project Structure
```bash
  task-manager-cli/
  │
  ├── main.c            # Entry point for the application
  ├── task_manager.c    # Task management functions (add, list, edit, delete, etc.)
  ├── task_manager.h    # Header file for task management
  ├── file_manager.c    # File handling functions (save, load tasks)
  ├── file_manager.h    # Header file for file handling
  └── tasks.txt         # Persistent storage for tasks (auto-generated)
```
## 🌟 Future Enhancements
- [ ] Task Categories: Organize your tasks by category.
- [ ] Due Dates: Set and track deadlines for each task.
- [ ] Search/Filter: Quickly find tasks by keywords or status.
- [ ] User Interface: Explore a graphical interface using ncurses.

## 🛠️ Built With
  Language: C<br>
  Libraries: Standard C libraries (stdio.h, stdlib.h, string.h)

###### Project developed by: [Carol Cortes](https://github.com/carolcortes)

  <a href = "mailto:caroline.ocortes@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/carolinecortess/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
