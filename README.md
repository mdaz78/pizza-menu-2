# Pizza Menu App 🍕

A modern React application showcasing a pizza restaurant menu. Built with React 19 and Vite, this project demonstrates component-based architecture and modern React patterns.

## Features

- **Interactive Menu Display**: Browse through a curated selection of authentic Italian pizzas
- **Real-time Availability**: See which pizzas are currently sold out
- **Dynamic Hours Display**: Footer automatically shows order availability based on current time (open 9:00 - 22:00)
- **Responsive Design**: Clean and modern UI with smooth user experience

## Project Structure

```
pizza-menu/
├── src/
│   ├── components/
│   │   ├── Header.jsx      # Restaurant header component
│   │   ├── Menu.jsx        # Main menu container
│   │   ├── Pizza.jsx       # Individual pizza card component
│   │   ├── Footer.jsx      # Footer with order information
│   │   └── Order.jsx       # Order call-to-action component
│   ├── data/
│   │   └── data.js         # Pizza data source
│   ├── App.jsx             # Main application component
│   ├── main.jsx            # Application entry point
│   └── index.css           # Global styles
├── public/
│   └── pizzas/             # Pizza images
└── package.json
```

## Components

### Header

Displays the restaurant name "Fast React Pizza Co."

### Menu

- Renders the complete pizza menu
- Dynamically displays pizza items from the data source
- Shows a message if the menu is empty

### Pizza

- Individual pizza card component
- Displays pizza image, name, ingredients, and price
- Shows "SOLD OUT" status for unavailable items

### Footer

- Conditionally renders based on current time
- Shows order information when open (9:00 - 22:00)
- Displays hours message when closed

### Order

- Order call-to-action component
- Displays closing time and order button

## Technologies

- **React** ^19.2.0
- **Vite** ^7.2.2
- **ESLint** for code quality

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository or navigate to the project directory
2. Install dependencies:

```bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the port shown in the terminal).

### Build

Create a production build:

```bash
npm run build
```

### Preview

Preview the production build:

```bash
npm run preview
```

### Linting

Run ESLint to check code quality:

```bash
npm run lint
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Pizza Menu

The app features 6 delicious pizza options:

1. **Focaccia** - Bread with Italian olive oil and rosemary ($6)
2. **Pizza Margherita** - Tomato and mozzarella ($10)
3. **Pizza Spinaci** - Tomato, mozzarella, spinach, and ricotta cheese ($12)
4. **Pizza Funghi** - Tomato, mozzarella, mushrooms, and onion ($12)
5. **Pizza Salamino** - Tomato, mozzarella, and pepperoni ($15) - _Currently Sold Out_
6. **Pizza Prosciutto** - Tomato, mozzarella, ham, arugula, and burrata cheese ($18)

## Learning Objectives

This project demonstrates:

- React functional components
- Component composition and props
- Conditional rendering
- Array mapping for dynamic lists
- Modern React patterns and best practices
- Vite build tooling

## License

This project is part of "The Ultimate React Course 2025" learning materials.
