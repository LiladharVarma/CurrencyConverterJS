# Currency Converter

Welcome to the Currency Converter repository! This project provides a simple web-based currency converter that allows users to convert between different currencies. The converter is built using HTML, CSS, and JavaScript, and it incorporates basic API functionality to fetch real-time exchange rates.

## Demo

You can check out the live demo of the Currency Converter by following this link: [Currency Converter Demo](https://liladharvarma.github.io/CurrencyConverterJS/)

## Features

- **User-Friendly Interface:** The converter has a clean and intuitive interface, making it easy for users to understand and use.
- **Real-Time Exchange Rates:** The application utilizes a currency exchange API to fetch the latest exchange rates, ensuring accuracy in currency conversion.
- **Multi-Currency Support:** Users can convert between a wide range of currencies, providing flexibility for various international transactions.

## Usage

1. Visit the [demo link](https://liladharvarma.github.io/CurrencyConverterJS/) to access the Currency Converter.
2. Select the source currency from the dropdown menu.
3. Enter the amount you want to convert.
4. Choose the target currency from another dropdown menu.
5. Click the "Convert" button to see the converted amount.

## Development

If you want to run the project locally or contribute to its development, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/liladharvarma/CurrencyConverterJS.git
   ```

2. Open the project folder:

   ```bash
   cd CurrencyConverterJS
   ```

3. Open the `index.html` file in your preferred web browser or use a local development server.

## API Integration

The Currency Converter uses a third-party API to fetch real-time exchange rates. The API used in this project is ExchangeRate API. You can obtain your API key by following the instructions on their website and replace it in the `script.js` file.

```javascript
// Replace 'YOUR_API_KEY' with your actual API key
const apiKey = 'YOUR_API_KEY';
const apiUrl = `https://api.example.com/currency/convert?apikey=${apiKey}&...`;
```


Thank you for checking out the Currency Converter! If you have any questions, feedback, or suggestions, feel free to open an issue or contribute to the project. Happy coding!
