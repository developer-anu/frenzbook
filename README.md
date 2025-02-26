# Angular Posts Management Application

This Angular application allows users to manage and view posts, featuring functionalities for fetching posts from a Node.js backend, hiding posts, and displaying user-added posts at the top of the list. The application also includes a login page and a user list with modals for displaying user details.

## Key Features

- **Components**:
  - **LandingComponent**: Displays the list of posts.
  - **LoginComponent**: Provides a login form for user authentication.
  - **User  ListComponent**: Displays a list of users and opens a modal with user details when clicked.

- **Services**:
  - Utilizes Angular's `HttpClient` for making HTTP requests to the backend API.

- **Data Binding**:
  - Implements interpolation and structural directives (`*ngIf`, `*ngFor`) for dynamic content rendering.

- **HTTP Client Module**:
  - Fetches posts for specific users from the backend API.

- **Sorting Logic**:
  - Ensures user-added posts appear at the top of the list.

- **Error Handling**:
  - Handles errors during HTTP requests with appropriate logging.

- **Template Structure**:
  - Structured to display a welcome message, a list of posts, and a message for no available posts.

- **Backend Integration**:
  - Built with Node.js and Express, providing RESTful API endpoints for managing posts.

- **File Handling**:
  - Uses the Node.js `fs` module for reading and writing to a JSON file for persistent storage.

- **JSON Data Structure**:
  - Data is structured in JSON format, including users and their posts.

- **Route Guards**:
  - Controls access to specific routes, ensuring only authorized users can navigate to certain components.

- **Login Page**:
  - A user-friendly login form styled with Bootstrap.

- **User  List with Modal**:
  - Displays a list of users with a modal for viewing user details.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/developer-anu/frenzbook.git
