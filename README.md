# user-API
The "user api" is a critical component of the Museum Artefact Explorer App, responsible for handling user data, authentication, and interactions related to user accounts. This API is designed to securely store and manage user information, such as registration, login, favorite artefacts, and search history.

## Deploy Link:
https://odd-gray-piglet-tutu.cyclic.app/

## Author:
Sooyeon Kim

## Tech Stack:
- **Node.js and Express**: The backend of this API is built using Node.js and the Express.js framework, providing a robust and scalable foundation for handling HTTP requests.
- **MongoDB**: MongoDB is employed as the NoSQL database to efficiently store and manage user-related data, including user profiles, favorites, and search histories.
- **JSON Web Tokens (JWTs)**: JWTs are used for user authentication and authorization. They provide secure access control to API endpoints, ensuring that only authenticated users can perform certain actions.
- **Passport.js**: Passport.js is utilized for implementing JWT-based authentication strategies, enhancing security and managing user sessions effectively.

## Endpoints:
- **/api/user/register**: Allows users to register by creating an account. Passwords are securely hashed before being stored in the database.
- **/api/user/login**: Enables users to log in and obtain a JWT token for secure API access.
- **/api/user/favourites**: Provides endpoints for retrieving and managing user-favorite artefacts.
- **/api/user/history**: Offers endpoints for accessing and managing a user's search history.

## Scalability:
The API is designed with scalability in mind, employing a NoSQL database structure that can accommodate a growing volume of user data as the ExploreArt App gains popularity.

## Usage:
To utilize this API, developers can integrate it into the ExploreArt App to manage user accounts and interactions. Secure authentication and data storage ensure that user information remains protected and accessible only to authorized individuals.
Museum Artefact Explorer App's "user-api" is a crucial component that enhances user experience and engagement by allowing users to curate their art exploration journey with saved favorites and personalized search histories.
