# T03 Single-Page-Application for Weather Monitoring (Web Technologies)

## Context
This project was developed as the third milestone within the "Web Technologies" module at my university. The objective was to expand my knowledge of web architecture by implementing a full-stack approach. The application consists of a dedicated backend server providing a local API and a frontend client that consumes this data to provide dynamic visualizations.

## Description
"Festival am See - Wetter" is a single-page application designed to monitor weather data for the upcoming days. The frontend connects to a local Node.js backend to fetch weather data, which is then dynamically visualized. Temperature data is presented as a pie chart, while cloud cover percentages are tracked via a line chart. A header and descriptive text boxes provide additional context for the visualizations.

## Architecture & Folder Structure
The application follows a client-server pattern:
- /client: Frontend source code (HTML, JavaScript).
- /server: Node.js server handling API requests, including JSON data files.
- package.json: Manages dependencies and scripts for both client and server.

## Setup & Execution
1. Ensure Node.js and npm are installed on your machine.
2. Download and unzip the project folder.
3. Open the root directory in your IDE (e.g., VS Code).
4. Run npm install in the terminal to install all necessary dependencies (including cors).
5. Open two terminal instances:
- Terminal 1: Run npm run server to start the backend.
- Terminal 2: Run npm run client to start the frontend.
6. The application will open automatically in your default browser. Enjoy! 😊

## Testing
The application was tested on Brave Browser, Firefox, and Chrome.
