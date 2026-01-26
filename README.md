# to-do-list.txt
To-Do List Application (Python – CLI)
📌 Description

This is a Command Line Interface (CLI) based To-Do List application developed using Python.
The application allows users to add, view, update, and remove tasks, and it stores tasks permanently using Python’s pickle module.

Tasks are automatically saved to a file and loaded again when the program restarts.

🚀 Features

➕ Add new tasks

📋 View all saved tasks

✏️ Update existing tasks

❌ Remove tasks

💾 Persistent storage using pickle

🖥️ Simple menu-driven CLI interface

🛠️ Technologies Used

Python 3

Pickle Module

OS Module

📂 Project Structure
todo-list/
│
├── todo.py        # Main application file
├── tasks.pkl      # Stored tasks file (auto-created)
└── README.md      # Project documentation

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/todo-list.git


Navigate to the project directory:

cd todo-list


Run the application:

python todo.py

📖 How It Works

Tasks are loaded from tasks.pkl when the program starts

User selects options from the menu

Changes are saved automatically when exiting the program

🔮 Future Enhancements

Mark tasks as completed

Add task priorities & due dates

Convert to GUI using Tkinter

Replace pickle with database storage
