# Treasure Island Sentence Generator

| Category         | Requirement                                                                                         |   ✅   |
| :--------------- | --------------------------------------------------------------------------------------------------- | :---: |
| **🐳 Docker**     | Repository contains a `Dockerfile` and a `docker-compose.yml` file                                  |   ✅   |
| **🐳 Docker**     | `Dockerfile` and `docker-compose.yml` file build without error                                      |   ✅   |
| **⚙️ Deployment** | Project deployed on CapRover using your own domain                                                  |   ✅   |
| **⚙️ Deployment** | Uptime monitored by FreshPing or another health check service                                       |   ✅   |
| **📝 Docs**       | `README` includes [badges](https://shields.io) for build status, and website monitoring             |   ✅   |
| **📝 Docs**       | `README` includes instructions on how to build and run your container                               |   ✅   |

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fstats.uptimerobot.com%2Fsvlcuvffwe&label=Website%20Status)](https://stats.uptimerobot.com/svlCuvffWe)

## How to Build and Run the Container

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/treasure-island-generator.git
   cd treasure-island-generator
   ```

2. Build the Docker image:
   ```
   docker build -t treasure-island-generator .
   ```

3. Run the container:
   ```
   docker run -p 5001:5001 treasure-island-generator
   ```

4. Access the application in your web browser at `http://localhost:5001`

Alternatively, you can use Docker Compose:

1. Run the following command in the project directory:
   ```
   docker-compose up
   ```

2. Access the application in your web browser at `http://localhost:5001`

To stop the container, press `Ctrl+C` in the terminal where it's running.