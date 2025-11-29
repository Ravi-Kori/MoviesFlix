# 🎬 Movies Flix — React Native App

Movies Flix is a modern mobile application built with **React Native** that lets users explore the latest movies, view detailed information, and discover trending titles.  
The app integrates with **TMDB (The Movie Database)** and uses **Appwrite (BaaS)** to store search history, user data, and saved movies.

---

## 🚀 Features

### 🔍 Search Movies
- Search any movie using TMDB API  
- View title, poster, description, and rating

### 📈 Trending Page
- Trending movies update based on **number of searches**
- Appwrite stores all search queries to rank movies in real time

### 📝 Movie Details
- Overview / description  
- Rating  
- Poster  
- Release date  

### 💾 Saved Movies
- Save movies for later viewing  
- Synced via Appwrite database

### 👤 Profile Page
- Manage user profile  
- Appwrite authentication support

---

## 🏠 App Screens
1. **Home Page** – Trending & latest movies  
2. **Search Page** – Search any movie  
3. **Saved Movies Page** – Your bookmarked list  
4. **Profile Page** – Account details

---

## 🛠 Tech Stack

### Frontend
- React Native  
- React Navigation  
- Axios  

### Backend (BaaS)
- **Appwrite**  
  - Authentication  
  - Database  
  - Saved movies  
  - Search tracking  

### APIs
- **TMDB API** for all movie data

---

## 📦 Installation & Setup

### 1️⃣ Clone repo
```bash
git clone https://github.com/your-username/movies-flix.git
cd movies-flix
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Add environment variables  
Create a `.env` file:

```
TMDB_API_KEY=your_tmdb_key
APPWRITE_ENDPOINT=your_appwrite_endpoint
APPWRITE_PROJECT_ID=your_project_id
```

### 4️⃣ Start app
```bash
npm start
```

Run on Android:
```bash
npm run android
```

Run on iOS:
```bash
npm run ios
```

---

## 📁 Folder Structure
```
movies-flix/
│── src/
│   ├── components/
│   ├── screens/
│   ├── navigation/
│   ├── services/
│   ├── hooks/
│   └── utils/
│── assets/
│── .env
│── package.json
│── README.md
```

---

## 🧪 Future Enhancements
- Dark mode  
- Notifications for new releases  
- Movie trailers inside app  
- Better recommendations  
- UI animations  

---

## 🤝 Contributing
Contributions are welcome!  
Open an issue before submitting major changes.

---

## 📜 License
Licensed under the **MIT License**.
