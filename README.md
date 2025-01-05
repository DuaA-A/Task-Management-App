<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="container">
        <h1>Task Management App</h1>
        <div class="section">
            <p>
                A simple web application that allows users to manage their daily tasks. This app helps users add, edit, delete, filter, and sort tasks. It supports task priorities and completion status, with a clean and responsive UI.
            </p>
        </div>
        <div class="section">
            <h2>Features</h2>
            <ul>
                <li><strong>Add, Edit, and Delete Tasks:</strong> Users can manage tasks with a title, description, due date, and priority level.</li>
                <li><strong>Task Filtering and Sorting:</strong> Tasks can be filtered by status (completed or pending) and sorted by due date or priority.</li>
                <li><strong>Task Priority:</strong> Users can assign priority levels (High, Medium, Low) to tasks, which will be visually displayed using badges.</li>
                <li><strong>Task Completion:</strong> Users can mark tasks as completed or pending, with real-time updates.</li>
                <li><strong>Responsive Design:</strong> Built with Bootstrap to ensure the app works well on mobile and desktop devices.</li>
                <li><strong>Persistence (Optional):</strong> The app uses local storage to save tasks between browser sessions.</li>
            </ul>
        </div>
        <div class="section">
            <h2>Technologies Used</h2>
            <ul>
                <li><strong>Angular:</strong> For building the task management functionality and handling data binding.</li>
                <li><strong>Bootstrap:</strong> For creating a responsive and visually appealing UI.</li>
                <li><strong>JavaScript:</strong> For task management logic (adding, editing, deleting, sorting tasks).</li>
                <li><strong>HTML & CSS:</strong> For designing the structure and styling of the app.</li>
            </ul>
        </div>
        <div class="section">
            <h2>Installation</h2>
            <ol>
                <li>Clone the repository: <code>git clone https://github.com/your-username/task-management-app.git</code></li>
                <li>Navigate to the project folder: <code>cd task-management-app</code></li>
                <li>Install the dependencies: <code>npm install</code></li>
                <li>Run the app: <code>ng serve</code></li>
                <li>Open your browser and go to <code>http://localhost:4200</code></li>
            </ol>
        </div>
        <div class="section">
            <h2>Usage</h2>
            <p>
                After running the app, you will see the Task Management interface. You can add new tasks, mark them as completed, edit details, and delete them. Use the filtering options to view tasks based on their status or priority.
            </p>
        </div>
        <div class="section">
            <h2>Contributing</h2>
            <p>
                If you would like to contribute to the project, feel free to fork the repository and create a pull request with your changes.
            </p>
        </div>
        <div class="section">
            <h2>License</h2>
            <p>
                This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.
            </p>
        </div>
    </div>
</body>
</html>
