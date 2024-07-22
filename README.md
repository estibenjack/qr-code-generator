# QR Code Generator

A simple command-line tool to generate QR codes from URLs and save them as image files. It also saves the input URL to a text file.

## Features

- Prompts the user for a URL.
- Generates a QR code image for the URL.
- Saves the QR code as a PNG file.
- Saves the URL to a text file.

## Requirements

- Node.js (v14 or higher recommended)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/qr-generator.git
   cd qr-generator# qr-code-generator
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

## Usage

1. **Run the script**:
   ```bash
   node index.js
   ```

2. **Follow the prompt to enter the URL you want to generate a QR code for.**

3. **Check the output:**
   - The QR code will be saved as `qr_img.png` in the project directory.
   - The URL will be saved in `URL.txt`.

## Example

```bash
$ node index.js
Type in your URL: https://example.com

The file has been saved!
```

This will generate a `qr_img.png` file containing the QR code for `https://example.com`, and `URL.txt` containing the URL.

## Acknowledgements

This project was completed as part of [Angela Yu's Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/) on Udemy. 
