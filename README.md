# Restaurant Tip Calculator

A simple, user-friendly web application that helps calculate tips and split bills among multiple people.

## Features

- Calculate tips with customizable percentage
- Quick tip selection buttons (15%, 18%, 20%)
- Split bill functionality
- Real-time error validation
- Clean and responsive design

## Usage

1. Enter the bill amount in the "Bill Amount ($)" field
2. Choose a tip percentage using either:
   - Quick tip selection buttons (15%, 18%, 20%)
   - Custom tip percentage input field
3. If splitting the bill, enter the number of people
4. Click "Calculate Tip" to see the results
5. Use "Reset" button to clear all inputs and start over

## Input Fields

- **Bill Amount ($)**: Enter the total bill amount (required)
- **Quick Tip Selection**: Click on preset tip percentages (15%, 18%, 20%)
- **Custom Tip (%)**: Enter a custom tip percentage between 0-100
- **Split Between**: Enter the number of people sharing the bill (defaults to 1)

## Validation

The calculator includes the following validation features:
- Bill amount must be greater than 0
- Tip percentage must be between 0 and 100
- Number of people must be at least 1
- Error messages display when invalid input is detected

## Development

### Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)

### Structure
- Responsive layout using CSS Flexbox
- Mobile-friendly design
- Modern UI with visual feedback
- Modular JavaScript code using object-oriented programming

## Browser Support

The calculator works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Local Development

1. Clone the repository
2. Open `tipcalculator.html` in your web browser
3. No additional dependencies or build steps required
