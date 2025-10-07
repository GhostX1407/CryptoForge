# CryptoForge - A Cryptography and Encoding Tool
CryptoForge is a versatile, client-side web application that allows you to encode, decode, and hash text using a variety of common cryptographic and encoding techniques. It's built with simplicity and ease of use in mind, requiring no backend or special setup to run.

Live Demo 
[Click Here!](https://ghostx1407.github.io/CryptoForge/CryptoForge.html)

Features :

CryptoForge provides a clean, minimal interface and supports the following techniques:

Base64 Encoding & Decoding: Easily encode your data into Base64 or decode it back to its original form. Correctly handles UTF-8 characters.

URL Encoding & Decoding: Make your text safe for inclusion in URLs.

Hashing Algorithms:

MD5: Generate an MD5 hash of your input.

SHA-256: Generate a secure SHA-256 hash using the modern Web Crypto API.

Classic Ciphers:

Caesar Cipher: Encrypt your text with a simple substitution cipher. You can specify a custom shift value (1-25).

Encoding Schemes:

Morse Code: Convert text to Morse code and vice-versa.

Simple Transformations:

Reverse Text: A fun and simple way to obfuscate text by reversing its order.

User Interface Features
Responsive Design: Looks great on desktops, tablets, and mobile devices.

Copy to Clipboard: Instantly copy the output with a single click.

Dynamic UI: The interface adapts to your selections, showing relevant options like the Caesar Cipher shift only when needed.

Error Handling: Provides user-friendly error messages for invalid operations (e.g., trying to Base64-decode an invalid string).

Minimalist Aesthetic: A clean, light theme that's easy on the eyes.

How to Use
Since CryptoForge is a single, self-contained HTML file, using it is incredibly simple:

Download: Clone this repository or download the crypto_tool.html file.

Open: Open crypto_tool.html in any modern web browser (like Chrome, Firefox, or Edge).

Use:

Enter your text into the "Input Text" area.

Select your desired technique from the dropdown menu.

Click the Transform button.

The result will appear in the "Output" area, ready to be copied.

Technologies Used
HTML5: For the structure of the application.

Tailwind CSS: For a modern, utility-first approach to styling.

Vanilla JavaScript (ES6+): For all the logic and functionality. No external frameworks or libraries are needed (besides Tailwind for styling).

Web Crypto API: Used for the secure implementation of the SHA-256 hash.

Contributing
Contributions are welcome! If you have ideas for new features, find a bug, or want to improve the code, please feel free to open an issue or submit a pull request.

License
This project is open-source and available under the MIT License.

Made by Jaivin Vachhani Email: jaivinvachhani@gmail.com
