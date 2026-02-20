# Getting Started with GitHub Copilot

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A hands-on GitHub Skills exercise for learning GitHub Copilot through building a school activity management system.

> **Note:** This repository was generated from the [GitHub Skills: Getting Started with GitHub Copilot](https://github.com/skills/getting-started-with-github-copilot) template.

## Overview

This project is part of GitHub's official Skills curriculum. It provides a practical, step-by-step exercise that teaches developers how to use GitHub Copilot effectively. The sample application is a **Mergington High School Activity Management System** — a FastAPI-powered web app that lets students browse and sign up for extracurricular activities.

## Features

- **Activity Listings** — View available extracurricular activities with descriptions, schedules, and remaining spots
- **Student Sign-Up** — Register for activities via a simple web form with email validation
- **RESTful API** — FastAPI backend with automatic OpenAPI documentation
- **Static Frontend** — Responsive HTML/CSS/JS interface served by FastAPI
- **DevContainer Support** — Pre-configured development environment for VS Code with GitHub Copilot

## Prerequisites

- [Python 3.13+](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installation/)
- [Git](https://git-scm.com/downloads)
- A [GitHub Copilot](https://github.com/features/copilot) subscription (for the exercise)

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/skills-getting-started-with-github-copilot.git
   cd skills-getting-started-with-github-copilot
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Start the FastAPI development server:
   ```bash
   uvicorn src.app:app --reload
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

3. Access the interactive API documentation at:
   ```
   http://localhost:8000/docs
   ```

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3.13 | Backend runtime |
| FastAPI | Web framework and REST API |
| Uvicorn | ASGI server |
| HTML5 / CSS3 | Frontend structure and styling |
| JavaScript | Client-side interactivity |
| VS Code DevContainers | Development environment |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
