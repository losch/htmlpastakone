# Pastakone

![Screenshot](./screenshot.png?raw=true)

Pastakone is a simple tool that allows users to add code snippets and share
them with others. It has an Ace editor component and uses Pako compression
library to compress the code snippets, which are stored as compressed query
parameters. There is no need for a database or backend.
The tool can be easily installed by simply dropping it into a web server
that can serve an HTML page.

## Installation

To install Pastakone, simply download the pastakone.html file from the
repository and upload it to your web server.

## Usage

1. Open the index.html file in your web browser.
2. Add your code snippet to the editor.
3. Click the "Share" button to generate a URL that can be shared with others.
4. Share the generated URL with others to allow them to view your code snippet.

## Dependencies

Pastakone is built using the following libraries:

* Ace editor: a lightweight code editor written in JavaScript.
* Pako compression library: a high-speed JavaScript library for compressing and
  decompressing data.
* Water.css: a minimal CSS framework for modern web applications.

## License

Pastakone is released under the MIT License. See the LICENSE file for more
information.
