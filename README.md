# Ollama DeepSeek Docker

A Dockerized setup for running DeepSeek models with Ollama.

## Prerequisites

- [Docker](https://www.docker.com/) installed on your system.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/ollama-deepseek-docker.git
   cd ollama-deepseek-docker
   ```

2. Build the Docker image:
   ```sh
   docker build -t ollama-deepseek .
   ```

## Usage

Start the container:
```sh
docker run --rm -p 7860:7860 ollama-deepseek
```

Access the service at [http://localhost:7860](http://localhost:7860).

## Configuration

- Edit environment variables or Dockerfile as needed for custom settings.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Author

- Yatheendraprakash Govindaraju (yatheep@gmail.com)
