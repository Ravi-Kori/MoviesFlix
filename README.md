🎬 Movies Flix — React Native Mobile App

Movies Flix is a cross-platform React Native mobile application that allows users to explore the latest movies, discover trending titles, search for any film, and view detailed movie information. The app integrates with TMDB (The Movie Database) API to fetch high-quality movie data such as descriptions, ratings, and images.

The application is powered by Appwrite (BaaS) on the backend, which handles data storage, user authentication, and tracking user activity for generating personalized trends.

🚀 Key Features
🔥 Trending Movies (Dynamic Ranking)

The backend tracks how many times each movie is searched by users.

Movies with the highest number of searches appear at the top of the Trending Page.

Real-time updates—no manual curation needed.

🔍 Movie Search

Search any movie using the TMDB API.

Results include posters, descriptions, and ratings.

Searches are automatically logged into Appwrite to update trending analytics.

📄 Movie Details Page

View detailed information:

Short description

Ratings

Release date

Poster image

Fast and responsive using optimized API requests.

⭐ Saved Movies

Users can bookmark/save their favorite movies.

Saved films are stored securely in Appwrite for easy access later.

👤 Profile Page

Displays user information.

Connected with Appwrite authentication (email/password, OAuth, etc. if implemented).

📱 App Screens

Home Page (Trending / Latest Movies)

Search Page

Saved Movies Page

Profile Page

🛠️ Tech Stack
Frontend

React Native

React Navigation

Context API

TMDB API for movie data

Backend (BaaS)

Appwrite

Database (search log, saved movies)

Authentication

Serverless functions (optional)

🌐 How It Works

User searches for a movie → search term is saved to Appwrite.

Appwrite counts number of searches per movie.

Trending page sorts movies based on search frequency.

TMDB API provides movie details and metadata.

Users can save movies, view profiles, and revisit previously liked titles.
