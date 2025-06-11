# Weather Chatbot

A beautiful and interactive weather chatbot that provides accurate weather information for any city around the world.

## Features

- Modern and responsive UI design
- Real-time weather information
- Detailed weather statistics including temperature, humidity, and wind speed
- Weather icons and descriptions
- Easy-to-use chat interface

## Setup Instructions

1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory and add your OpenWeatherMap API key:
   ```
   OPENWEATHER_API_KEY=your_api_key_here
   ```
   You can get a free API key by signing up at [OpenWeatherMap](https://openweathermap.org/api)

4. Run the application:
   ```bash
   python app.py
   ```

5. Open your web browser and navigate to `http://localhost:5000`

## Usage

1. Type a city name in the input field
2. Press Enter or click the send button
3. The chatbot will display the current weather information for the specified city

## Technologies Used

- Python
- Flask
- OpenWeatherMap API
- HTML5
- CSS3
- JavaScript
- Socket.IO 