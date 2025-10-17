# Captcha Solver Demo

This repository contains a client-side web application demonstrating a basic interface for loading and "solving" captcha images. It allows users to input an image URL (or uses a default local image) and then enter a potential solution for the displayed captcha.

## Features

*   **Load Captcha by URL:** Easily load any captcha image by providing its URL.
*   **Default Image Support:** Defaults to `sample.png` if no URL is specified.
*   **User Input for Solution:** Provides an input field for users to enter their captcha solution.
*   **Client-Side Demo:** Illustrates the frontend interaction for a captcha challenge. (Note: actual captcha validation typically requires server-side logic).
*   **Responsive Design:** Built with Tailwind CSS for a modern, responsive user experience across different devices.

## How to Use

To run this application:

1.  **Save the files:** Save `index.html`, `README.md`, `LICENSE`, and `sample.png` in the same directory.
2.  **Open `index.html`:** Open the `index.html` file directly in your web browser.

### Loading Custom Captcha Images

You can specify an image URL in two ways:

1.  **Using the input field:** Enter the desired image URL into the "Image URL" input box and click "Load Captcha Image".
2.  **Via URL parameter:** Append `?url=` followed by the image URL to your browser's address bar when opening `index.html`.
    *   Example: `file:///path/to/your/index.html?url=https://example.com/some-captcha.png`
    *   Example: `file:///path/to/your/index.html?url=another-image.jpg` (if `another-image.jpg` is in the same directory)

### Solving the Captcha

1.  Once an image is loaded, type your solution into the "Your Solution" input field.
2.  Click "Submit Solution". The application will display your submitted solution (without actual server-side validation).

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** For styling and responsive design.
*   **JavaScript:** For dynamic behavior and handling image loading/submission logic.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.
