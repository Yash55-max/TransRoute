# TransRoute - AI-Powered Transport & Travel Information Platform

TransRoute is an intelligent travel assistant platform designed for India, combining Google Maps-like navigation with hotel integration, real-time road and weather updates, and personalized cost estimation for any vehicle type.

## Features

### 1. Mapping and Navigation
- Interactive India-wide map using OpenStreetMap
- Real-time routing with traffic density information
- Road hazard alerts (accidents, blocked roads, potholes, construction)
- Weather conditions along routes
- Fuel stations and EV charging points

### 2. Hotel Integration
- Nearby hotels, rest stops, and restaurants along routes
- Filtering by budget, rating, distance, amenities, and availability
- Direct booking options
- AI-powered recommendations based on trip duration and preferences

### 3. Fuel Cost Estimation
- Vehicle type, fuel type, and mileage input
- Current fuel prices by location
- Trip cost estimation
- Petrol vs diesel vs EV cost comparison

### 4. Real-time Alerts
- Weather warnings (storms, fog, heatwaves, rainfall)
- Traffic and hazard notifications
- Emergency alerts (floods, landslides, natural hazards)
- Push notification system

### 5. User Interaction & Personalization
- Voice-enabled assistant
- Account dashboard for saved routes and preferences
- Dark/light mode toggle
- Responsive design for mobile users

## Technology Stack

- **Frontend**: React.js with Vite
- **Mapping**: Leaflet.js with OpenStreetMap
- **UI Framework**: Material-UI (MUI)
- **State Management**: React Context API
- **Routing**: React Router
- **Voice Recognition**: Web Speech API

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/transroute.git
   ```

2. Navigate to the project directory:
   ```bash
   cd transroute
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and visit `http://localhost:5173`

## Project Structure

```
src/
├── components/
│   ├── Dashboard.jsx
│   ├── MapView.jsx
│   ├── HotelSearch.jsx
│   ├── CostEstimator.jsx
│   ├── AlertsPanel.jsx
│   ├── VoiceAssistant.jsx
│   └── UserProfile.jsx
├── App.jsx
├── App.css
└── main.jsx
```

## Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Builds the production-ready app
- `npm run preview` - Previews the production build locally

## Future Enhancements

- Backend API integration for real-time data
- Mobile app development with React Native
- Machine learning for personalized recommendations
- Social features for sharing travel experiences
- Multi-language support

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenStreetMap for map data
- Leaflet.js for mapping functionality
- Material-UI for UI components