cURL to Code Converter
A simple, single-file web utility to deconstruct cURL commands and instantly generate equivalent code snippets in various programming languages. Built with vanilla JavaScript and styled with Tailwind CSS, this tool is designed for developers who frequently work with APIs and need a quick way to translate cURL commands into usable code.

✨ Features
Instant cURL Parsing: Automatically breaks down any cURL command into its core components:

URL

Request Method (GET, POST, etc.)

Headers

Request Body

Multi-Language Code Generation: Convert cURL commands into ready-to-use code snippets for:

JavaScript (with fetch API)

Python (with the requests library)

PHP (with its native cURL extension)

Go (with the net/http package)

Rust (with the reqwest crate)

Sleek & Responsive UI: A clean, dark-themed interface built with Tailwind CSS that works beautifully on all screen sizes.

Simple "Copy" Functionality:

Copy individual parsed parts (URL, body, etc.) with a single click.

Copy the entire generated code snippet.

A "Copy All" button to get all parsed details at once.

Zero Dependencies: A self-contained index.html file. No builds, no npm install, no fuss. Just open the file in your browser.

Smart Body Formatting: Automatically pretty-prints JSON bodies for better readability.

🚀 How to Use
Download: Get the curl_to_code.html file.

Open: Open the file directly in any modern web browser (like Chrome, Firefox, or Edge).

Paste & See the Magic:

Paste a cURL command into the input text area.

The tool will instantly parse the command and display the URL, method, headers, and body in their respective cards.

A code snippet in the default language (JavaScript) will be generated simultaneously.

Use the dropdown menu to select a different language and see the code update in real-time.

🛠️ Technologies Used
HTML5

Tailwind CSS (loaded via CDN)

Vanilla JavaScript (ES6+)

🤝 Contributing
Contributions are welcome! If you have ideas for new features, support for another language, or find a bug, feel free to open an issue or submit a pull request.

📄 License
This project is open-source and available under the MIT License.
