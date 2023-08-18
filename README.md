# TodoPlus: Simplify Your Task Management

TodoPlus is a versatile todo app developed in Python that provides three different interfaces for task management: command-line, GUI (Graphical User Interface), and web interface. The web interface is built using Streamlit, while the GUI is created with PySimpleGUI.

## Features

- Manage your tasks seamlessly through three different interfaces: command-line, GUI, and web.
- Add, edit, delete, and mark tasks as complete.

## Getting Started

### Clone the Repository

To get started, clone the TodoPlus repository to your local machine using the following command:

```bash
git clone https://github.com/yourusername/TodoPlus.git
```

### Command-Line Interface

The command-line interface allows you to manage your tasks using simple commands. Navigate to the project directory and run the following command to start the command-line interface:

```bash
python main.py cli
```

### GUI Interface

The GUI interface provides an intuitive graphical interface for managing tasks. Run the following command to launch the GUI:

```bash
python main.py gui
```

### Web Interface

The web interface is powered by Streamlit and allows you to access your tasks through a browser. Run the following command to start the web interface:

```bash
streamlit run main.py
```

## Usage

### Command-Line Interface

- Use the command-line interface to interact with your tasks through text-based commands.
- Add tasks: `add "Task description"`
- Edit tasks: `edit task_id "New task description"`
- Delete tasks: `delete task_id`
- Mark tasks as complete: `complete task_id`
- List tasks: `list`

### GUI Interface

- The GUI interface presents a user-friendly way to manage tasks with buttons and input fields.
- Add tasks: Click "Add Task" and enter the task description.
- Edit tasks: Select a task from the list and click "Edit Task."
- Delete tasks: Select a task and click "Delete Task."
- Mark tasks as complete: Click the checkbox next to a task.
- View tasks: The list of tasks is displayed on the main window.

### Web Interface

- The web interface provides a convenient way to access your tasks from a browser.
- Open your web browser and navigate to `http://localhost:8501` (default Streamlit port) after running the web interface command.
- Interact with your tasks using the buttons and input fields provided on the web page.

## Contribution

TodoPlus welcomes contributions from the community. If you'd like to contribute, fork the repository, make your changes, and submit a pull request. Whether it's adding features, improving usability, or fixing bugs, your contributions are appreciated.

## Notes

- TodoPlus aims to provide a simple task management solution with different interfaces catering to user preferences.

- The Streamlit web interface is accessible through a web browser.

- The GUI interface offers an alternative to the command-line and web interfaces, providing a visual and interactive experience.

## License

TodoPlus is released under the [MIT License](LICENSE). Feel free to use, modify, and distribute the project in accordance with the terms of the license.

