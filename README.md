# Pharmaceutic

A modern pharmacy appointment booking system built with React. Enables customers to book consultations with pharmacists and allows administrators to manage appointments and availability slots.

## Features

### For Customers
- 📅 **Book Appointments** - Select from available pharmacist consultation slots
- 💬 **Describe Concerns** - Explain symptoms and health questions in detail
- 📋 **Track Appointments** - View booking history and appointment status
- 🔒 **Secure Verification** - Phone number verification via OTP during registration

### For Administrators
- ⚕️ **Manage Appointments** - Confirm, cancel, or add notes to patient appointments
- 🕐 **Manage Slots** - Add and remove available consultation time slots
- 👥 **View Patients** - Access registered patient information and appointment history
- 📊 **Dashboard Stats** - Monitor total appointments, pending bookings, and registered patients

## Demo Credentials

**Admin Account:**
- Phone: `+265999000001`
- Password: `admin123`

## Tech Stack

- **React** - UI framework
- **JavaScript (ES6+)** - Language
- **CSS-in-JS** - Inline styling with custom color scheme

## Color Scheme

- Primary: `#0F6E56` (Dark Green)
- Primary Light: `#1D9E75` (Light Green)
- Accent: `#5DCAA5` (Mint)
- Danger: `#E24B4A` (Red)
- Warning: `#EF9F27` (Orange)

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the development server: `npm start`
4. Open your browser to `http://localhost:3000`

## Application Flow

### Customer Journey
1. Land on the homepage
2. Register with phone number (receives OTP verification)
3. Log in with phone and password
4. Book appointments by selecting available slots and describing concerns
5. View appointment status and pharmacist notes

### Admin Journey
1. Log in with admin credentials
2. Access dashboard to manage appointments
3. Confirm/cancel bookings and add clinical notes
4. Add new appointment slots as needed
5. Monitor registered patients and appointment statistics

## Project Structure

- `App` - Main application component with routing
- `Landing` - Homepage with service overview
- `Register` - Customer registration with phone verification
- `Login` - Authentication for both customers and admins
- `CustomerDashboard` - Customer appointment booking and tracking
- `AdminDashboard` - Admin appointment and slot management

## License

© 2026 Good Hope Pharmacy · Blantyre, Malawi
