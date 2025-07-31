# Wanderlust

Wanderlust is a full-stack accommodation booking platform inspired by Airbnb. The platform allows users to discover, book, and list accommodations around the world, providing a seamless, secure, and user-friendly experience.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## About

Wanderlust is built for travelers and hosts alike, offering a modern solution for accommodation discovery and management. The platform is designed with a responsive and dynamic interface, robust authentication, and scalable deployment.

## Features

- **Accommodation Listings:** Browse, search, and filter accommodation options.
- **Secure Booking:** Book stays with secure user authentication and authorization.
- **Host Dashboard:** List new properties, manage bookings, and view analytics.
- **Responsive Design:** Works seamlessly across devices for travelers and hosts.
- **Authentication:** Secure login and registration powered by Passport.js.
- **User Reviews and Ratings:** Leave feedback and ratings for stays.
- **Deployed on Render:** Ensuring high availability and scalability.

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Frontend:** HTML, CSS, JavaScript, EJS (Embedded JavaScript Templates)
- **Authentication:** Passport.js
- **Deployment:** Render

## Getting Started

### Prerequisites

- Node.js
- npm
- MongoDB instance (local or cloud)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/wanderlust.git
   cd wanderlust
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set environment variables:**
   - Create a `.env` file in the root directory and add:
     ```
     MONGODB_URI=your_mongodb_connection_string
     SESSION_SECRET=your_session_secret
     ```

4. **Start the server:**
   ```bash
   npm start
   ```
   The app should now be running at `http://localhost:3000`

## Usage

- **Sign Up / Login:** Create an account or log in to access booking and hosting features.
- **Browse Listings:** Search for places to stay by city, price, and other filters.
- **Book Accommodation:** Select dates and book your stay securely.
- **Become a Host:** List your property for travelers and manage your bookings.
- **Leave Reviews:** Share your experiences with the community.

## Deployment

Wanderlust is deployed on [Render](https://render.com/), providing scalability and a seamless user experience. To deploy your own version:
- Push your code to a public GitHub repository.
- Connect your repository to Render and set the environment variables as above.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for improvements or bug fixes.

## License

**Maintained by:**  
Naseeramaan
