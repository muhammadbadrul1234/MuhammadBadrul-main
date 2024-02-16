# Project Installation Guide

This README provides a step-by-step guide on how to install the project successfully. If you encounter any issues during the installation process, please refer to the troubleshooting section at the end of this document.

## Prerequisites

- Git installed on your machine
- Node.js and npm installed
- Gatsby CLI installed globally (`npm install -g gatsby-cli`)

## Installation Steps

### 1. Clone the Project

Start by cloning the project repository from GitHub:

```bash
git clone <repository_url>
```

### 2. Navigate to the Project Directory

Move into the project directory:

```bash
cd <project_directory>
```

### 3. Delete yarn.lock file

Remove the `yarn.lock` file if it exists:

```bash
rm yarn.lock
```

### 4. Install Gatsby CLI

If you haven't installed Gatsby CLI globally, run the following command:

```bash
npm install -g gatsby-cli
```

### 5. Install Project Dependencies

Forcefully install project dependencies:

```bash
npm install --force
```

### 6. Start the Project

Initiate the project by running the following command:

```bash
npm start
```

### 7. View the Project

Open your browser and navigate to [http://localhost:8000/](http://localhost:8000/) to view the project.

## Troubleshooting

If you encounter any issues during the installation process, consider the following steps:

- Ensure all prerequisites are installed correctly.
- Double-check your internet connection, as some dependencies may need to be downloaded.
- Delete the `node_modules` directory and run `npm install --force` again.
- Check for any error messages in the console and resolve accordingly.

If the issue persists, feel free to seek help on the project's GitHub repository or contact the project maintainers.

Happy coding!
