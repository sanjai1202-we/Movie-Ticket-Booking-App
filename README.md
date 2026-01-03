# CineMax - Movie Ticket Booking Application

A premium movie ticket booking web application featuring Tamil and English movies released in 2025. Users can select their city, find the nearest theaters, book seats, and complete payment.

## Features

- 🎬 **Latest 2025 Movies** - Browse Tamil and English releases only
- 📍 **Location-based Theaters** - Find theaters nearest to your selected city
- 🎟️ **Interactive Seat Selection** - Visual seat map with real-time selection
- 💳 **Multiple Payment Options** - Card, UPI, and Wallet support
- 📱 **Responsive Design** - Works on desktop and mobile
- ✨ **Premium UI** - Dark mode with glassmorphism effects

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)
- A local development server (optional but recommended)

### Running Locally

**Option 1: Using a simple HTTP server**

```bash
# Navigate to project directory
cd movie-ticket-app

# Using Python 3
python -m http.server 8080

# OR using Node.js (install serve globally first)
npx -y serve .
```

Then open `http://localhost:8080` in your browser.

**Option 2: Direct file access**

Simply open `index.html` in your browser. Note: Some features may not work due to CORS restrictions.

## Project Structure

```
movie-ticket-app/
├── index.html          # Landing page
├── login.html          # User login
├── home.html           # Movie listing with filters
├── booking.html        # Seat selection
├── payment.html        # Payment & ticket confirmation
├── styles.css          # Global styles (dark theme)
├── app.js              # Core JavaScript utilities
├── data/
│   ├── movies.json     # Movie database
│   └── theaters.json   # Theater & city data
└── README.md           # This file
```

## Usage Flow

1. **Landing Page** - Click "Get Started" or "Login"
2. **Login** - Enter any email and password (min 6 chars)
3. **Movies** - Select your city, browse movies, click to view details
4. **Theater & Showtime** - Choose a theater and showtime from the modal
5. **Seat Selection** - Pick your seats on the interactive seat map
6. **Payment** - Complete payment using Card/UPI/Wallet
7. **Confirmation** - View your digital ticket with QR code

## Demo Credentials

Any valid email format and password with 6+ characters will work (mock authentication).

Example:
- Email: `user@example.com`
- Password: `123456`

## Available Cities

Chennai, Coimbatore, Madurai, Trichy, Salem, Tirunelveli, Bangalore, Hyderabad, Mumbai, Delhi

## Technologies Used

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

## License

MIT License
