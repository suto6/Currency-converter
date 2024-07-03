Currency Converter
This is a simple and intuitive currency converter application built with React. The app allows users to convert an amount from one currency to another using real-time exchange rates. The UI is designed to be user-friendly and responsive, making it easy for users to perform currency conversions on any device.

Features
Real-time Currency Conversion: Convert amounts from one currency to another using up-to-date exchange rates.
Swap Currencies: Easily swap the "From" and "To" currencies with a single click.
Responsive Design: The application is designed to be fully responsive and works seamlessly on all devices.
User-friendly Interface: Simple and clean UI for a smooth user experience.
Technologies Used
React: A JavaScript library for building user interfaces.
Tailwind CSS: A utility-first CSS framework for styling the application.
Currency API: Fetching real-time currency data from @fawazahmed0/currency-api.
Getting Started
Follow these steps to get a copy of the project up and running on your local machine.

Prerequisites
Node.js
npm or yarn
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/currency-converter.git
cd currency-converter
Install the dependencies:

bash
Copy code
npm install
or

bash
Copy code
yarn install
Start the development server:

bash
Copy code
npm start
or

bash
Copy code
yarn start
Open your browser and navigate to http://localhost:3000 to see the app in action.

Project Structure
src/components: Contains the InputBox component for the input fields.
src/hooks: Contains the custom hook useCurrencyInfo to fetch currency data.
src/App.jsx: Main application component.
How to Use
Enter the amount you want to convert in the "From" field.
Select the currency you are converting from.
Select the currency you are converting to.
Click the "Convert" button to see the converted amount.
Use the "Swap" button to switch the "From" and "To" currencies.
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License.
