# E.C.M

## Overview

E.C.M is a Energy Consumption Monitor website that is built using React and Vite, providing a minimal setup and a lot of features to users.

## Features
1.📊 View Energy Consumption Data
  Explore U.S. data on electricity and natural gas usage.
2.💰 Track Retail Prices
  See how much electricity and gas cost over time in different states.
3.🏭 Analyze Industry & Commercial Use
  Understand how energy is used in industries vs. commercial sectors.
4.🌡️ Check Heat Content of Natural Gas
  View energy content (in BTUs) of natural gas over time.
5.📅 Filter Data by Year
  Choose specific years or ranges to compare energy trends.
6.📍 Filter by State
  See which states are top or lowest consumers.
7.✨ Save Favorite Graphs
  Mark certain graphs as favorites and revisit them anytime.
8.🔍 Add & View Different Energy Types (Dynamic)
  The system is built to dynamically handle new energy types by just adding the API and new page.
9.📈 Interactive Graphs
  Hover and interact with visual charts to get detailed info.
10.📥 Import Data & Edit Variables (Planned / Functional)
  Import datasets, and possibly tweak variables for deeper analysis (depending on current stage of development).
11.💡 Get Optimization Tips
  The site suggests strategies for energy efficiency based on usage patterns.

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
