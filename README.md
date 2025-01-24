# Smart Traffic Light Management System

## Overview

The Smart Traffic Light Management System is designed to optimize traffic flow at intersections by dynamically adjusting signal timings based on real-time traffic conditions. This system aims to reduce congestion, improve travel times, and enhance overall road safety.

## Features

- **Real-Time Traffic Monitoring:** Utilizes sensors/cameras to gather live traffic data.
- **Dynamic Signal Control:** Adjusts traffic light durations based on current traffic density.
- **Emergency Vehicle Detection:** Prioritizes emergency vehicles to ensure swift passage.
- **Data Analytics:** Collects and analyzes traffic data for future infrastructure planning.
- **Pygame Simulation:** Provides a visual simulation of the traffic light system using the Pygame library.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/dev0052/Smart-Traffic-Light-Management-System.git
   cd Smart-Traffic-Light-Management-System
   ```

2. **Set Up the Environment:**

   - Ensure you have Python 3.x installed.
   - Create and activate a virtual environment:

     ```bash
     python3 -m venv venv
     source venv/bin/activate  # On Windows, use venv\Scripts\activate
     ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Settings:**

   - Update any configuration files with your specific settings (e.g., camera IPs, sensor configurations).

## Usage

1. **Start the System:**

   ```bash
   python main.py
   ```

2. **Access the Dashboard:**

   - Open your web browser and navigate to `http://localhost:8000` to view the traffic management dashboard.

3. **Run the Pygame Simulation:**

   - To view the visual simulation of the traffic light system, run the following command:
     ```bash
     python simulation.py
     ```
   - The simulation will display a graphical representation of the traffic lights and their dynamic behavior.

## Project Structure

- `main.py`: Entry point of the application.
- `simulation.py`: Pygame-based simulation of the traffic light system.
- `config/`: Configuration files.
- `src/`: Source code for various modules.
- `docs/`: Documentation and related resources.

## Contributing

We welcome contributions to enhance the system's capabilities. Please fork the repository and submit pull requests for review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We would like to thank all contributors and the open-source community for their invaluable support.
