# QR Code Generator

This Python project generates a QR code for a given URL, specifically for a portfolio website. The QR code is created using the `qrcode` library, with customizable settings for the color and size.

## Features

- Generates a QR code for a specified URL.
- Uses high error correction to ensure the QR code remains readable even if slightly damaged.
- Allows customization of the QR code's fill and background colors.

## Prerequisites

Ensure that Python is installed on your system. The following Python libraries are also required:
- `qrcode`
- `Pillow` (PIL)

### Installing the Libraries

Install the required libraries using `pip`:

```bash
pip install qrcode
pip install pillow

### How to Clone the Repository
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/qr-code-generator.git
cd qr-code-generator
Replace your-username with your GitHub username if you plan to host the project on GitHub.

### How to Run the Script
Navigate to the project directory:

bash
Copy code
cd qr-code-generator
Run the Python script to generate the QR code:

bash
Copy code
python generate_qr.py
Find the generated QR code image, saved as my_portfolio.png, in the same directory.


