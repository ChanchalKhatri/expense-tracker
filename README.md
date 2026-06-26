# Expense Tracker

A modern, beautiful expense tracking application built with React, Vite, and TailwindCSS. Track, manage, and organize your daily expenses with ease.

![Preview](public/preview.png)

## Features

- **Add Expenses**: Easily add expenses with amount, category, description, and date
- **Category Management**: Choose from predefined categories (Food, Transport, Shopping, Bills, Entertainment, Health, Other)
- **Expense List**: View all your expenses in a beautiful card layout
- **Delete Expenses**: Remove expenses with a single click
- **Total Calculation**: Automatically calculates and displays total expenses
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations and transitions
- **Indian Rupee Support**: Built-in support for ₹ currency

## Tech Stack

- **React 19** - UI library
- **Vite** - Build tool and dev server
- **TailwindCSS 4** - Styling
- **shadcn/ui** - UI components
- **Lucide React** - Icons
- **Radix UI** - Headless UI primitives

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ChanchalKhatri/expense-tracker.git
cd expense-tracker
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Usage

1. **Add an Expense**:
   - Enter the amount
   - Select a category from the dropdown
   - Add a description (optional)
   - Select the date
   - Click "Add Expense"

2. **View Expenses**:
   - All expenses are displayed in a card layout
   - Each card shows the amount, category, date, and description
   - Total expenses are displayed at the top

3. **Delete an Expense**:
   - Click the trash icon on any expense card to remove it

## Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

## Preview Production Build

```bash
npm run preview
```

## Project Structure

```
expense-tracker/
├── src/
│   ├── components/
│   │   ├── ui/          # shadcn/ui components
│   │   ├── ExpenseCard.jsx
│   │   ├── ExpenseForm.jsx
│   │   └── ExpenseList.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
└── vite.config.js
```

## License

MIT License - feel free to use this project for personal or commercial purposes.
