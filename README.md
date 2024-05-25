
# Task Manager without Authentication

This is a React-based task management application that allows users to manage their tasks. It includes features like adding, editing, deleting, and completing tasks. The application supports task filtering based on completion status and persists task data using local storage. Users can sign in with Google using Firebase authentication, ensuring that each user's tasks are stored separately.

## Features

- Add a task with a title, description, due date, and priority level.
- Edit existing tasks.
- Delete tasks.
- Mark tasks as completed or active.
- Filter tasks by all, completed, or active status.
- User authentication with Google.
- Persistent task data in local storage specific to each user.
- Drag-and-drop functionality for task reordering.

## Technologies Used

- React.js
- Firebase for authentication
- react-beautiful-dnd for drag-and-drop functionality
- Local Storage for data persistence

## Setup and Installation

### Prerequisites

- Node.js installed on your machine
- Firebase project setup (with Google sign-in enabled)

### Firebase Setup

1. Go to the [Firebase Console](https://console.firebase.google.com/).
2. Create a new project.
3. Add a web app to your Firebase project.
4. Enable Google authentication in the Firebase Authentication section.
5. Copy the Firebase configuration details provided.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Ramling855/Task-Management.git
cd Task-Management
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

## Project Structure

```
src/
│
├── components/
│   ├── TaskForm.js
│   ├── TaskList.js
│   ├── TaskItem.js
│   └── TaskFilter.js
│
├── App.js
└── index.js
```

## Usage

- Open your browser and navigate to `http://localhost:3000`.
- Click the "Sign in with Google" button to authenticate.
- Add, edit, delete, and manage your tasks.
- Use the filter buttons to view all tasks, completed tasks, or active tasks.
- Your tasks are saved automatically and will persist across sessions.
## samples after installation
##sign in with google
![sign in with google](https://github.com/Ramling855/Ramling855-Task-Management-Application/assets/99536932/025b94d1-9cd6-4fe7-a576-9e8d4877cf3e)
##sign in with account
![choose google account give permission to continue](https://github.com/Ramling855/Ramling855-Task-Management-Application/assets/99536932/4fae8f3e-e98b-40f1-9c85-756033f10ff4)
##main page
![main page](https://github.com/Ramling855/Ramling855-Task-Management-Application/assets/99536932/1b95d576-5487-4387-95e6-fb7a372cec54)
##category wise list
![category wise task list](https://github.com/Ramling855/Ramling855-Task-Management-Application/assets/99536932/c7338e1a-61a6-49b3-9b9a-e2f3fdf8fd12)
##drag and drop list change order
![drag and drop shuffle change order](https://github.com/Ramling855/Ramling855-Task-Management-Application/assets/99536932/ead4100a-bf0c-4ab8-be39-8114e390fdf4)
##task complete

![task complete list](https://github.com/Ramling855/Ramling855-Task-Management-Application/assets/99536932/4060ac63-c8ea-458e-a3c4-97ed297d25bd)




## Contact

If you have any questions or feedback, please contact ramling855@gmail.com.
