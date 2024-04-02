# LogoCrafterSVG
LogoCrafterSVG is a command-line application built with Node.js that enables users to create custom logos saved as SVG files. By following a simple interactive prompt, users can specify the logo's text, color, and shape to generate a personalized logo.

## Features
- Interactive CLI prompts for custom logo creation.
- Supports multiple shapes: Circle, Triangle, Square.
- Allows custom text (up to three characters) and color selection for both text and shape.
- Generates logos as SVG files.
## Installation
To use LogoCrafterSVG, you'll need to have Node.js installed on your computer. If you don't have Node.js installed, download it from nodejs.org
Clone this repository to your local machine:
git clone https://yourrepositorylink.com/LogoCrafterSVG.git
Install the required dependencies:
npm install inquirer@8.2.4
npm install jest@28.1.3

## Usage
To start creating your logo, run:
node index.js

Follow the interactive prompts to choose your logo's text, text color, shape, and shape color. After completing all prompts, your logo will be saved as logo.svg in the current directory, and you'll see a message indicating the file has been generated.

Example of creating a logo with a circle shape:

Enter up to three characters for the logo text: ABC
Enter the text color (keyword or hex):red
Choose a shape: circle
Enter the shape color (keyword or hex): #FF5733
Generated logo.svg

## Credit
This project was created by Ummul Mukta to demonstrate skills in generating custom logos. It leverages the inquirer package for interactive user prompts and jest for testing.


## License
This project is licensed under the MIT License.

## Acknowledgments
Node.js and the npm community for the invaluable packages.
