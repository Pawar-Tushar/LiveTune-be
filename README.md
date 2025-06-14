# LiveTune-be

## Description

**LiveTune-be** is the backend server for the [LiveTune](https://github.com/Live-Tune) project—an open-source, web-based music streaming app that allows users to enjoy real-time music together using YouTube links. The backend handles room creation, user sessions, and core logic for live interactions.

## Features

  
- **Room Management**: Create, update, delete, and list public or private rooms.

- **User Sessions**: Lightweight user tracking (no login required; ephemeral session).

- **Real-time Functionality**: Enables live updates and interactions within rooms.

## Technologies Used

- Python 3.x
- Flask
- Flask-SocketIO
- OpenAPI

## Getting Started

### Prerequisites

Make sure you have Python 3.9+ installed.

### Installation


1. **Clone the repository**

```bash
git clone git@github.com:Live-Tune/LiveTune-be.git
cd LiveTune-be
```

2. **Create and activate a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the application**

```bash
python run.py
```

## API Documentation

- The OpenAPI specification is available at [`openapi.yaml`](./docs/openapi.yaml).

## Contributing


We welcome contributions! Please read our [CONTRIBUTING.md](./CONTRIBUTING.md) guide for detailed instructions on how to get involved.

If you're new to the project, check out the issues labeled [`good first issue`](https://github.com/Live-Tune/LiveTune-be/labels/good%20first%20issue) to get started.