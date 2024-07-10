# Todo List Application

This is a simple Todo List application built with React. The app allows users to fetch, add, update, and delete todo items using the JSONPlaceholder API.

## Features

- **Fetch Todo Items**: Retrieve a list of todo items from the JSONPlaceholder API.
- **Add Todo Item**: Add a new todo item (dummy request).
- **Update Todo Item**: Update an existing todo item (dummy request).
- **Delete Todo Item**: Delete a todo item (dummy request).

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-list-app.git
   cd todo-list-app

2. Installing the dependencies:

    ```bash
    npm install

3. Running the application:

    ```bash
    npm start


## Code Overview

### TodoList Component

The `TodoList` component handles the main functionality of the app. It uses `useState` and `useEffect` hooks to manage state and side effects.

- **State Variables**:
  - `todos`: Stores the list of todo items.
  - `newTodo`: Stores the input value for a new todo item.
  - `editingTodo`: Stores the ID of the todo item being edited.
  - `editText`: Stores the text of the todo item being edited.

- **Functions**:
  - `fetchTodos`: Fetches todo items from the API.
  - `addTodo`: Adds a new todo item.
  - `startEditTodo`: Initiates editing for a specific todo item.
  - `updateTodo`: Updates the text of a specific todo item.
  - `toggleComplete`: Toggles the completion status of a specific todo item.
  - `deleteTodo`: Deletes a specific todo item.

### Styling

The app uses CSS for styling. The CSS files are located in the `src/components` directory and are imported into the corresponding components.

## API Reference

The app interacts with the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/) for fetching, adding, updating, and deleting todo items.

- **GET** `/todos`: Fetches a list of todo items.
- **POST** `/todos`: Adds a new todo item.
- **PUT** `/todos/:id`: Updates an existing todo item.
- **DELETE** `/todos/:id`: Deletes a todo item.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) for providing the fake online REST API.
- [React](https://reactjs.org/) for providing a powerful JavaScript library for building user interfaces.

