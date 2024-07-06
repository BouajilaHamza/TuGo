# TuGo: Tunisian Transport Guide

Welcome to the **TuGo** (Tunisian Transport Guide) open-source project! TuGo aims to provide real-time information and community-driven insights for public transport in Tunisia. Whether you're a daily commuter or an occasional traveler, TuGo helps you navigate the transport system efficiently.

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
TuGo is a mobile app built using Flutter, MongoDB, and FastAPI. It allows users to:
- Check real-time bus and train schedules.
- Report delays, crowded vehicles, and other issues.
- Share tips and experiences with fellow commuters.

## Tech Stack
- **Flutter**: Cross-platform framework for building beautiful UIs.
- **MongoDB**: Scalable NoSQL database for storing transport data.
- **FastAPI**: Fast, asynchronous Python framework for building APIs.

## Getting Started
1. **Prerequisites**:
   - Install [Flutter](https://flutter.dev/docs/get-started/install).
   - Set up a [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account or install MongoDB locally.
   - Install [Python](https://www.python.org/downloads/) and [FastAPI](https://fastapi.tiangolo.com/tutorial/first-steps/).

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/tugo.git
   cd tugo
   ```

3. **Frontend (Flutter)**:
   - Navigate to the `frontend` directory.
   - Run the app on an emulator or physical device:
     ```bash
     flutter run
     ```

4. **Backend (FastAPI)**:
   - Navigate to the `backend` directory.
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Configure MongoDB connection in `main.py`.
   - Run the FastAPI server:
     ```bash
     uvicorn main:app --reload
     ```

5. **Contributing**:
   - Check the [open issues](https://github.com/yourusername/tugo/issues) for tasks.
   - Fork the repository and create a new branch for your feature or bug fix.
   - Make your changes and submit a pull request.

## Contributing
We welcome contributions from the community! Here's how you can contribute:
- Report bugs or suggest enhancements by opening an issue.
- Submit pull requests for new features, improvements, or bug fixes.
- Help improve documentation or write tests.

## License
TuGo is open-source and available under the [Apache 2.0 License](LICENSE). Feel free to use, modify, and share!

Let's make Tunisia's public transport better together! 🚌🇹🇳