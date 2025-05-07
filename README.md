# ExpenseEase

ExpenseEase is a modern expense tracking application that helps users manage their finances efficiently. Built with a React frontend and Node.js backend, it provides real-time expense tracking and management capabilities.

## Features

- Real-time expense tracking
- User authentication and authorization
- Interactive dashboard
- Expense categorization
- Real-time updates using Socket.IO
- Responsive design

## Tech Stack

### Frontend
- React.js
- Socket.IO Client
- React Testing Library
- Web Vitals

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Socket.IO
- CORS
- dotenv for environment variables

## Project Structure

```
ExpenseEase/
├── frontend/           # React frontend application
│   ├── public/        # Static files
│   ├── src/          # Source files
│   └── package.json  # Frontend dependencies
│
└── Backend/          # Node.js backend application
    ├── controllers/  # Route controllers
    ├── models/      # Database models
    ├── utils/       # Utility functions
    └── package.json # Backend dependencies
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ExpenseEase.git
cd ExpenseEase
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd ../Backend
npm install
```

4. Create a `.env` file in the Backend directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

### Running the Application

1. Start the backend server:
```bash
cd Backend
npm run dev
```

2. Start the frontend development server:
```bash
cd frontend
npm start
```

The application will be available at `http://localhost:3000`

## Development

- Frontend runs on port 3000
- Backend runs on port 5000
- MongoDB connection is required for the backend to function

## Testing

To run frontend tests:
```bash
cd frontend
npm test
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

## Acknowledgments

- React.js community
- Node.js community
- MongoDB community 