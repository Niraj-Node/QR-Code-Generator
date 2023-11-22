# API-based QR Code Generator

This repository contains code for an API-based QR code generator utilizing the `https://api.qrserver.com/v1/create-qr-code/` API.

## Description

This project provides a simple way to generate QR codes using the QR Code Generator API. The API allows users to generate QR codes by specifying the size and the data to be encoded in the QR code.

## Usage

To generate a QR code, make a GET request to the following endpoint:
https://api.qrserver.com/v1/create-qr-code/?size=SIZE&data=DATA

Replace `SIZE` with the desired dimensions (e.g., `150x150`) and `DATA` with the information you want to encode in the QR code.

For example:
https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://example.com


This will generate a QR code with a size of 150x150 pixels that encodes the URL `https://example.com`.

## Files Included

- `index.html`: Contains implementation of the usage of API to generate QR codes.
- `style.css`: Stylesheet file for basic styling of the example page.
- `script.js`: JavaScript file handling API requests and QR code display.

## Getting Started

1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Modify the API request in the JavaScript file (`script.js`) to generate QR codes based on your requirements.

## Additional Notes

- Ensure a stable internet connection to use the API.
- The QR code size and data can be dynamically adjusted based on your application's needs.

## Resources

- https://goqr.me/api/
