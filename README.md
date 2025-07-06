# ALX Listing App

A modern, responsive property listing platform inspired by Airbnb. This app is designed as part of the ALX curriculum to demonstrate practical skills in building scalable frontend applications using **Next.js**, **TypeScript**, and **Tailwind CSS**.

## 🚀 Project Goals

- Build a reusable, component-based property listing UI  
- Use modern web development tools and best practices  
- Organize code in a scalable and maintainable way  
- Prepare for integration with APIs or a backend service  

## 📁 Project Structure

alx-listing-app/
│
├── components/
│   └── common/
│       ├── Card.tsx       # Reusable Card component for listing properties
│       └── Button.tsx     # Reusable Button component (e.g., “Book Now”, “Details”)
│
├── interfaces/
│   └── index.ts           # TypeScript interfaces (e.g., CardProps, ButtonProps)
│
├── constants/
│   └── index.ts           # Constants such as API URLs or UI text
│
├── public/
│   └── assets/            # All project images and SVGs (e.g., placeholder images)
│
├── pages/                 # Next.js pages
│
├── styles/                # Tailwind and global styles
│
├── README.md              # Project documentation (this file)
│
├── package.json           # Project dependencies and scripts
│
└── tsconfig.json          # TypeScript configuration

## 🖼️ Assets

All images and SVGs used throughout the project are stored in:

public/assets/

Organize them as needed:
- placeholders/ – Sample property images
- icons/ – SVG icons for UI
- logos/ – Project or brand logos

## 💡 Component Descriptions

components/common/Card.tsx  
Reusable component for displaying property listings such as images, price, title, and description.

components/common/Button.tsx  
Generic, reusable button used across the app for actions like “Book Now” or “Details”.

## 🧩 TypeScript Interfaces

interfaces/index.ts  
Defines and exports all TypeScript interfaces used in the project.

Example:
export interface CardProps {
  id: string;
  title: string;
  imageUrl: string;
  price: number;
}

export interface ButtonProps {
  text: string;
  onClick: () => void;
  variant?: 'primary' | 'secondary';
}

## ⚙️ Constants

constants/index.ts  
Holds global constants such as API URLs or shared UI text.

Example:
export const API_BASE_URL = "https://api.example.com";
export const PLACEHOLDER_IMAGE = "/assets/placeholders/property.jpg";

## 🛠️ How to Run the Project Locally

1. Clone the Repository

git clone https://github.com/devhan-abdu/alx-listing-app.git  
cd alx-listing-app

2. Install Dependencies

Make sure you have Node.js v18+ installed.

npm install

3. Start the Development Server

npm run dev

4. Open in Browser

Visit: http://localhost:3000

## 🧪 Verify Setup

After starting the dev server, ensure:
- The app compiles with no errors
- The UI loads successfully in the browser
- Components render as expected

## 📚 Technologies Used

- Next.js
- TypeScript
- Tailwind CSS
- Lucide Icons
- Radix UI (planned)
- React

## 📬 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to improve or add.

## 📄 License

This project is developed for educational use as part of the ALX Software Engineering Program.
