# Django Weather Application

## Overview
This is a Django-based weather application that provides real-time weather data for various cities. It fetches weather information using an external API and displays it in a user-friendly web interface.

## Features
- Search for weather information by city name
- Display current temperature, humidity, wind speed, and weather conditions
- User-friendly interface built with HTML, CSS, and Django templates
- API integration for real-time weather data

## Technologies Used
- **Backend:** Django, Python
- **Frontend:** HTML, CSS
- **Database:** SQL (SQLite/PostgreSQL/MySQL)
- **APIs:** OpenWeatherMap API (or any other weather API)

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Cbeforeanya/Weather-application.git
   cd Weather-application
   ```

2. **Create a virtual environment and activate it:**
   ```sh
   python -m venv test
   source test/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the project root
   - Add your API key for weather data:
     ```sh
     WEATHER_API_KEY=your_api_key_here
     ```

5. **Run database migrations:**
   ```sh
   python manage.py migrate
   ```

6. **Run the development server:**
   ```sh
   python manage.py runserver
   ```
   Open `http://127.0.0.1:8000/` in your browser to use the application.

## Configuration
- Replace `your_api_key_here` in the `.env` file with your actual API key.
- Modify `settings.py` to adjust database settings if necessary.

## Usage
- Enter a city name in the search bar.
- Click the search button to fetch weather data.
- View the current temperature, weather condition, wind speed, and humidity.

## Future Enhancements
- Add a feature to display a 7-day weather forecast.
- Improve UI with better styling and animations.
- Implement user authentication to save favorite locations.
- Support multiple weather API providers.

## Contributing
Feel free to contribute by forking the repository and submitting pull requests. Any improvements and suggestions are welcome!

## License
This project is licensed under the MIT License.

---

### Author
**Chaitanya BK** - A Django developer passionate about building web applications.

For any queries, reach out at chaitanyabk3@gmail.com.
