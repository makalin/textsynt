# Textarea Tabs + Syntax Highlighter

This project showcases an editable textarea that supports syntax highlighting, tab spaces, and features for toggling fullscreen mode. It is designed to allow users to edit code within a `textarea` while automatically highlighting the syntax, providing a seamless and user-friendly coding experience.

Live Preview: https://makalin.github.io/textsynt/

## Features

- **Syntax Highlighting**: Automatically highlights syntax within the textarea for improved readability and code editing experience.
- **Tab & Double Space Functionality**: Supports indentation through tabs or double spaces within the textarea.
- **Fullscreen Toggle**: Easily switch between fullscreen and normal view for focused editing.
- **Simple Toolbar**: Quick access to toolbar functions like indent and fullscreen mode.
- **Responsive Design**: Built with Foundation CSS framework for responsive and modern styling.

## Project Structure

- **HTML File**: `index.html` is the main file that holds the structure for the editor and its functionalities.
- **CSS**: Styles are provided via external stylesheets and `Foundation` for responsive design.
  - `./css/style.css`: Custom styling for the editor.
- **JavaScript**: The project uses jQuery, Highlight.js for syntax highlighting, and a custom script for managing the editor.
  - `./js/script.js`: Main script for handling interactions in the editor.
  - `./js/emmet.min.js`: Additional support for Emmet abbreviations in the editor.

## Getting Started

### Prerequisites

Ensure you have a modern web browser to view the project and have a stable internet connection for external library dependencies.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/makalin/textsynt.git
   ```
2. Navigate to the project directory:
   ```bash
   cd textsynt
   ```
3. Open `index.html` in a web browser to view the editor.

### Usage

1. The textarea allows users to enter or paste code, which will be highlighted automatically.
2. Use the toolbar to toggle between tab and spaces for indentation or enable fullscreen mode.
3. Customize the syntax highlighting or add new functionalities by modifying the scripts in `./js/script.js` or by including additional libraries as needed.

### Dependencies

- [Foundation CSS](https://foundation.zurb.com/)
- [jQuery](https://jquery.com/)
- [Highlight.js](https://highlightjs.org/)

### Contributing

Feel free to fork the repository and make contributions. Create a pull request with any improvements or new features you would like to add.

### License

This project is open-source and available under the [MIT License](LICENSE).
