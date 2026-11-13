
# Mil3 Implementation

There are **two methods** to run and access the application:

- **Method 1:** Run the complete project locally using Visual Studio Code and Vite.
- **Method 2:** Download the HTML file and open it directly in a web browser.

---

# Method 1: Run the Project Locally Using Visual Studio Code

## Overview

This project is a web application built using Vite. It contains the frontend implementation and the configuration files required to run the application locally.

## Prerequisites

Before running the project, make sure you have installed:

- **Node.js (LTS version)** – [Download Node.js](https://nodejs.org/)
- **npm** – Installed automatically with Node.js.
- **Git** (optional) – If cloning the project from a repository.

To verify your installations, open a terminal and run:

```bash
node -v
npm -v
```

Both commands should return their installed version numbers.

## Project Setup

### 1. Clone the Repository

If you do not already have the project files on your computer:

1. Open the project's GitHub repository.
2. Click the **Code** button.
3. Copy the HTTPS repository URL.
4. Open a terminal on your computer.
5. Navigate to the folder where you want to save the project.
6. Run the following command, replacing the example URL with the copied repository URL:

```bash
git clone https://github.com/NouraFady/HCI_Milestone3_LearnLoop.git
```

7. Move into the newly created project folder:

```bash
cd REPOSITORY
```

If you already have the project folder, you can skip this step.

### 2. Open the Project

Open the project folder (`Mil3_implementation`) in Visual Studio Code.

Open the integrated terminal:

`Terminal → New Terminal`

Make sure the terminal is running inside the root project directory, where `package.json` is located.

### 3. Install Dependencies

Run the following command:

```bash
npm install
```

This installs all the dependencies specified in `package.json` and creates the `node_modules` directory.

### 4. Run the Application Locally

Start the Vite development server:

```bash
npm run dev
```

Once the server starts successfully, the terminal will display a local URL.

Open this URL in your web browser to access the application.

Keep the terminal running while using the application.

To stop the development server, press:

`Ctrl + C`

---

# Method 2: Download the HTML File and Open It in a Browser

1. Download the HTML file `index.html` to your computer.
2. Locate the downloaded file (usually in the **Downloads** folder).
3. Right-click the `.html` file.
4. Select **Open with**.
5. Choose **Google Chrome** or **Microsoft Edge**.
6. The HTML page will open in the selected browser.

If your browser is not listed, select **Choose another app** and then choose Chrome or Edge.

**Note:** Method 2 works when the HTML file is standalone. If the page relies on Vite, installed packages, or other project files, use Method 1 instead.

---

# Testing the Application Locally

After starting the development server:

1. Open the application using the localhost URL.
2. Navigate through the available pages and interface components.
3. Test the interactive elements, buttons, navigation links, and forms.
4. Verify that the application displays correctly and that the expected interactions work.
5. Check the browser's Developer Tools (F12) for console errors.
6. Check the VS Code terminal for build or runtime errors.

### Build Verification

To verify that the project can be compiled successfully, run:

```bash
npm run build
```

This generates the production-ready build in the `dist` directory.

### Preview the Production Build

To preview the generated production build locally, run:

```bash
npm run preview
```

Vite will provide a local URL where you can inspect the production version of the application.

## Available Commands

| Command | Description |
|---|---|
| `npm install` | Installs project dependencies. |
| `npm run dev` | Starts the local development server. |
| `npm run build` | Generates the production build. |
| `npm run preview` | Previews the production build locally. |

## Troubleshooting

**1. npm or node is not recognized**

Make sure Node.js is installed and added to your system PATH. Restart VS Code after installation.

**2. Missing module or dependency errors**

Run:

```bash
npm install
```

**3. Vite configuration or missing file errors**

Make sure the project folder structure is preserved and that all imported configuration files exist at their specified paths.

**4. Port already in use**

Vite will attempt to use another available port automatically. Check the terminal for the correct localhost URL.

---

## Notes

- Always run commands from the project root directory.
- Do not delete the `package.json` or `package-lock.json` files.
- The `node_modules` folder is generated automatically when running `npm install`.
- Run `npm install` again whenever project dependencies change.
