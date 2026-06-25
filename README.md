# REAL-TIME COLLABORATIVE DOCUMENT EDITOR

*COMPANY*: CODTECH IT SOLUTIONS PVT. LTD.

*NAME*: ARETHOTI MANOJ

*INTERN ID*: CTIS9586

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

# DESCRIPTION

The Real-Time Collaborative Document Editor is a modern full-stack web application developed using React.js, Node.js, Express.js, and Socket.IO. The primary objective of this project is to enable multiple users to edit the same document simultaneously while ensuring that all changes are synchronized instantly across every connected client. This project demonstrates the practical implementation of real-time communication using WebSocket technology and showcases how collaborative applications function efficiently.

The frontend of the application is developed using React.js, providing a responsive, interactive, and user-friendly interface. A large text editor allows users to enter, modify, or delete text naturally. React Hooks such as useState and useEffect are used for state management and handling Socket.IO events. The user interface updates dynamically whenever new data is received from the server, ensuring that every connected user always sees the latest version of the document.

The backend is built using Node.js and Express.js, which manage client connections and maintain communication between all users. Socket.IO establishes a persistent WebSocket connection between the server and every connected client. Whenever a user types or edits the document, the updated content is immediately transmitted to the server. The server then broadcasts the changes to all other connected users in real time. This process occurs instantly without requiring any page refresh, making collaboration smooth and efficient.

One of the major advantages of this application is its ability to synchronize document updates among multiple users. Every keystroke or text modification is reflected almost instantly on every connected device. This functionality makes the application suitable for collaborative environments such as online note-taking, team documentation, educational platforms, coding collaboration, and content editing systems.

The project also demonstrates important concepts of client-server architecture, event-driven programming, asynchronous communication, and real-time data synchronization. Proper CORS configuration was implemented to allow secure communication between the React frontend running on one port and the Node.js backend running on another port. The application architecture is organized into separate frontend and backend folders, making the codebase clean, maintainable, and scalable.

The user interface is designed with simplicity and responsiveness in mind. The editor adapts to different screen sizes, ensuring compatibility with desktops, laptops, tablets, and mobile devices. The clean design improves readability and enhances the overall user experience.

During the development of this project, several important web development concepts were applied, including React component architecture, Express.js server creation, Socket.IO event handling, WebSocket communication, state management, DOM updates, asynchronous programming, and frontend-backend integration. The project provided valuable hands-on experience in building real-world collaborative applications using modern JavaScript technologies.

The application can be further enhanced by adding advanced features such as user authentication, multiple collaborative documents, automatic document saving using MongoDB or Firebase, cursor position synchronization, rich text formatting, document version history, typing indicators, user presence status, document sharing, role-based permissions, cloud storage integration, and secure login functionality.

Overall, the Real-Time Collaborative Document Editor successfully achieves its goal of providing seamless collaborative editing through real-time synchronization. The project demonstrates strong knowledge of full-stack web development, React.js, Node.js, Express.js, Socket.IO, WebSocket communication, and responsive user interface design while showcasing practical implementation of collaborative technologies used in modern web applications.

# TECHNOLOGIES USED

- React.js
- Node.js
- Express.js
- Socket.IO
- JavaScript (ES6)
- HTML5
- CSS3
- Vite

# FEATURES

- Real-time collaborative editing
- Instant text synchronization
- Multiple users can edit simultaneously
- Responsive user interface
- React Hooks (useState, useEffect)
- Socket.IO WebSocket communication
- Express.js backend server
- Fast and interactive performance
- Clean and simple user interface

# HOW TO RUN

1. Download or clone the repository.
2. Open the project folder.
3. Navigate to the server folder:
   ```
   cd server
   ```
4. Install the backend dependencies:
   ```
   npm install
   ```
5. Start the backend server:
   ```
   node server.js
   ```
6. Open another terminal and navigate to the project root folder.
7. Install frontend dependencies:
   ```
   npm install
   ```
8. Start the React development server:
   ```
   npm run dev
   ```
9. Open your browser and visit:
   ```
   http://localhost:5173
   ```
10. Open the same application in another browser window or another device connected to the same server. Start typing in one editor, and the changes will appear instantly in the other editor, demonstrating real-time collaborative editing.

<img width="1918" height="967" alt="Image" src="https://github.com/user-attachments/assets/01c43202-2e01-48eb-ae19-b5cff8827a1a" />
<img width="1918" height="967" alt="Image" src="https://github.com/user-attachments/assets/25400414-2fd7-48a0-a6b7-345e853457ef" />
