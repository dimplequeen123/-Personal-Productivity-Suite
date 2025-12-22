# -Personal-Productivity-Suite
A comprehensive, modular command-line interface (CLI) suite designed to streamline daily workflows. Built with a focus on Object-Oriented Programming (OOP), Data Persistence, and Modular Architecture.

🌟 Key Features
Notes Manager: Full CRUD operations with JSON-based storage and timestamp tracking.

File Organizer: Automated sorting of cluttered directories based on file extensions.

Smart Calculator: Advanced arithmetic operations with error handling for edge cases.

Timer & Stopwatch: Precise time-tracking tools for productivity sessions (Pomodoro-ready).

Unit Converter: Quick conversion between metric and imperial systems.

Data Security: Automated backup and restore functionality for your local database.

🏗 System Architecture
The project is built using a Modular Design Pattern. Each tool exists as an independent class, allowing for easy scalability without affecting the core engine.

⚙️ Installation & Setup
Prerequisites
Python 3.8 or higher

VS Code (recommended)

Local Setup
Clone the repository:

Bash

git clone https://github.com/yourusername/personal-productivity-suite.git
cd personal-productivity-suite
Create a virtual environment:

Bash

python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
Run the application:

Bash

python main.py

📂 Project Structure
Plaintext

personal-productivity-suite/
├── main.py                # Application Entry Point
├── modules/               # Core Logic Modules
│   ├── notes_manager.py   # JSON Data Handling
│   ├── file_organizer.py  # OS/FileSystem Logic
│   └── calculator.py      # Math Logic
├── data/                  # Persistent Storage
│   ├── notes.json         # User Data
│   └── backups/           # Auto-generated Backups
├── docs/                  # Technical Manuals
├── tests/                 # Unit Tests
└── requirements.txt       # Project Dependencies

🧪 Technical Implementation Details
Data Persistence: Uses the json and csv modules to ensure data survives application restarts.

Error Handling: Implemented custom Exception classes to handle invalid user inputs and file system permissions.

Environment Interaction: Utilizes the os and shutil libraries for high-level file operations.

🤝 Contributing
Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📜 License
Distributed under the MIT License. See LICENSE for more information.
