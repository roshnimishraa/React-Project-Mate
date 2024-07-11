# React Project Management Web App 

## Technology Used
1. React.js
2. Tailwind CSS

## Functions
1. Create Projects
2. Add Tasks to Projects
3. View Different Projects
4. Clear Tasks
5. Delete Projects

## Features 
1. Build and Style: Develop a Project Management Web App using Tailwind CSS for styling, ensuring reusable and configurable components.
2. State Management: Effectively manage state across components.
3. DOM Access: Utilize Refs to access and interact with DOM elements and browser APIs.
4. JSX Rendering: Manage rendering positions with Portals for flexible UI components.
5. User Input Validation: Validate user input and display error modals using useImperativeHandle.

## Concepts Used 
1. useState Hook: Managing state to switch between components 
2. useRef Hook: Directly access and manipulate DOM elements and store mutable values without causing re-renders.
3. forwardRef Hook: Establish cross-component ref connections.This helps the child to read and modify the element from any location where it is used.
4. createPortal (React-dom): Render dialogs and content in different DOM locations for flexibility and reusability.
5. useImperativeHandle: It is used to customize the handle exposed as a ref.
6. Props: Pass data and event handlers from parent to child components for effective communication and reusability.

<!-- 1. useState Hook: Managing state to switch between components 
2. useRef Hook: To connect with HTML elements and with interact with HTML elements or to retrive value of a Input 
3. forwardRef Hook: To establish cross components ref connection
4. createPortal in React-dom: To render dialog and the content that will be wrapped by this dialog in a different place of a DOM and to make modal more flexible and re-usable
5. useImperativeHandle: To expose a function that can be called outside the component function.
6. Props: used to pass data and event handlers from parent to child components, enabling component communication and reusability -->
## Deployed
To view the deployed app [click here](https://roshni-project-management-app.vercel.app/).

## Installation 
1. Clone the repository to your local machine
   $ git clone https://github.com/roshnimishraa/React-Project-Management-App.git
2. navigate to the project's directory and install all the relevant dev-dependencies
   $ npm intsall
3. Start application
   $ npm run dev
4. Visit http://localhost:5173/ in your browser

