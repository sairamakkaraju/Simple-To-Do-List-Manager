# Simple-To-Do-List-Manager
1. Persistent Storage with a File

Used a text file named tasks.txt to store tasks.

load_tasks() → Reads tasks from the file at the start.

save_tasks(tasks) → Writes the updated task list to the file.

This keeps the to-do list persistent across program runs.

2. Task Management Using a List

Tasks are loaded into a list when the program starts.

New tasks are added to the list and saved.

Tasks can be removed by index.

You can view all tasks neatly with numbering.

3. Simple Menu-Based CLI

The program shows a menu:

1. View Tasks
2. Add Task
3. Remove Task
4. Exit


The user selects an option by entering a number.

Input is handled using input().

The menu runs in a loop until the user exits.

4. Error Handling

If the file doesn’t exist, the program starts with an empty list.

Handles invalid input (e.g. typing letters instead of numbers).
