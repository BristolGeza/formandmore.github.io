# Easy Quiz

This project is a simple web-based quiz application that displays a random image and asks the user to identify it from a list of options. The user submits their answer through a form, and the application provides feedback on whether the answer is correct or not.

## Project Structure


- `assets/css/style.css`: Contains the CSS styles for the application.
- `assets/images/`: Directory where the images used in the quiz are stored.
- `control.php`: Placeholder for any server-side logic (not implemented in this project).
- `index.html`: The main HTML file that structures the web page.
- `script.js`: Contains the JavaScript code for the quiz functionality.
- `README.md`: This file.

## Features

- Displays a random image from a predefined list when the page loads.
- Provides a form for the user to submit their name, email, and answer.
- Validates the user's answer and displays a message indicating whether the answer is correct or not.
- Includes basic styling and hover effects for images.

## Usage

1. Clone the repository or download the project files.
2. Open `index.html` in a web browser.
3. The page will display a random image.
4. Fill in the form with your name, email, and select the correct answer from the dropdown.
5. Submit the form to see if your answer is correct.

## JavaScript Functions

### `displayRandomImage()`

This function selects a random image from the `images` array and displays it in the `image-container` element.

### `showData(e)`

This function handles the form submission, validates the user's answer, and displays a message indicating whether the answer is correct or not.

## CSS Styling

The CSS file `assets/css/style.css` includes styles for the body, header, form elements, and images. It also includes hover effects for images.

## License

This project is open-source and available under the MIT License.