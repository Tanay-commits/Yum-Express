# 🍽️ Yum Express

A modern and responsive web-based food ordering platform designed for canteens. This project enables users to browse a menu, add items to their cart, log in, and place orders efficiently. Built with React and styled for a clean user experience.

-- Demo Link: https://yum-express-tan.vercel.app/

---

## 🚀 Features

- 🧾 Browse & explore a dynamic menu
- 🛒 Add/remove items to/from a cart
- 📲 Responsive design with app download prompts
- 🔐 Login functionality
- 💳 Integrated order placement and mock payment form
- 🌐 Social media and app store links in the footer
- 🧠 Global state management via React Context API

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite
- **Styling**: CSS Modules
- **Package Management**: npm
- **Linting**: ESLint
- **Assets**: PNG, JPEG, SVG icons and food images

---

## 📁 Project Structure

Yum Express
├─ Frontend
│ ├─ public / index.html # Entry HTML file
│ ├─ package.json # Dependencies and scripts
│ ├─ vite.config.js # Vite configuration
│ ├─ .eslintrc.cjs # Linting config
│ └─ src
│ ├─ App.jsx # Root React component
│ ├─ index.css / App.css # Global and component styles
│ ├─ main.jsx # App entry point
│ ├─ assets/ # Static images & icons
│ ├─ Context/StoreContext # Global state management
│ ├─ Components/ # Reusable UI components
│ └─ Pages/ # Main page-level components


## 📸 UI Components

| Component      | Description                          |
|----------------|--------------------------------------|
| `Navbar`       | Top navigation bar with logo & links |
| `Header`       | Landing section banner               |
| `ExploreMenu`  | Category-based food filtering        |
| `FoodDisplay`  | List of food items per category      |
| `FoodItem`     | Individual food item cards           |
| `Cart`         | Shopping cart page                   |
| `Login`        | Basic login form                     |
| `PlaceOrder`   | Final order placement flow           |
| `Footer`       | Links to social & app stores         |

---

## 🔧 Getting Started

### 1. Clone the repository

git clone https://github.com/Tanay-commits/Yum-Express.git
cd Yum Express/Frontend

2. Install dependencies
npm install

3. Start development server
npm run dev
Open http://localhost:5173 to view in browser.

📷 Assets
Located under src/assets/, this folder includes:

Food item images

Icons (add/remove, search, login, social)

App Store & Play Store badges

Logo & branding assets

🧪 Linting
Run ESLint to check for code issues:
npx eslint .

✨ Future Improvements
Backend integration (orders, users, payments)

Enhanced authentication

Real-time order tracking

Admin panel for canteen staff

Unit testing with Jest or Vitest

