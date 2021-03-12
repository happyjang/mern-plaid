# mern-plaid
A full-stack banking web app built with the MERN stack and Plaid's API that allows users to easily authenticate and link their bank account. The users can see their statements and add/remove their bank accounts in a secure manner. While building this web app, I leveraged React.JS, Redux.js, Node.JS, MongoDB, and RESTful methods to develop frontend design, client-side validations, proximity lookups, and the API framework. Addressed authentication and security concerns with Passport and JWTs. I performed 100% coverage with unit and integration testing

This project uses the following technologies:
- React and React Router for the frontend
- Express and Node for the backend
- MongoDB for the database
- Redux for global state management
- Plaid for bank account linkage and transaction data
- Passport and JWTs for authentication

This app will allow users to
- Register
- Log in
- Access protected pages only accessible to logged in users
- Stay logged in when they close the app or refresh the page
- Log out
- Link multiple bank accounts
- Remove bank accounts
- View transactions from all linked accounts in a searchable and filterable data table
