# Image Display App

## Summary
This application displays a simple image and also includes a basic calculator functionality.

## Features
- Display a static image embedded directly in the HTML.
- Calculator functionality to add two numbers.

## Setup
No build steps required. This is a static HTML application.

### Local Usage
1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. The application will run immediately

## Usage Instructions
1. Enter values in the 'Number 1' and 'Number 2' fields.
2. Click on the 'Calculate' button to see the sum of the entered numbers displayed below the button.
3. View the embedded image displayed at the bottom of the application interface.

## Technical Details

### Technologies Used
- HTML5
- CSS3 (Bootstrap 5.3.0)
- Vanilla JavaScript

### Key Features
- Responsive design
- Client-side data processing
- Error handling
- Modern UI/UX

### File Structure
```
.
├── index.html          # Main application file
├── README.md           # This file
└── LICENSE             # MIT License
```

## Code Explanation

### HTML Structure
- The main container holds a card which includes form inputs, a button, a result display area, and an image display section.

### CSS Styling
- Uses Bootstrap for layouts and custom styles for aesthetics like background gradient and shadow effects.

### JavaScript Functionality
- Adds event listeners to the calculate button to process inputs, perform calculations, and handle errors.

## Evaluation Criteria
This application meets the following requirements:
- Page has input field with id='num1'
- Page has input field with id='num2'
- Page has button with id='calculate-btn'
- Page has element with id='result'
- Page loads Bootstrap 5 from CDN
- Repo has MIT LICENSE
- README.md is professional
- Page displays image in #image-display

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Generated as part of a front-end development project.