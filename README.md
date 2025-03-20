# PermaList

PermaList is a powerful yet lightweight to-do list web application designed to help users manage their daily tasks efficiently. With a clean and intuitive interface, PermaList ensures seamless task organization while maintaining simplicity. Built using Node.js, Express, and PostgreSQL, this application offers a smooth user experience with persistent data storage. Whether you're planning your day, managing project deadlines, or tracking long-term goals, PermaList has you covered.

## Features
- **Task Management:** Add, update, and delete tasks with ease.
- **Persistent Data:** All tasks are stored in a PostgreSQL database to ensure data retention.
- **User-Friendly Interface:** Clean UI with clear navigation for efficient task management.

## Technologies Used
- **Frontend:**
  - HTML
  - CSS
  - EJS (Embedded JavaScript)
- **Backend:**
  - Node.js
  - Express.js
- **Database:**
  - PostgreSQL
- **Middleware:**
  - body-parser
- **Libraries & Tools:**
  - pg (PostgreSQL client for Node.js)

## Project Structure
```
/PermaList
├── /public          # Static files (CSS, Images)
├── /views           # EJS templates
├── index.js         # Main server logic
├── solution.js      # Core functionality for CRUD operations
├── queries.sql      # Database setup commands
├── package.json     # Project dependencies
├── package-lock.json # Dependency lock file
└── .env             # Environment variables for database credentials
```

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Bhargav13304/PermaList.git
   cd PermaList
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up the PostgreSQL database:**
   - Install PostgreSQL if not already installed.
   - Create a database named `permalist`.
   - Execute the SQL commands provided in `queries.sql` to set up tables.

4. **Configure environment variables:**
   - Create a `.env` file in the root directory.
   - Add the following details:
     ```env
     DB_USER=your_postgresql_username
     DB_PASSWORD=your_postgresql_password
     DB_NAME=permalist
     DB_HOST=localhost
     DB_PORT=5432
     ```

5. **Start the application:**
   ```bash
   node index.js
   ```

6. **Access the application:**
   - Open your browser and visit `http://localhost:3000`

## Usage
- **Add a Task:** Type your task in the input field and click "Add" to add it to the list.
- **Edit a Task:** Click "Edit," modify the task, and save it to update.
- **Delete a Task:** Click the "Delete" button next to a task to remove it from the list.

