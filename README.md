# PWA Challenge: Text Editor

Progressive Web Applications (PWA) push the boundaries of web capabilities to deliver app-like experiences. This text editor is designed to showcase advanced PWA features, enabling you to write, save, and manage text documents directly in your browser, even without an internet connection. With persistent data storage using modern web technologies, your notes and code snippets are safely stored and retrievable anytime, anywhere. This text editor stands out by offering a seamless user experience that mimics the functionality of native apps, accessible from any web browser.

## Description

This project develops a browser-based text editor that functions as a single-page application meeting PWA criteria. It incorporates various data persistence techniques to ensure functionality even when certain browser features are unsupported. The editor is capable of running offline and utilizes the `idb` package—a lightweight wrapper for IndexedDB—to handle data storage and retrieval efficiently. This project is a demonstration of real-world application development.


![Prueba](https://github.com/caiman48/Text-Editor/assets/102683872/4412dae4-0bfd-439b-adb9-79890a115998)



## Installation

### Prerequisites
- Node.js 

### Steps
1. Clone the starter code from the provided repository.
2. Navigate to the cloned repository's directory in your terminal.
3. Run `npm install` to install all required dependencies.

## Usage

To get started with the text editor:
1. Navigate to the repository's directory in your terminal.
2. Run `npm run start` to initiate the server and serve the client.
3. Access the application in your browser at `localhost:3000`.
4. Enjoy creating, editing, and viewing your notes or code snippets, online or offline.

## Features

- **Offline Functionality**: Full PWA compliance allows for robust offline capabilities.
- **Data Persistence**: Utilizes IndexedDB with the `idb` package for reliable data storage.
- **Modern Tooling**: Bundled with webpack, includes auto-generated HTML, service worker, and manifest files.
- **Deployment Ready**: Includes proper build scripts for deployment on platforms like Render.

## Deployment

Follow the Render Deployment Guide to deploy your application. Ensure your webpack application's build scripts are configured correctly for a smooth deployment process.

## License

This project is released under the MIT License. [Learn more about the MIT License](https://opensource.org/licenses/MIT).

## Questions

For any queries regarding this project, feel free to contact me via email at [your-email](mailto:your-email) or visit my GitHub profile at [your-github](https://github.com/your-github).
