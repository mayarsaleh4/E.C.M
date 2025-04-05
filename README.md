# E.C.M

## Overview

E.C.M is a Energy Consumption Monitor website that is built using React and Vite, providing a minimal setup and a lot of features to users.

## Features
- 📊 View and explore electricity and natural gas consumption data in the U.S.
- 💰 Track and compare retail energy prices across states and years.
- 🏭 Analyze industrial and commercial energy usage patterns.
- 🌡️ Check heat content data for natural gas.
- 📅 Filter data by year for trend analysis.
- 📍 Filter by state to view top or least energy consumers.
- ✨ Save your favorite graphs for easy access anytime.
- 🔄 Dynamically add new energy data types without changing the code.
- 📈 Interactive and responsive graph visualizations.
- 💡 Get suggestions for optimizing energy consumption.

## Project Tools
- **React + Vite**: Leverages Vite's fast build system with React for efficient development.
- **ESLint Integration**: Ensures code quality and consistency throughout the project.
- **Tailwind CSS**: Utilizes Tailwind CSS for rapid and customizable UI development.

## Project Structure

```
E.C.M/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── App.jsx
│   └── main.jsx
├── .eslintrc.cjs
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.cjs
├── tailwind.config.cjs
└── vite.config.js
```

- `public/`: Contains static assets.
- `src/`: Contains the main source code for the React application.
  - `assets/`: Asset files like images or fonts.
  - `components/`: Reusable React components.
  - `App.jsx`: The root React component.
  - `main.jsx`: The entry point for the React application.
- `.eslintrc.cjs`: Configuration file for ESLint.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `index.html`: The main HTML file.
- `package-lock.json` & `package.json`: Manage project dependencies.
- `postcss.config.cjs`: Configuration for PostCSS.
- `tailwind.config.cjs`: Configuration for Tailwind CSS.
- `vite.config.js`: Configuration for Vite.

## Getting Started

To set up the project locally:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/mayarsaleh4/E.C.M.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd E.C.M
   ```

3. **Install dependencies**:

   ```bash
   npm install
   ```

4. **Start the development server**:

   ```bash
   npm run dev
   ```

   The application will be running at `http://localhost:3000`.
