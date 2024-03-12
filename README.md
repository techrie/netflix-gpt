## Features
  - Login/Sign Up
      - Sign In /Sign up Form  
      - redirect to Browse Page
  - Browse (after authentication)
      - Header
      - Main Movie
          - Trailer in Background
          -  Title & Description
          -  MovieSuggestions
              - MovieLists * N
  - NetflixGPT
      - Search Bar
      - Movie Suggestions  

## 👨🏻‍💻Tech choices
  - ReactJS (scaffolded with CRA)
  - TailwindCSS
  - Single responsibility via Custom hooks
  - State management using React-Redux
  - Firebase for authentication backend
  - Routing using React-router-dom



## 💡Development sequence
  - Create React App
  - Configured TailwindCSS 
  - Header
  - Routing of App
  - Login Form
  - Sign up Form
  - Form Validation
  - useRef Hook
  - Firebase Setup
  - Deploying our app to production
  - Create SignUp User Account
  - Implement Sign In user Api
  - Created Redux Store with userSlice
  - Implemented Sign out 
  - Update Profile
  - BugFix: Sign up user displayName and profile picture update
  - BugFix: if the user is not logged in Redirect /browse to Login Page and vice-versa
  - Unsubscribed to the onAuthStateChanged callback
  - Add hardcoded values to the constants file
  - Register TMDB API & create an app & get access token
  - Get Data from TMDB now playing movies list API
  - Custom Hook for Now Playing Movies
  - Create movieSlice
  - Update Store with movies Data
  - Planning for MainContainer & secondary container
  - Fetch Data for Trailer Video
  - Update Store with Trailer Video Data
  - Embedded the Youtube video and make it autoplay and mute
  - Tailwind Classes to make Main Container look awesome
  - Build Secondary Component
  - Build Movie List
  - build Movie Card
  - TMDB Image CDN URL
  - Made the Browse page amazing with Tailwind CSS
  - usePopularMovies Custom hook
  - GPT Search Page
  - GPT Search Bar
  - Multi-language Feature
  - Get Open AI Api Key 
  - Gpt Search API Call
  - fetched gptMoviesSuggestions from TMDB
  - created gptSlice added data
  - Reused Movie List component to make movie suggestion container
  - Memoization
  - Added .env file
  - Adding .env file to gitignore
  - Made our Site Responsive



# Project Setup
    - Before starting the project please add .env file and add TMDB and OPENAI KEY into it.