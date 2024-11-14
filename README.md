# Smart Traffic System Simulation

## Overview
The Smart Traffic System is a Python-based project that simulates traffic signal management using the Pygame library. It aims to demonstrate intelligent traffic control by simulating real-world traffic conditions and managing signals effectively.

## Features
- **Traffic Signal Simulation**: Controls and updates signal states for multiple intersections.
- **Visual Representation**: Utilizes Pygame to display graphical representations of traffic lights.
- **Configurable Timers**: Customizable green, yellow, and red signal durations.
- **Real-Time Simulation**: Updates signal states dynamically with a focus on realistic timing.

## Requirements
- Python 3.11 or later
- Pygame 2.6.1 or later

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Vipul251/Real_Traffic_Monitoring_System.git
   cd Smart-Traffic-System
   ```
2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. **Install Dependencies**:
   ```bash
   pip install pygame
   ```

## File Structure
```
Smart-Traffic-System/

|-- images/
|   |-- signals/
|   |   |-- red.png
|   |   |-- yellow.png
|   |   |-- green.png
|-- simulation.py
|-- README.md
|-- requirements.txt
```

## Running the Simulation
To run the traffic simulation, execute the following command:
```bash
python -u "d:\Smart-Traffic-System\simulation.py"
```

## Troubleshooting
### Common Issues
1. **ModuleNotFoundError: No module named 'pygame'**:
   - Ensure Pygame is installed in the active virtual environment.
   - Run `pip install pygame` if needed.

2. **FileNotFoundError for Image Paths**:
   - Verify that the images (e.g., `red.png`, `yellow.png`, `green.png`) are present in the `images/signals` directory.
   - Use absolute paths or check the working directory with:
     ```python
     import os
     print(os.getcwd())
     ```

## Customization
- Modify the signal timings by updating the respective timer variables in `simulation.py`.
- Replace image files in `images/signals/` to customize the visual appearance of the traffic lights.

## Contribution
Feel free to fork the repository, make improvements, and submit pull requests. Your contributions are welcome!

## License
This project is licensed under the MIT License. See `LICENSE` for more details.

## Contact
For any questions or feedback, please reach out to:
- **Email**: stl.1547vipul@gmail.cpm
- **GitHub**: (https://github.com/Vipul251/Real_Traffic_Monitoring_System.git)

