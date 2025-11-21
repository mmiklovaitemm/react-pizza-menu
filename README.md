# Fast React Pizza Co.

A small practice React project that displays a simple pizza menu.  
The app shows a list of pizzas from a data array, marks sold-out items, and displays an open/closed message based on the current time.

## Features

- Header with the restaurant name (`Header` component)
- Dynamic pizza menu built from the `pizzaData` array
- Each pizza shows its image, name, ingredients, and price (or **SOLD OUT**)
- Footer that checks opening hours and shows:
  - an “Order” section during open hours
  - a closing message outside working hours

## Technologies Used

- React
- JavaScript (ES6+)
- JSX
- CSS (`index.css`)

## Project Structure

This project mainly consists of:

- **index.js** – contains all components, the pizza data, and renders the app
- **index.css** – styling for the layout and UI
- **/pizzas** – folder with pizza images used by the app

## How to Run the Project

1. Make sure **Node.js** and **npm** are installed.
2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the project:
   ```bash
   npm start
   ```
4. Open in browser:
   ```bash
   http://localhost:3000
   ```
