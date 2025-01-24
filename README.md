# OpenModelica Desktop App

## Overview
This project is a desktop application built using Python and PyQt6 that allows users to execute OpenModelica-generated models with specific simulation parameters. The application provides a graphical user interface to select an executable model, set simulation start and stop times, and run the simulation.

## Features
- **Executable Selection:** Browse and select the OpenModelica-generated executable file.
- **Input Fields:** Specify simulation start and stop times.
- **Validation:** Ensures valid start and stop time inputs (0 <= start < stop < 5).
- **Simulation Execution:** Run the model with provided parameters via a button click.

## Technologies Used
- **Python 3.6+**
- **PyQt6**
- **OpenModelica**
- **Windows 10/11 OS**

## Installation

### Prerequisites
1. Install **Python 3.6+** from [python.org](https://www.python.org/downloads/).
2. Install **OpenModelica** from [openmodelica.org](https://openmodelica.org/download/download-windows).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/openmodelica-desktop-app.git
   cd openmodelica-desktop-app
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app/main.py
   ```

## Usage
1. Launch the application.
2. Click **Browse** to select the OpenModelica executable.
3. Enter the simulation start time (0-4).
4. Enter the simulation stop time (1-5).
5. Click **Run Simulation** to start the model.

## File Structure
```
openmodelica-desktop-app/
│-- app/
│   │-- main.py               # PyQt6 application
│   │-- requirements.txt       # List of dependencies
│   └-- README.md              # Instructions
│-- model/
│   └-- TwoConnectedTanks/      # Compiled model executable and dependencies
│-- .gitignore
└-- LICENSE
```

## Validation Rules
- Ensure `0 <= start time < stop time < 5`.
- The application provides error messages for invalid inputs.

## Submission Guidelines
- Upload code and compiled model files to a GitHub repository.
- Share the repository link to `contact-esim@fossee.in` before the deadline.

## License
This project is licensed under the MIT License.

## Contact
For queries, contact: `govindup63@gmail.com`

