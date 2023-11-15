# My HTML/CSS Project

This project uses HTML, CSS, and SCSS with a 7-1 architecture. It also includes a reset to ensure consistency across different browsers.

## Project Structure

The project has the following structure:

- `css/main.css`: The compiled version of the SCSS files. It contains all the styles used in the project.
- `css/reset.css`: Resets the default styles of the browser to ensure consistency across different browsers.
- `scss/abstracts/_variables.scss`: Contains all the SCSS variables used in the project.
- `scss/abstracts/_functions.scss`: Contains all the SCSS functions used in the project.
- `scss/base/_reset.scss`: Contains the SCSS version of the reset styles.
- `scss/base/_typography.scss`: Contains the base typography styles for the project.
- `scss/components/_buttons.scss`: Contains the styles for the buttons used in the project.
- `scss/layout/_header.scss`: Contains the styles for the header of the project.
- `scss/layout/_footer.scss`: Contains the styles for the footer of the project.
- `scss/pages/_home.scss`: Contains the styles for the home page of the project.
- `scss/themes/_theme.scss`: Contains the styles for the theme of the project.
- `scss/vendors/_bootstrap.scss`: Contains the Bootstrap styles used in the project.
- `scss/main.scss`: Imports all the other SCSS files. It is the file that gets compiled into `css/main.css`.
- `index.html`: The main HTML file of the project. It includes the `css/main.css` and `css/reset.css` files.

## Setup

To set up the project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Open `index.html` in your browser to view the project.

## Running the Project

To run the project, simply open the `index.html` file in your browser. The styles are already compiled into `css/main.css`, so there's no need to compile the SCSS files unless you make changes to them.

If you do make changes to the SCSS files, you'll need to recompile them into `css/main.css`. You can do this using a tool like [Sass](https://sass-lang.com/install).

## Contributing

Contributions are welcome. If you find a bug or have a suggestion for improvement, please open an issue or submit a pull request.