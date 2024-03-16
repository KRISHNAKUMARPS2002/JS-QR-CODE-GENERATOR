## Installation

1. Clone this repository to your local machine using `git clone https://github.com/your-username/qr-code-generator.git`.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install the required dependencies.

## Usage

1. Open your terminal and navigate to the project directory.
2. Run the application using `node index.js`.
3. Follow the prompts to enter the URL for which you want to generate a QR code.
4. After entering the URL, a QR code image will be generated and saved as `qr_img.png` in the project directory.
5. The URL will also be saved to a text file named `URL.txt` in the project directory.

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): For user input prompts.
- [qr-image](https://www.npmjs.com/package/qr-image): For generating QR code images.
- [fs](https://nodejs.org/api/fs.html): Node.js built-in module for file system operations.

## Contributing

Contributions are welcome! If you'd like to improve this project, please fork the repository and submit a pull request.
