

# Bump Buster

Bump Buster is a mobile application designed to detect and report potholes using inbuilt sensors in smartphones, providing a compact and efficient alternative to traditional bump integrators. This tool aims to streamline and modernize road quality assessments for the construction industry by reducing equipment size by 70% and offering actionable data through an interactive dashboard.

## Features

- **Real-Time Monitoring**: Users can activate monitoring mode to detect bumps and potholes on roads while driving.
- **Detailed Reports**: Provides comprehensive reports on detected bumps with timestamps and locations.
- **Interactive Dashboard**: Offers visual insights, trends, and maps of reported potholes for easy analysis.
- **Data Collection and Management**: Efficiently collects sensor data to provide consistent and accurate readings.
  
## Technologies Used

- **Flutter**: Cross-platform mobile development framework.
- **MongoDB**: Database for storing sensor data and reports.
- **Flask**: Backend server for data processing and API management.
- **Mobile Sensors**: Utilizes accelerometers and GPS for pothole detection.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BumpBuster.git
   ```
2. Navigate to the `App` directory and install the required Flutter packages:
   ```bash
   flutter pub get
   ```
3. In the `Server` directory, set up the Flask server and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure MongoDB for data storage and update the connection details in the Flask backend.
  
## Usage

1. Launch the server:
   ```bash
   python app.py
   ```
2. Run the mobile app on an emulator or connected device:
   ```bash
   flutter run
   ```
3. Start the monitoring feature within the app to begin collecting data.
  
## Contributing

Contributions are welcome! Please fork the repository and create a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License.

--- 

Let me know if you'd like any adjustments to better suit your repository.
