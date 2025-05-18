# Vepo Marketing Agency Website

A modern, full-stack marketing agency website built with Next.js, Node.js, and MongoDB.

## Features

- 🎨 Modern, responsive design with dark mode support
- 📱 Mobile-first approach
- 📝 Blog system with rich text editor
- 🔒 Secure admin authentication
- 📊 Admin dashboard for content management
- 🗺️ Contact page with Google Maps integration
- 📧 Contact form with email integration
- 🔍 SEO optimized

## Tech Stack

### Frontend
- Next.js 14
- React 18
- Tailwind CSS
- Framer Motion
- TypeScript

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Multer (file uploads)

## Prerequisites

- Node.js 18.x or higher
- MongoDB
- npm or yarn

## Getting Started

1. Clone the repository:
```bash
git clone [repository-url]
cd vepo-marketing
```

2. Install dependencies:
```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

3. Set up environment variables:
```bash
# In the client directory
cp .env.example .env.local

# In the server directory
cp .env.example .env
```

4. Start the development servers:
```bash
# Start backend server (from server directory)
npm run dev

# Start frontend server (from client directory)
npm run dev
```

The frontend will be available at `http://localhost:3000`
The backend API will be available at `http://localhost:5000`

## Project Structure

```
vepo-marketing/
├── client/                 # Frontend Next.js application
│   ├── components/        # Reusable React components
│   ├── pages/            # Next.js pages
│   ├── public/           # Static assets
│   ├── styles/           # Global styles
│   └── utils/            # Utility functions
│
├── server/                # Backend Node.js application
│   ├── controllers/      # Route controllers
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   ├── middleware/      # Custom middleware
│   └── utils/           # Utility functions
│
└── uploads/              # Uploaded files (if using local storage)
```

## Environment Variables

### Frontend (.env.local)
```
NEXT_PUBLIC_API_URL=http://localhost:5000
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

### Backend (.env)
```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
SMTP_HOST=your_smtp_host
SMTP_PORT=your_smtp_port
SMTP_USER=your_smtp_user
SMTP_PASS=your_smtp_password
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 