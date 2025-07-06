alx-listing-app/
│
├── components/
│ └── common/
│ ├── Card.tsx # Reusable Card component for listing properties
│ └── Button.tsx # Reusable Button component (e.g., “Book Now”, “Details”)
│
├── interfaces/
│ └── index.ts # TypeScript interfaces (e.g., CardProps, ButtonProps)
│
├── constants/
│ └── index.ts # Constants such as API URLs or UI text
│
├── public/
│ └── assets/ # All project images and SVGs (e.g., placeholder images)
│
├── pages/ # Next.js pages
│
├── styles/ # Tailwind and global styles
│
├── README.md # Project documentation (this file)
│
├── package.json # Project dependencies and scripts
│
└── tsconfig.json # TypeScript configuration


---

## 🖼️ Assets

All images and SVGs used throughout the project are located in:

public/assets/


Organize them into folders such as:
- `placeholders/`
- `icons/`
- `logos/`

---

## 💻 Running the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/devhan-abdu/alx-listing-app.git
cd alx-listing-app

2. Install Dependencies

Ensure Node.js (v18+) is installed.

npm install

3. Start the Development Server

npm run dev
