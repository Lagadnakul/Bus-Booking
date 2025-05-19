# 🚌 Bus Booking System

![Angular](https://img.shields.io/badge/Angular-18.0.0-dd0031?style=flat-square&logo=angular)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-7952b3?style=flat-square&logo=bootstrap)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

A modern bus booking application built with Angular 18 that allows users to search for bus routes, view available seats, and book tickets online.

![Bus Booking Demo](https://via.placeholder.com/800x400?text=Bus+Booking+App+Demo)

## ✨ Features

- 🔍 Search for bus routes by source and destination
- 📅 Select travel dates with an intuitive calendar interface
- 🚌 View available buses with details like timing, price, and ratings
- 💺 Select seats with interactive seat layout
- 💳 Secure payment integration
- 📱 Fully responsive design for mobile and desktop

## 🚀 Getting Started

### Prerequisites

- Node.js (v16.x or higher)
- npm (v8.x or higher)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Lagadnakul/Bus-Booking.git
cd Bus-Booking
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

4. Open your browser and navigate to `http://localhost:4200`

## 🛠️ Tech Stack

- **Framework**: Angular 18
- **UI Library**: Bootstrap 5.3.3
- **Icons**: Font Awesome 4.7.0
- **State Management**: RxJS
- **Testing**: Jasmine & Karma

## 📝 Project Structure

```
src/
  ├── app/
  │   ├── pages/
  │   │   ├── search/         # Search page with filters
  │   │   └── booking/        # Seat selection and booking flow
  │   ├── services/           # API and data services 
  │   └── shared/             # Shared components, models and utilities
  └── assets/                 # Static assets
```

## 🧪 Running Tests

```bash
# Unit tests
npm test

# End-to-end tests
npm run e2e
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
