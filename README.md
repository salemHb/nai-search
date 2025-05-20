Nai-Search: House Hunting Application for Nairobi
Nai-Search is a web application designed to simplify the process of searching, renting, and buying apartments in Nairobi, Kenya. It provides a user-friendly interface for tenants and buyers to browse properties and an admin dashboard for landlords, caretakers, or property managers to manage listings and interact with users. Built with React, Vite, and Tailwind CSS, it offers a responsive and modern experience.
Features

Property Search: Users can search for apartments by location, price, size, or other criteria in Nairobi.
Rent or Buy Options: Supports both rental and purchase inquiries for apartments.
Responsive Navbar: Includes a navigation bar with links to Home, Products, Contact, and About, with a mobile-friendly menu.
Admin Dashboard: Allows landlords/caretakers to:
Manage property listings (add, edit, delete).
View inquiries from potential tenants or buyers.
Handle bookings or applications.

Modern UI: Built with Tailwind CSS for a sleek, responsive design.
Scalable Architecture: Frontend powered by React and Vite for fast development and performance.

Tech Stack

Frontend: React, Vite, Tailwind CSS
Backend: [Specify if you’re using Node.js, Express, Laravel, etc., or leave as TBD]
Database: [Specify if you’re using MongoDB, MySQL, Firebase, etc., or leave as TBD]
Other Tools: Git, GitHub

Getting Started
Prerequisites

Node.js (v14.18+ or higher)
npm (v6+ or higher)
Git

Installation

Clone the repository:git clone https://github.com/your-username/nai-search.git
cd nai-search

Install dependencies:npm install

Start the development server:npm run dev

Open http://localhost:5173 in your browser to view the app.

Configuration

Tailwind CSS: Ensure tailwind.config.js includes the correct content paths:module.exports = {
content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
theme: { extend: {} },
plugins: [],
};

Vite: Verify vite.config.js is set up with React and Tailwind plugins:import { defineConfig } from "vite";
import react from "@vitejs/plugin-react";
import tailwindcss from "@tailwindcss/vite";

export default defineConfig({
plugins: [react(), tailwindcss()],
});

Usage

For Users:
Navigate to the homepage to search for apartments in Nairobi.
Use filters (e.g., price, location) to find properties.
Contact landlords via the app for renting or buying inquiries.

For Admins/Landlords:
Access the admin dashboard to manage property listings.
View and respond to tenant/buyer inquiries.
Update property details or availability.

Project Structure
nai-search/
├── public/ # Static assets (e.g., images)
├── src/ # React components and styles
│ ├── components/ # Reusable components (e.g., Navbar.jsx)
│ ├── index.css # Tailwind CSS styles
│ ├── main.jsx # Entry point
│ └── App.jsx # Main app component
├── index.html # HTML template
├── package.json # Dependencies and scripts
├── vite.config.js # Vite configuration
├── tailwind.config.js # Tailwind CSS configuration
└── README.md # Project documentation

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request.

License
MIT License
Contact
For inquiries, reach out via [husseinsalim419@gmail.com] or open an issue on GitHub.
