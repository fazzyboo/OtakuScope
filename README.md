# OtakuScope

## Project Overview
User-Centric Anime Tracking Platform
Comprehensive Anime Data
Review & Rating

## Features
- **User Registration & Authentication**: Secure login and registration using JWT.
- **Anime Watchlist**: Track anime (watching, completed, dropped, etc.) from AniList.
- **Anime Reviews**: Users can rate and write reviews for anime.
- **Forums**: Users can create discussions and participate in forum threads.
- **Recommendations**: Users can recommend anime to each other.
- **Genres**: Multiple genres are associated with each anime.
  
## Tech Stack
- **Frontend**: React.js
  - React Router for client-side navigation
  - Axios for API calls
- **Backend**: Express.js (Node.js)
  - RESTful API design for handling user actions (CRUD operations)
  - JWT for user authentication
- **Database**: MySQL
  - Relational database for storing user data, anime watchlists, reviews, forums, and recommendations
- **API**: AniList GraphQL API
  - Fetch anime data (titles, synopsis, ratings, genres) from AniList.
- **Version Control**: Git/GitHub for source control and collaboration.
  
## Relational Database Design
The database uses MySQL to store user profiles, anime statuses, reviews, and forum discussions. Below is a summary of the main tables:

- **Users**: Stores user information like username, email, password, and role (admin/user).
- **Anime**: Stores information fetched from AniList, such as title, synopsis, and episode count.
- **Anime Status**: Tracks the status of anime on a user's watchlist (e.g., watching, completed).
- **Reviews**: Stores user reviews for each anime.
- **Forums & Forum Posts**: Handles discussions and user posts in the forums.
- **Recommendations**: Stores anime recommendations made by users.

## ERD 
https://tinyurl.com/4c8jyyt3
