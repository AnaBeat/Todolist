# Todo List App

This project is a **Todo List application** built using **React** and **Vite**. The application allows users to add, delete, and mark tasks as completed in a simple and efficient way.

## Features

- **Add Tasks**: Users can add new tasks with a description.
- **Mark as Completed**: Allows users to mark and unmark tasks as completed.
- **Delete Tasks**: Users can remove tasks from the list.
- **Data Persistence**: Tasks are saved in the browser's LocalStorage, so they are not lost upon page reload.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Vite**: Fast and lightweight front-end development tool.
- **CSS (or styled-components, tailwind, etc.)**: Styling of the application.
- **LocalStorage**: Used to store tasks locally in the browser.

## Prerequisites

Before starting, ensure you have [Node.js](https://nodejs.org/) installed on your machine.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AnaBeat/Todolist.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Todolist
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Running the Project

To start the development server, run:

```bash
npm run dev
```

The project will start at `http://localhost:5173`. Open it in your browser to see the application in action.

## Building for Production

To generate an optimized build of the project, run:

```bash
npm run build
```

The optimized files will be generated in the `dist` folder.

## File Structure

```plaintext
├── public/               # Public files
├── src/
│   ├── components/       # Reusable React components
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # React entry point
│   └── styles.css        # Global styles
├── package.json          # npm configurations and dependencies
└── vite.config.js        # Vite configurations
```

## Future Improvements

- Implement task filtering (all, completed, incomplete).
- Edit Tasks
- Add the option to sort tasks by creation date or priority.
- Integrate with a backend for data persistence.
