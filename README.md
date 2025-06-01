# Ollama DeepSeek Docker

A Dockerized setup for running DeepSeek models with Ollama.

## Prerequisites

- [Docker](https://www.docker.com/) installed on your system.
- [Docker Compose](https://docs.docker.com/compose/) installed.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/yathee/ollama-deepseek-docker.git
   cd ollama-deepseek-docker
   ```

## Usage

Start the services using Docker Compose:
```sh
docker compose up -d
```

- The Ollama API will be available at [http://localhost:11434](http://localhost:11434).
- The Open WebUI will be available at [http://localhost:3000](http://localhost:3000).

To stop the services:
```sh
docker compose down
```

## Configuration

- Edit environment variables in `docker-compose.yml` as needed for custom settings.
- Model data is persisted in Docker volumes (`ollama-data`, `openwebui-data`).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Author

- Yatheendraprakash Govindaraju (yatheep@gmail.com)
