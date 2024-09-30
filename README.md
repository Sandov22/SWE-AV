# SWE-AV CARLA Project

## Project Overview
This project utilizes the CARLA simulator for autonomous vehicle development. Our team is focusing on implementing and testing various autonomous driving algorithms and scenarios using CARLA's Python API.

## Team Members
- Alejandro Sandoval
- Marcelo Moreno
- Sebastian Bohrt
- Aahan Mehta

## Project Structure
- `src/`: Contains the main source code
  - `main.py`: Entry point of the application
  - `vehicle_control.py`: Handles vehicle spawning and control
  - `sensor_management.py`: Manages sensor data collection
- `tests/`: Contains unit tests
- `requirements.txt`: Lists all Python dependencies
- `README.md`: This file

## Setup and Installation
1. Ensure you have Python 3.7 or later installed.
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Make sure you have CARLA simulator installed or accessible.

## Running the Project
To run the main script:
```
python src/main.py
```

## Testing
To run the unit tests:
```
python -m unittest discover tests
```

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
[Insert chosen license here]

## Acknowledgments
- CARLA Simulator team for providing the simulation environment
- [Any other acknowledgments]

## Contact
For any queries regarding this project, please contact any of the team members mentioned above.