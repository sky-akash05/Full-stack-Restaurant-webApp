
# Full-Stack Restaurant WebApp

This is a comprehensive full-stack restaurant web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application allows users to view the restaurant menu, place orders, and manage reservations. It also includes an admin panel for restaurant staff to manage orders and update the menu.

## Features

- **User Authentication:** Secure login and registration using JWT.
- **Menu Management:** Users can view the restaurant menu with detailed descriptions and images.
- **Order Placement:** Users can place orders from the menu.
- **Reservation System:** Users can book tables for specific dates and times.
- **Admin Panel:** Admins can manage orders, update the menu, and view reservations.
- **Responsive Design:** Optimized for both desktop and mobile views.

## Technologies Used

- **Frontend:** React.js, Redux, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token)
- **Hosting:** Deployed on AWS EC2

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Node.js
- npm or yarn
- MongoDB (local or remote)

### Clone the Repository

```bash
git clone https://github.com/sky-akash05/Full-stack-Restaurant-webApp.git
cd Full-stack-Restaurant-webApp
```

### Backend Setup

1. Navigate to the backend directory:

```bash
cd backend
```

2. Install the dependencies:

```bash
npm install
```

3. Create a `.env` file in the `backend` directory and add the following environment variables:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

4. Start the backend server:

```bash
npm start
```

### Frontend Setup

1. Navigate to the frontend directory:

```bash
cd ../frontend
```

2. Install the dependencies:

```bash
npm install
```

3. Create a `.env` file in the `frontend` directory and add the following environment variables:

```env
REACT_APP_API_URL=http://localhost:5000/api
```

4. Start the frontend server:

```bash
npm start
```

### Running the Application

- The backend server will run on `http://localhost:5000`
- The frontend server will run on `http://localhost:3000`

Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage

1. Register a new user or log in with existing credentials.
2. Browse the menu and place orders.
3. Make a reservation by selecting the date and time.
4. Admins can log in to access the admin panel for managing orders and updating the menu.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.



