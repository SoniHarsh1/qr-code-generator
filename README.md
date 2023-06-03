# QR Code Generator

This is a simple Node.js application that allows users to enter a URL and generate a QR code image based on the entered URL. The application utilizes the `inquirer` npm package for user input, the `qr-image` npm package to create the QR code image, and the native `fs` module to save user input in a text file.

## Installation

1. Clone the repository:
```bash
    git clone <repository_url>
```

2. Navigate to the project directory:
```bash
   cd qr-code-generator
```

3. Install the dependencies:
```bash
   npm install
```

## Usage
To run the application, use the following command:
```bash
   node index.js
```

The application will prompt you to enter a URL. Once you've entered the URL, it will generate a QR code image and save it as qr_img.png. Additionally, the entered URL will be saved in a text file named URL.txt.

## Dependencies
- __inquirer__: A collection of common interactive command-line user interfaces.
- __qr-image__: A QR code generator.
- __fs__: A native Node.js module for interacting with the file system.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.

