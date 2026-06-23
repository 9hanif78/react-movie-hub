🎬 React Movie Hub

A modern, fast, and responsive movie discovery web application built with React + Vite that allows users to explore trending movies, search any film in real time, and manage their favorite movies using a clean and intuitive UI powered by TMDB API.

This project is designed with a focus on performance, scalability, reusable components, and real-world frontend architecture patterns.

🚀 Live Features
🔍 Smart Movie Search System
Real-time movie search by title
Instant filtering with optimized rendering
Case-insensitive search experience
🎥 Movie Discovery Dashboard
Trending & popular movies from TMDB API
Clean and modern movie grid layout
High-quality movie posters with responsive UI
📄 Detailed Movie Experience
Movie poster display
Release year extraction
Rating-ready structure (expandable)
Clean overview-ready architecture
❤️ Favorites System
Add / remove favorite movies
Persistent storage using LocalStorage
Dedicated favorites page
📱 Responsive UI/UX
Mobile-first design approach
Tablet and desktop optimized layout
Smooth hover interactions and modern spacing
⚡ Performance Optimized
Built with Vite for lightning-fast dev & build speed
Component-based architecture for scalability
Efficient state management using React Context API
🛠️ Tech Stack
⚛️ Frontend
React.js (Functional Components + Hooks)
React Router DOM
⚡ Build Tool
Vite (Ultra-fast development environment)
🎨 Styling
Vanilla CSS (modular structure)
Modern UI patterns (glassmorphism, gradients, grid systems)
🌐 API Integration
TMDB API (The Movie Database)
📡 TMDB API Integration

This project uses The Movie Database (TMDB) API to fetch real-time movie data including trending, popular, and searched movies.

👉 Official API Docs:
https://www.themoviedb.org/documentation/api

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/react-movie-hub.git
2️⃣ Navigate to project
cd react-movie-hub
3️⃣ Install dependencies
npm install
4️⃣ Setup environment variables

Create a .env file in root:

VITE_TMDB_API_KEY=your_api_key_here
5️⃣ Run development server
npm run dev
🌍 Open in browser
http://localhost:5173
📁 Project Architecture
src/
├── components/       # Reusable UI components (MovieCard, Navbar)
├── pages/            # Application pages (Home, Favorites)
├── contexts/         # Global state management (Favorites system)
├── services/         # API handling (TMDB requests)
├── css/              # Modular styling files
├── App.jsx           # Main app routing structure
└── main.jsx          # App entry point
🧠 Key Engineering Highlights

✔ Clean component-based architecture
✔ Scalable React Context state management
✔ Reusable UI components
✔ Separation of concerns (UI / Logic / API layers)
✔ Optimized API handling with async/await
✔ Persistent user data using LocalStorage
✔ Responsive grid-based UI system

🎯 Future Improvements (Roadmap)
🌙 Dark / Light mode toggle
🎬 Movie trailer integration (YouTube API)
🎭 Genre-based filtering system
🔐 User authentication system
🤖 AI-based movie recommendations
⭐ Advanced rating & review system
⚡ Pagination & infinite scroll optimization
💼 Why This Project Matters

This project demonstrates:

Real-world React development skills
API integration experience (TMDB)
State management using Context API
UI/UX design thinking
Responsive frontend engineering
Clean GitHub project structuring
🤝 License

This project is open-source and available under the MIT License.
