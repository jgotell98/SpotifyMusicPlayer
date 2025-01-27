# Spotify Music Player

A web-based music player that integrates with Spotify, utilizing Django for the backend and React.js for the frontend.

---

## Features

- **User Authentication**: Secure login and logout functionality.
- **Spotify Integration**: Stream music directly from Spotify.
- **Playlist Management**: Create, edit, and delete playlists.
- **Search Functionality**: Search for songs, artists, and albums.
- **Responsive Design**: Optimized for various device sizes.

---

## Technologies Used

- **Backend**: Django
- **Frontend**: React.js
- **Styling**: CSS
- **APIs**: Spotify Web API

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/jgotell98/SpotifyMusicPlayer.git
cd SpotifyMusicPlayer
```

### 2. Backend Setup (Django)

1. Navigate to the backend directory:
   ```bash
   cd music_controller
   ```

2. Create a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```bash
   python manage.py migrate
   ```

5. Start the Django development server:
   ```bash
   python manage.py runserver
   ```

### 3. Frontend Setup (React)

1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```

---

## Usage

1. Access the app by navigating to `http://localhost:3000` in your web browser.
2. Log in with your Spotify account to enjoy a personalized music experience.
3. Explore features such as searching for music, managing playlists, and streaming directly from Spotify.

---


### Steps to Contribute:

1. Fork this repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request to the main branch.


## Acknowledgements

- **[Spotify Web API](https://developer.spotify.com/documentation/web-api/)**: For enabling seamless music integration.
- **[Django Documentation](https://docs.djangoproject.com/)**: For excellent backend support.
- **[React.js Documentation](https://reactjs.org/docs/getting-started.html)**: For frontend framework support.
