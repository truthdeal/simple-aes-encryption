# AES Encrypt/Decrypt Web Application

GitHub Pages: https://truthdeal.github.io/simple-aes-encryption/

This web application provides a client-side AES encryption and decryption service. It is designed to run entirely in the browser, with no server-side processing, ensuring that your data remains private and secure. You can load the website and use the application offline, as all the necessary files are included in the repository.

## Features

- AES encryption with a user-provided key and IV (Initialization Vector)
- AES decryption that matches the encryption process
- Client-side processing for enhanced security
- Responsive design for desktop and mobile browsers

## Usage

To use the application, follow these steps:

1. Open the https://truthdeal.github.io/simple-aes-encryption/ in a modern web browser.
2. Enter a 32-character key in the Key field.
3. Enter a 16-character IV in the IV field.
4. For encryption, enter the text you want to encrypt in the "Text to encrypt" textarea and click the "Encrypt" button.
5. For decryption, enter the AES-encrypted text in the "Text to decrypt" textarea and click the "Decrypt" button.
6. The encrypted or decrypted output will appear in the output area. Use the "Copy" button to copy the output to the clipboard.

## Client-Side Processing

All encryption and decryption processes are performed on the client side, which means that the data never leaves your browser. This design ensures that sensitive information is not exposed to the server or network, providing a secure way to handle encryption and decryption operations.

## Technologies

- HTML
- CSS
- JavaScript
- Web Crypto API

Remember to always keep your keys and IVs secure and never share them.