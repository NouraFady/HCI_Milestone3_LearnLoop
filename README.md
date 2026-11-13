# Mil3 Implementation

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

### 1. Open the Project

Open the project folder (`Mil3_implementation`) in Visual Studio Code.

Open the integrated terminal:

`Terminal → New Terminal`

Make sure the terminal is running inside the root project directory, where `package.json` is located.

### 2. Install Dependencies

Run the following command:

```bash
npm install
```

This installs all the dependencies specified in `package.json` and creates the `node_modules` directory.

### 3. Run the Application Locally

Start the Vite development server:

```bash
npm run dev
```

Once the server starts successfully, the terminal will display a local URL.

Open this URL in your web browser to access the application.

Keep the terminal running while using the application.

To stop the development server, press:

`Ctrl + C`

## Testing the Application Locally

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