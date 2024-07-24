

# Windows to WSL Path Converter

This is a simple web application that converts Windows file paths to WSL (Windows Subsystem for Linux) format. This tool is particularly useful for developers who frequently switch between Windows and WSL environments and need a quick way to translate file paths.

## Features

- **Path Conversion**: Converts Windows file paths (e.g., `C:\Users\alfred\Desktop\git_training`) to WSL format (e.g., `/mnt/c/Users/alfred/Desktop/git_training`).
- **Quotation Handling**: Automatically adds quotes around folder names containing spaces to ensure proper path formatting.
- **Copy to Clipboard**: Easily copy the converted WSL path to the clipboard for quick use.

## How to Use

1. Enter the Windows file path in the input field.
2. Click the "Convert to WSL Format" button to generate the WSL path.
3. The converted path will be displayed in the output area.
4. Click the "Copy" button to copy the WSL path to the clipboard.

## Demo

![Demo GIF](path/to/demo.gif)

## Installation

No installation required! Simply open `index.html` in your web browser to use the application.

## Code

Here is the main structure of the project:

- **HTML**: The main structure of the web app.
- **CSS**: Styling for a dark-themed interface.
- **JavaScript**: Handles path conversion and clipboard functionality.

## Example

Input:
```
C:\Users\alfred\Desktop\git_training
```

Output:
```
cd /mnt/c/Users/alfred/Desktop/git_training
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to contact me at jakewilsone42@gmail.com

