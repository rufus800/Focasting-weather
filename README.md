# Weather App

A professional weather application built with Python, featuring a FastAPI backend and PyQt6 frontend. This app fetches real-time weather data from OpenWeatherMap API, processes it, and displays it in a user-friendly interface.

## Features

- Real-time weather data fetching
- Current weather and forecast display
- Data caching to reduce API calls
- Responsive GUI with search functionality
- Settings panel for user preferences
- Charts and graphs for visual data representation
- Geolocation for automatic location detection
- Severe weather alerts and notifications
- Mini-widget for system tray or desktop

## Tech Stack

- Backend: FastAPI
- Frontend: PyQt6
- Data Processing: Pandas
- Database: SQLAlchemy with SQLite
- API: OpenWeatherMap
- Testing: Pytest, Pytest-Qt
- Deployment: PyInstaller
- Dependency Management: Poetry

## Installation

1. Ensure you have Python 3.8+ and Poetry installed on your system.

2. Clone the repository:
git clone https://github.com/rufus800/weather-app.git
cd weather-app

3. Install dependencies:

poetry install
4. Set up environment variables:
Create a `.env` file in the root directory and add your OpenWeatherMap API key:

API_KEY=your_openweathermap_api_key_here




The executable will be created in the `dist/` directory.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- OpenWeatherMap for providing the weather data API

- FastAPI, PyQt6, and other open-source libraries used in this project

This README provides an overview of the project, its features, tech stack, and instructions for installation, usage, and development. It also includes sections on deployment, contributing, licensing, and acknowledgements.



