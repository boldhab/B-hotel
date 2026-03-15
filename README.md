# B-Hotel Management System

## Project Update Overview

This update introduces significant improvements to the **B-Hotel Management System**, including backend enhancements and a complete frontend modification to improve usability, performance, and maintainability.

The goal of this update is to modernize the system interface, streamline workflows, and improve system stability for hotel staff and administrators.

---

## Key Updates

### 1. Backend Improvements

* Updated API endpoints for better data handling and validation.
* Improved database queries to optimize performance.
* Refactored service logic for maintainability and scalability.
* Added additional error handling and logging.
* Improved authentication and authorization middleware.

### 2. Frontend Modifications

The frontend has been redesigned and updated across all modules to provide a more consistent and user-friendly experience.

Main improvements include:

* Updated UI components and layout
* Improved navigation structure
* Better responsiveness for different screen sizes
* Refactored component structure for easier maintenance
* Updated styling and design consistency

### 3. Updated Modules

The following modules received frontend updates and improvements:

* Dashboard
* Room Management
* Reservations / Bookings
* Guest Management
* Billing & Payments
* Reports and Analytics
* User Management

Each module now uses a cleaner component structure and improved data handling.

---

## Frontend Structure (Updated)

```
client/src
│
├── assets
├── components
├── layouts
├── pages
│   ├── dashboard
│   ├── rooms
│   ├── reservations
│   ├── guests
│   ├── billing
│   └── reports
│
├── services
├── hooks
├── utils
└── styles
```

---

## Backend Structure

```
server/src
│
├── config
├── modules
│   ├── auth
│   ├── rooms
│   ├── reservations
│   ├── guests
│   └── billing
│
├── middleware
├── routes
├── utils
└── app.js
```

---

## Installation

### 1. Clone the Repository

```
git clone https://github.com/your-repository/b-hotel-system.git
```

### 2. Install Dependencies

Backend:

```
cd server
npm install
```

Frontend:

```
cd client
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the backend directory and configure:

```
PORT=5000
DATABASE_URL=your_database_connection
JWT_SECRET=your_secret_key
```

### 4. Run the Application

Start Backend:

```
npm run dev
```

Start Frontend:

```
npm start
```

---

## Technologies Used

### Frontend

* React / Next.js
* CSS / Tailwind / Bootstrap
* Axios for API communication

### Backend

* Node.js
* Express.js
* REST API architecture

### Database

* PostgreSQL / MySQL

---

## Future Improvements

Planned enhancements include:

* Online booking integration
* Notification system
* Advanced analytics dashboard
* Role-based access improvements
* Mobile-friendly UI improvements

---

## Contributors

* Development Team – B-Hotel System
* Frontend Refactoring and UI Updates
* Backend Optimization and API Improvements

---

## License

This project is licensed under the MIT License.
