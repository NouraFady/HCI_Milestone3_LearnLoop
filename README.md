
Mil3 Implementation
There are two methods to run and access the application:

Method 1: Run the complete project locally using Visual Studio Code and Vite. Follow the prerequisites, clone the repository, install dependencies, and start the development server.
Method 2: Download the HTML file and open it directly in a web browser. This is the simpler option when you only need to view a standalone HTML file.
Method 1: Run the Project Locally Using Visual Studio Code
Overview
This project is a web application built using Vite. It contains the frontend implementation and the configuration files required to run the application locally.

Prerequisites
Before running the project, make sure you have installed:

Node.js (LTS version) – Download Node.js
npm – Installed automatically with Node.js.
Git (optional) – If cloning the project from a repository.
To verify your installations, open a terminal and run:

node -v
npm -v
Both commands should return their installed version numbers.

Project Setup
1. Clone the Repository
If you do not already have the project files on your computer:

Open the project's GitHub repository.
Click the Code button.
Copy the HTTPS repository URL.
Open a terminal on your computer.
Navigate to the folder where you want to save the project.
Run the following command, replacing the example URL with the copied repository URL:
git clone [https://github.com/USERNAME/REPOSITORY.git](https://github.com/NouraFady/HCI_Milestone3_LearnLoop.git)
Move into the newly created project folder:
cd REPOSITORY
If you already have the project folder, you can skip this step.

2. Open the Project
Open the project folder (Mil3_implementation) in Visual Studio Code.

Open the integrated terminal:

Terminal → New Terminal

Make sure the terminal is running inside the root project directory, where package.json is located.

3. Install Dependencies
Run the following command:

npm install
This installs all the dependencies specified in package.json and creates the node_modules directory.

4. Run the Application Locally
Start the Vite development server:

npm run dev
Once the server starts successfully, the terminal will display a local URL.

Open this URL in your web browser to access the application.

Keep the terminal running while using the application.

To stop the development server, press:

Ctrl + C

Method 2: Download the HTML File and Open It in a Browser
Download the HTML file "index.html" to your computer.
Locate the downloaded file (usually in the Downloads folder).
Right-click the .html file.
Select Open with.
Choose Google Chrome or Microsoft Edge.
The HTML page will open in the selected browser.
If your browser is not listed, select Choose another app and then choose Chrome or Edge.

Note: Method 2 works when the HTML file is standalone. If the page relies on Vite, installed packages, or other project files, use Method 1 instead.

Testing the Application Locally
After starting the development server:

Open the application using the localhost URL.
Navigate through the available pages and interface components.
Test the interactive elements, buttons, navigation links, and forms.
Verify that the application displays correctly and that the expected interactions work.
Check the browser's Developer Tools (F12) for console errors.
Check the VS Code terminal for build or runtime errors.
Build Verification
To verify that the project can be compiled successfully, run:

npm run build
This generates the production-ready build in the dist directory.

Preview the Production Build
To preview the generated production build locally, run:

npm run preview
Vite will provide a local URL where you can inspect the production version of the application.

Available Commands
Command	Description
npm install	Installs project dependencies.
npm run dev	Starts the local development server.
npm run build	Generates the production build.
npm run preview	Previews the production build locally.
Troubleshooting
1. npm or node is not recognized

Make sure Node.js is installed and added to your system PATH. Restart VS Code after installation.

2. Missing module or dependency errors

Run:

npm install
3. Vite configuration or missing file errors

Make sure the project folder structure is preserved and that all imported configuration files exist at their specified paths.

4. Port already in use

Vite will attempt to use another available port automatically. Check the terminal for the correct localhost URL.

Notes
Always run commands from the project root directory.
Do not delete the package.json or package-lock.json files.
The node_modules folder is generated automatically when running npm install.
Run npm install again whenever project dependencies change.




