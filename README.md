# QR Code Generator Project

This project aims to create a simple command-line tool that generates a QR code image and saves it along with the original URL in separate files.

## Prerequisites

Before starting, make sure you have the following software installed:

1. Node.js: Download and install it from [https://nodejs.org/](https://nodejs.org/)

## Installation

1. Clone the repository or download the project files.
2. Open your terminal or command prompt and navigate to the project directory.
3. Run `npm install` to install the required dependencies.

## Usage

1. Run the application using the command `node index.js`.
2. You will be prompted to enter a URL.
3. Type in the desired URL and press Enter.
4. The application will generate a QR code image and save it as `qr_img.png` in the project directory.
5. It will also save the URL in a text file named `URL.txt` within the same directory.
6. Upon successful saving, a message "The file has been saved!" will be displayed.

## Dependencies

This project uses the following NPM packages:

1. [Inquirer](https://www.npmjs.com/package/inquirer): A popular package to create interactive command-line user interfaces.
2. [QR-Image](https://www.npmjs.com/package/qr-image): A package to generate QR code images.
3. [Fs (File System)](https://www.npmjs.com/package/fs): A built-in Node.js module to work with the file system.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to create a pull request or submit an issue.
