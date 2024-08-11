# Currency Converter

![React](https://img.shields.io/badge/React-v18.2.0-blue.svg?style=flat&logo=react)
![Vite](https://img.shields.io/badge/Vite-v4.0.0-blueviolet.svg?style=flat&logo=vite)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v3.2.0-38B2AC.svg?style=flat&logo=tailwind-css)


## 📝 Overview

The **Currency Converter** is a web application that allows users to convert amounts from one currency to another using real-time exchange rates. This app is built with **React**, **Vite**, and **Tailwind CSS**, ensuring a fast, modern, and responsive user experience.

## ✨ Features

- 🌐 **Real-time Exchange Rates**: Fetches live exchange rates from a reliable API.
- 💻 **Responsive Design**: Designed with Tailwind CSS for a seamless experience across devices.
- 🔄 **Multiple Currencies**: Convert between a wide range of currencies.


## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/en/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

**1. Clone the repository**:

   ```bash
   git clone https://github.com/Rushikesh-purohit-0503/currency-converter.git
   cd currency-converter
   ```
   
 **2. Install Dependencies**:
 ```bash
 npm install 
 ```
 ## 🖌 Tailwind CSS Configuration

Customize your design in `tailwind.config.js` or add custom styles in `src/index.css`.

Make sure this Configurations is there in `tailwind.config.js`: 
```bash
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
## Also Make sure that below code is there in `index.css`:
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Technologies Used

- **[React](https://reactjs.org/)**: Front-end library for building user interfaces.
- **[Vite](https://vitejs.dev/)**: Next-generation front-end tooling for fast development and build times.
- **[Tailwind CSS](https://tailwindcss.com/)**: Utility-first CSS framework for rapid UI development.

   ## Acknowledgments

- **[ExchangeRatesAPI](https://exchangeratesapi.io/)** for providing the exchange rate data.
- **[React](https://reactjs.org/)** for the front-end library.
- **[Vite](https://vitejs.dev/)** for the fast development and build tool.
- **[Tailwind CSS](https://tailwindcss.com/)** for the utility-first CSS framework.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch** for your feature or bugfix.
3. **Make your changes** and commit them with descriptive messages.
4. **Push your changes** to your forked repository.
5. **Submit a pull request** with a detailed description of your changes.


