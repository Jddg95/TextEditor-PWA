# Text Editor Web Application

## Description

This is a progressive web application (PWA) for creating and storing notes or code snippets. The application works offline and includes features such as IndexedDB for storage, service workers for offline capabilities, and webpack for bundling JavaScript files. The application is deployable and can be installed as a desktop icon.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

To install and set up the application locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/Jddg95/TextEditor-PWA.git
   ```

2. Navigate to the project directory 
    ```sh
    cd TextEditor-PWA 
    ```

3. Build the application:
    ```sh
    npm run build
    ```

4. Start the application:
    ```
    npm start
    ```

This will start both the backend and the client, serving the application in your browser. 

## Usage 

To use the text editor:

1. Open the application in your browser.

2. Enter your notes or code snippets.

3. Choose the app, and it will open in a separate window. (Next to the URL in Chrome, a box with an arrow pointing outside the right top corner)

4. Your content is automatically saved using IndexedDB when you click off the DOM window.

5. Reopen the application to see your previously saved content.


## Technologies

- Node.js
- Express.js
- React
- Webpack
- IndexedDB
- Service Workers (Workbox)
- Render (for deployment)

