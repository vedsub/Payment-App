

## Description

This Payments App is a comprehensive solution designed to facilitate seamless financial transactions between users. It features a unique account creation process that assigns a random balance to each new account.  The app ensures a secure and efficient way of sending money, guaranteeing that transactions are either fully completed or not processed at all,so as to remove unfair methods.

### Features

- **Random Balance Assignment**: Each account is created with a random balance, providing an engaging start for users.
- **Secure Transactions**: Ensures that money transfers between users are executed completely or not at all, avoiding any partial transaction issues.
- **Profile Updates**: Users have the ability to update their profile information, ensuring their details are always current.
- **Authentication**: Utilizes JSON Web Tokens (JWT) for authentication, securing the app and user data effectively.
- **Protected Routing**: Implements protected routes to prevent unauthorized access to certain parts of the app, such as the dashboard.
- **Sign-in/Sign-out**: Streamlined sign-in process that directs users with a token in local storage to the sign-in page for enhanced security. Logging out clears the JWT token, ensuring user session termination.
- **Transaction History Tracking**: Offers users the ability to view a detailed history of their transactions, including information on whom they have sent money to and from whom they have received money. This feature enhances transparency and allows users to easily keep track of their financial activities within the app.

## How to Use

1. **Account Creation:** Start by creating an account. Upon registration, you will be assigned a random balance to begin your transactions.
2. **Send Money:** Navigate to the 'Send Money' feature to transfer funds to another user. Enter the recipient's details and the amount you wish to send.
3. **Update Profile:** Access your profile settings to update your personal information as needed.
4. **Sign In/Out:** Securely sign in to access your dashboard and perform transactions. Sign out to clear your session and JWT token.

## Security Features

- **JWT Authentication:** Ensures that all user sessions are securely managed and that data transactions are protected.
- **Protected Routes:** Guards sensitive pages from unauthorized access, ensuring that users must be signed in to view certain content.
- **Transaction Integrity:** By implementing atomic transactions, the app ensures that all financial operations are reliably processed.


## Installation

### Prerequisites

- Node.js installed on your local machine.
- MongoDB account for database management.

### Setup Instructions

**Frontend:**

1. Navigate to the frontend directory in your terminal.
2. Install the required dependencies by running:
   ```sh
   npm install
   ```
3. Start the frontend application in development mode by running:
   ```sh
   npm run dev
   ```

**Backend:**

1. Navigate to the backend directory in your terminal.
2. Install the required dependencies by running:
   ```sh
   npm install
   ```
3. Create a `.env` file in the root of the backend directory.
4. Inside the .env file, specify your MongoDB URL and the port you wish to use for the server:
```
MONGODB_URL=your_mongodb_connection_string_here
PORT=your_preferred_port
```
5. Start the backend server by running:
   ```sh
   node index.js
   ```

This will set up both the frontend and backend parts of the Payments App. Ensure both the frontend and backend servers are running to use the app fully.
Below are a few screenshots illustrating the above functionalities:
![Screenshot (131)](https://github.com/vedsub/Payment-App/assets/115373199/3da31e0c-8eec-4487-b9c8-eeb727d5cb23)

![Screenshot (132)](https://github.com/vedsub/Payment-App/assets/115373199/bf9f1955-58ea-4819-81eb-e5ed968d9083)

![Screenshot (133)](https://github.com/vedsub/Payment-App/assets/115373199/e60813b4-d8ca-48ec-8fa5-0406b99bffef)

![Screenshot (134)](https://github.com/vedsub/Payment-App/assets/115373199/c7a3b29c-aa37-441b-a8a1-b3fe61dd7bfb)

![Screenshot (136)](https://github.com/vedsub/Payment-App/assets/115373199/925ada37-c1f3-464c-8d7f-1f86caacd3ac)






