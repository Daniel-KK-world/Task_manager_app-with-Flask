
![TaskSmash screenshot](https://github.com/user-attachments/assets/e6b67357-d617-4b53-80ac-ab6c1f0e4e5d)



# TaskSmash

**TaskSmash** is a straightforward task management web application built with **Flask**. It provides users with the ability to create, edit, and delete tasks, making it easy to manage daily activities. This project is designed to demonstrate basic CRUD operations, SQLite integration, and responsive design. It's a great project to do as an introduction to Flask.

## Features
- **Create Tasks**: Add new tasks quickly and easily.
- **Edit Tasks**: Modify existing tasks as needed.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Responsive Design**: Works well on both desktop and mobile devices.

## Technologies Used
- **Flask**: A lightweight web framework for Python.
- **SQLite**: A self-contained, high-reliability database engine.
- **HTML/CSS**: For structuring and styling the web pages.
- **Python**: The programming language used for the backend.

## Installation

To get started with **TaskSmash**, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Daniel-KK-world/Task_manager_app-with-Flask.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd tasksmash
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    python app.py
    ```

5. **Access the app**: Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

## Usage

- **Homepage**: View all tasks and add new tasks.
- **Edit Task**: Click on a task to edit it.
- **Delete Task**: Click the delete button next to a task to remove it.

## Project Structure

The project directory structure is as follows:
tasksmash/ │ ├── app.py # Main application file │ ├── templates/ # HTML templates │ ├── base.html # Base template │ ├── index.html # Main page template │ └── edit.html # Edit page template │ ├── static/ # Static files │ ├── css/ │ │ └── style.css # Stylesheet for the project │ ├── database.db # SQLite database ├── requirements.txt # Python dependencies └── README.md # Project documentation


## Future Improvements

- Add **user authentication** for personalized task lists.
- Implement **task categories** or **priorities**.
- Add **deadlines** and **reminders** for tasks.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

