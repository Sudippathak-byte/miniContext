# React Context API Demo

This project demonstrates the use of React's Context API for state management. It includes a login functionality and user profile display with shared state between components.

## Features

- Login form with user credentials
- Display user information if logged in
- React Context API for managing global state

## Project Structure

```plaintext
src/
├── components/
│   ├── Login.jsx          # Login form component
│   ├── Profile.jsx        # Profile display component
├── context/
│   ├── UserContext.js     # Context object
│   ├── UserContextProvider.jsx # Context Provider
├── App.jsx                # Main application component
└── App.css                # Stylesheet


Usage
Open the app in your browser at http://localhost:3000.
Enter a username and password in the login form.
After submitting, the profile component will display a welcome message with the username.


Technologies Used
React: Frontend library for building user interfaces
React Context API: For state management across components
JavaScript: Programming language for logic
CSS: Styling the application


Explanation of Key Files
UserContext.js: Creates a React context to hold user-related data.
UserContextProvider.jsx: Provides user data and state management functions to child components.
Login.jsx: Allows users to input and submit their credentials.
Profile.jsx: Displays a welcome message if a user is logged in or prompts them to log in.


Future Enhancements
Add form validation for login inputs.
Implement secure authentication mechanisms.
Style the application for a more polished look.


![Screenshot 2024-12-02 091000](https://github.com/user-attachments/assets/842deb37-3d6a-48aa-83dc-a5bf36abccf2)
![Screenshot 2024-12-02 091014](https://github.com/user-attachments/assets/5ea40209-3cb6-4c9e-9585-7d75218c117c)
