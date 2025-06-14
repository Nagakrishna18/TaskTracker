# 📝 Task Tracker - Python CLI App

This is a simple command-line Task Tracker built using Python. It allows users to manage their to-do tasks stored in a `tasks.txt` file. The script supports adding, deleting, updating, and listing tasks along with tracking their completion status.

---

## 🚀 Features

- ✅ Add new tasks with completion status
- ❌ Delete specific tasks by task number
- 🔄 Update task completion status
- 🗑️ Remove all tasks
- 🔍 Check the status of individual tasks
- 📋 List all/completed/pending tasks

---

## 🛠️ How It Works

1. The program interacts with a `tasks.txt` file.
2. On running the script, users are prompted with options:
   - `add` – Add one or more tasks
   - `del` – Delete tasks by number
   - `update` – Update the completion status
   - `removeall` – Clear the task file
   - `status` – Check status of specific tasks
   - `list_tasks` – Display tasks (all/completed/pending)

---

## 📄 Task Format

Each task is stored in the format:

task1-<Task Description> : completed
task2-<Task Description> : not completed



---

## 🧑‍💻 How to Run

1. Make sure you have Python 3 installed.
2. Save the script as `task_tracker.py`.
3. Run it in the terminal:

```bash
python task_tracker.py
📝 Notes
All tasks are saved in tasks.txt in the same directory.

Task numbers start from 1 (not 0) when performing delete or update actions.

📌 To Do (Optional Improvements)
Add exception handling for non-integer inputs

Use a class-based approach for better modularity

Add a GUI using Tkinter or a web interface

Support timestamps for tasks

💡 Author
Created with ❤️ by Naga Krishna

🔗 GitHub: github.com/Nagakrishna18
