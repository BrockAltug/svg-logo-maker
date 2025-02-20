# SVG Logo Maker

## Description

The SVG Logo Maker is a Node.js command-line application that allows users to create customized SVG logos by entering simple prompts. Users can personalize their logos by choosing the logo text, text color, shape, and shape color, resulting in a unique SVG file that suits their preferences.

## Table of Contents

- [Description](#description)
- [How to Use](#how-to-use)
- [Example Output](#example-output)
- [Running Tests](#running-tests)
- [Technologies Used](#technologies-used)
- [Future Improvements](#future-improvements)
- [Summary](#summary)

## How to Use

1. **Clone the Repository:**

   - Clone the project to your local machine using:
     ```bash
     git clone https://github.com/BrockAltug/svg-logo-maker.git
     ```

2. **Install Dependencies:**

   - Navigate to the project directory and run:
     ```bash
     npm init -y
     npm install
     ```
     Install additional packages:
     ```bash
     npm install inquirer@8.2.4
     npm install --save-dev jest
     ```

3. **Run the Application:**

   - Start the logo generator by running:
     ```bash
     node index.js
     ```

4. **Follow the Prompts:**
   - Enter the desired text (up to 3 characters).
   - Choose the text color (keyword or hexadecimal).
   - Select a shape (Circle, Triangle, or Square).
   - Specify the shape color (keyword or hexadecimal).
   - The application will generate an SVG logo based on your input and save it as `logo.svg` in the `examples` directory.

## Example Output

A sample logo generated by this application can be found at:

- `examples/logo.svg`

<img src="./assets/images/demo.png" alt="Sample Logo" width="200">

## Running Tests

The application includes unit tests to ensure functionality. Run the following command to execute the tests using Jest:

```bash
npm run test
```

<img src="./assets/images/demo1.gif" alt="Demo Vid">
<img src="./assets/images/demo2.gif" alt="Demo Test">

## Technologies Used

- **Node.js**: The core platform for building the command-line application.
- **Inquirer.js**: For handling user inputs and prompts.
- **Jest**: To perform unit testing and ensure the reliability of the code.

## Future Improvements

- **Additional Shapes**: Introduce more shapes (e.g., hexagons, stars) to provide more design options.
- **Text Styling Options**: Allow users to choose different fonts, sizes, and other text styling properties.
- **Multiple Logo Designs**: Enable users to create multiple logos in a single session.
- **Color Palette**: Add a feature to let users pick colors from a predefined palette.

## Summary

The SVG Logo Maker is an easy-to-use command-line tool that empowers users to quickly create personalized SVG logos. It offers flexibility in design, allowing users to select their desired text, colors, and shapes, resulting in a tailored logo creation experience. Perfect for anyone looking to craft simple yet effective logos without the need for complex software.
