**Collaborative Whiteboard**

This repository contains a web application built for real-time collaboration on a whiteboard. Users can draw, upload images, and collaborate with others in real-time. The application is developed using React and utilizes WebSocket for real-time functionality.

### Features:
- **Real-time Collaboration**: Multiple users can draw on the whiteboard simultaneously, with changes synced in real-time.
- **Drawing Tools**: A variety of drawing tools are available, including different colors and brush sizes.
- **Image Upload**: Users can upload images onto the whiteboard for collaborative editing.
- **Undo/Redo**: Undo and redo functionality allows users to revert or repeat drawing actions.
- **Cursor Movement Indication**: Real-time cursor movements of other users are displayed to indicate their drawing actions.
- **Save Whiteboard**: Users can save the whiteboard content as an image or PDF file.
- **Authentication**: User authentication is implemented using Keycloak, ensuring secure access to the whiteboard.
- **Responsive Design**: The application is responsive and works seamlessly on both desktop and mobile devices.

### Technologies Used:
- **Frontend**: React, TypeScript, Bootstrap 5.0, WebSocket.
- **Authentication**: Keycloak.
- **State Management**: React Context API or Redux.

### Setup Instructions:
1. Clone the repository: `git clone https://github.com/costingh/collaborative-whiteboard.git`
2. Navigate to the project directory: `cd collaborative-whiteboard`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Access the application in your browser at `http://localhost:3000`

### Usage:
1. Sign up or log in using Keycloak authentication.
2. Create a new whiteboard session or join an existing one.
3. Use the drawing tools to sketch on the whiteboard.
4. Undo or redo actions as needed.
5. See the real-time cursor movements of other connected users.
6. Save the whiteboard content as an image or PDF.

### Folder Structure:
- **/src**: Contains the source code for the React application.
  - **/components**: Reusable React components.
  - **/pages**: Top-level page components.
  - **/services**: Services for API calls, authentication, etc.
  - **/styles**: CSS or SCSS stylesheets.
- **/public**: Public assets like images, icons, and HTML template.

### Additional Notes:
- Ensure Docker is installed to run Keycloak and PostgreSQL containers.
- Explore the WebSocket implementation for real-time functionality.
- Improve the user experience with additional features such as live chat and invitation system.
- Ensure code readability, simplicity, and cleanliness.

### Contributors:
- [@Chitra Harini](https://github.com/Harini-chitra)
