# Ridex - Your Safe Ride

Ridex is a ride-hailing platform with real-time tracking, user and captain authentication, and a modern frontend built with React and Vite.

## Project Structure

```
Ridex/
  Backend/      # Node.js Express backend
  frontend/     # React + Vite frontend
```

## Backend

- Node.js, Express, Socket.io
- REST APIs for user, captain, ride management
- JWT authentication
- MongoDB database

### Run Backend

```bash
cd Backend
npm install
node server.js
```

## Frontend

- React, Vite, Tailwind CSS
- Live ride tracking
- User and captain dashboards

### Run Frontend

```bash
cd frontend
npm install
npm run dev
```

## Features

- User and Captain registration/login
- Book and track rides in real-time
- Captain dashboard for ride management
- Secure authentication and token blacklist

## Contributing

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/foo`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request



## GitHub Workflow

### Clone the Repository

```bash
git clone https://github.com/ashhhiii/Ridex-Your-safe-Ride.git
cd Ridex-Your-safe-Ride
```

### Commit and Push Changes

```bash
git add .
git commit -m "Your commit message here"
git push origin main
```

### Create a New Branch (for features or fixes)

```bash
git checkout -b feature/your-feature-name
```

### Open a Pull Request

1. Push your branch to GitHub:
   ```bash
   git push origin feature/your-feature-name
   ```
2. Go to the repository on GitHub and click "Compare & pull request".
3. Fill in the details and submit your pull request.

--

## More Details

- **Live Tracking:**
  - Real-time location updates for rides using Socket.io.
  - Map integration for user and captain tracking.

- **Authentication:**
  - Secure login/signup for users and captains.
  - JWT-based authentication and token blacklisting for enhanced security.

- **Ride Management:**
  - Users can book, confirm, and track rides.
  - Captains can accept, manage, and finish rides.

- **Frontend Experience:**
  - Responsive UI with Tailwind CSS.
  - Pop-ups and panels for ride confirmation, tracking, and status updates.

- **Backend APIs:**
  - Modular controllers and services for scalability.
  - Middleware for authentication and request validation.
