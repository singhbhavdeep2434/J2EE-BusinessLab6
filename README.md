# Online Banking API

This API provides a structured interface for managing online banking operations such as user authentication, account management, and fund transfers.

## Endpoints

### User Authentication
- **POST /auth/login**: Authenticate a user and return a JWT token.
- **POST /auth/logout**: Log out the user and invalidate the JWT token.

### Account Management
- **GET /accounts/{id}**: Retrieve account details by ID.
- **PUT /accounts/{id}**: Update account information.

### Fund Transfers
- **POST /transactions/transfer**: Initiate a fund transfer.
- **GET /transactions/history**: Retrieve transaction history.