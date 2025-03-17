# Auth Website

This is a simple authentication website that allows users to sign up, sign in, view user information, and log out using a backend API.

## Features
- **User Signup**: Users can create an account.
- **User Signin**: Users can log in and receive an authentication token.
- **User Information**: Users can retrieve their information using the stored token.
- **Logout**: Users can log out, clearing their authentication token.

## Technologies Used
- **HTML, CSS, JavaScript**: Frontend UI.
- **Axios**: For making HTTP requests.
- **LocalStorage**: To store authentication tokens.

## Setup Instructions
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/auth-website.git
   cd auth-website
   ```
2. Ensure your backend server is running at `http://localhost:3000`.
3. Open `index.html` in a browser.

## API Endpoints
The frontend interacts with a backend API at `http://localhost:3000` with the following endpoints:
- `POST /signup` - Registers a new user.
- `POST /signin` - Logs in a user and returns an authentication token.
- `GET /me` - Retrieves user information (requires authentication token).

## Usage
1. **Sign up** by entering a username and password.
2. **Sign in** using the registered credentials.
3. **View user information** displayed after signing in.
4. **Log out** to clear the authentication token.

## Notes
- Ensure that the backend server supports JWT authentication.
- Modify API URLs if needed based on your backend configuration.

## License
This project is open-source under the MIT License.

---
Feel free to contribute or report issues!

