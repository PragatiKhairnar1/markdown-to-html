# Markdown Viewer Application

This is a simple, single-page web application designed to convert Markdown content from an `input.md` file into HTML and display it dynamically in a responsive user interface.

## Features

- **Markdown to HTML Conversion**: Utilizes the `marked` library to parse Markdown syntax and render it as styled HTML.
- **Responsive Design**: Built with Tailwind CSS, ensuring a consistent and user-friendly experience across various devices and screen sizes.
- **Single-File Application**: All HTML, CSS (via Tailwind CDN), and JavaScript (via `marked` CDN and inline script) are contained within `index.html` for easy deployment.
- **Local Content Loading**: Fetches `input.md` directly from the same directory, making it suitable for local project documentation or simple content display.

## Usage

1.  **Save the files**: Place `index.html` and your Markdown file (`input.md`) in the same directory.
2.  **Open in Browser**: Open the `index.html` file with any modern web browser (e.g., Chrome, Firefox, Safari, Edge).
3.  **View Content**: The application will automatically fetch `input.md`, convert its content to HTML, and display it on the page.

### Example `input.md` Content (for testing):

```markdown
# Welcome to the Markdown Viewer

This is a sample **Markdown** document.

## Features of Markdown

-   Easy to read and write syntax.
-   Converts to HTML effortlessly.
-   Supports various formatting options:
    -   *Italic text*
    -   **Bold text**
    -   `Inline code`

### Code Example

```javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
}
greet('World');
```

### Links and Images

Visit [Google](https://www.google.com).

> This is a blockquote, often used for citations or emphasized text.

## Get Started

Simply edit the `input.md` file and refresh your browser to see the changes!
```

## Local Development

No build steps are required for this application. Simply opening `index.html` in a browser will run the app. Ensure `input.md` is present in the same directory for the application to function correctly.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS**: For responsive styling and utility-first CSS.
-   **Marked.js**: A fast Markdown parser and compiler for JavaScript.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.