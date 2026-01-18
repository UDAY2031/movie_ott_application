# CineVault – Flutter Movie Discovery App

This repository contains **CineVault**, a Flutter-based movie discovery application developed as part of a company assessment submission.  
The application allows users to browse popular movies, search for titles, view detailed movie information, and manage favourites and a watchlist using data from the TMDB API.

---

## Submission Guidelines Compliance

- The project is shared via GitHub
- A complete README is provided with:
  - Setup instructions
  - Steps to run the assignment locally
  - Assumptions and dependencies used
- The solution is original, well-structured, and readable with appropriate comments

---

## Setup Instructions

### Prerequisites
- Flutter SDK (3.x or higher)
- Dart SDK (bundled with Flutter)
- Android Studio or VS Code with Flutter extensions
- Git
- Stable internet connection (required for API calls)

---

## Steps to Run the Assignment Locally

### Clone the Repository
```
git clone https://github.com/UDAY2031/movie_ott_application.git 
cd movie_ott_application
```
### Install Dependencies
```
flutter pub get
```
### Run the Application
```
flutter run
```
### Run on Web (Optional)
```
flutter run -d web-server
```
---

## Assumptions and Dependencies Used

### Assumptions
- Flutter environment is correctly set up on the system
- The application is run with internet access
- TMDB API services are available

### Dependencies
- Flutter framework
- Dart language
- TMDB API for fetching movie data
- Flutter Material UI components

---

## Project Structure

lib/
├── main.dart  
├── splash_screen.dart  
├── home_page.dart  
├── movies_page.dart  
├── movie_details_page.dart  
├── favourites_page.dart  
├── watchlist_page.dart  
└── movie_model.dart  

---

## Features Implemented
- Splash screen on app launch
- Browse popular movies
- Real-time movie search
- Detailed movie view
- Add/remove favourites
- Add/remove movies from watchlist
- Minimal and clean UI

---

## Code Quality and Originality
- Entire implementation is original
- Code is modular and easy to understand
- Meaningful variable and function naming
- Comments added where required
- Follows Flutter best practices

---

## Known Limitations
- API key is hardcoded for simplicity
- No authentication system
- Favourites and watchlist are not persisted

---

## License
This project is licensed under the MIT License.

---

## Acknowledgements
- TMDB API for movie data
- Flutter framework
