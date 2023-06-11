# Currency Converter
Currency Converter Using HTML,Css,javascript and currency exchange Api


This is a simple currency converter application built using HTML, CSS, JavaScript, and a currency exchange API. The application allows users to convert between different currencies using real-time exchange rates.

# Demo
You can see a live demo of the application [Here](https://shubhamu63.github.io/Currency-converter/).
## Features

- Real-time currency conversion using an API
- Supports conversion between multiple currencies
- User-friendly interface

## Technologies Used

- HTML
- CSS
- JavaScript

## APIs Used

- [Currency Exchange API](https://v6.exchangerate-api.com): This API provides real-time exchange rates for different currencies.

## Getting Started

To run the currency converter application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ShubhamU63/Currency-converter.git
   ```

2. Open the project directory:

   ```bash
   cd Currency-converter
   ```

3. Open the `index.html` file in your preferred web browser.

## Configuration

To use the currency exchange API, you will need to sign up for an API key. Once you have the API key, replace the `apiKey` variable in the 
`api-key.js` file with your actual API key.

```javascript
let apiKey = 'your-api-key';
```

## Usage

1. Enter the amount you want to convert in the "Amount" field.
2. Select the currency you want to convert from in the "From" dropdown.
3. Select the currency you want to convert to in the "To" dropdown.
4. Click the "Convert" button.
5. The converted amount will be displayed below.
