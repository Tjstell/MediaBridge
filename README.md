**MediaBridge**
A cross-domain recommendation system that connects movies and books through shared user preferences.
**Live App**
mediabridge-recs.web.app
**About**
MediaBridge is a graduate capstone project built to explore cross-domain recommendation systems. The current version is in active data collection — users rate movies and books on a 1-10 scale, and that data will be used to train a two-tower shared embedding model that can recommend movies based on your favorite books and vice versa.
**Tech Stack**

Frontend: HTML, CSS, JavaScript
Authentication: Firebase Auth (Google and Email)
Database: Firebase Firestore
Movie data: TMDB API
Book data: Google Books API
Hosting: Firebase Hosting

**Project Status**

Phase 1 (current): Data collection via rating survey
Phase 2 (in progress): Two-tower shared embedding model
Phase 3 (planned): Live recommendations interface

**Running Locally**

1. Clone the repository
2. Create a config.js file in the root folder with the following structure:

```javascript
const CONFIG = {
  TMDB_KEY: "your-tmdb-api-key",
  BOOKS_KEY: "your-google-books-api-key",
  firebaseConfig: {
    apiKey: "your-key",
    authDomain: "your-domain",
    projectId: "your-project-id",
    storageBucket: "your-bucket",
    messagingSenderId: "your-sender-id",
    appId: "your-app-id",
    measurementId: "your-measurement-id"
  }
};
```

3. Get a free TMDB API key at themoviedb.org
4. Get a free Google Books API key at console.cloud.google.com
5. Create a Firebase project at firebase.google.com and copy your config
6. Open with Live Server in VS Code

**Author**
Taylor Stell
MS Applied Data Science, Bay Path University 2026
[LinkedIn](https://www.linkedin.com/in/taylorstell/)
[GitHub](https://www.github.com/Tjstell)
